# Day 2 - MYSQL RELATIONSHIPS (MANY-TO-MANY)

Read Dotnet WebAPI's > Relationships, and answer the following questions

What is the difference between a primary key and a foreign key

        A primary key constrain is a column that uniquely identifies every row in the table of the relational database management system, while foreign key is a column that creates a relationship between two tables. Primary Key never accepts null values whereas foreign key may accept multiple null values.

What is an Alias?

        SQL aliases are used to give a table, or a column in a table, a temporary name.
        Aliases are often used to make column names more readable.An alias only exists for the duration of that query.

Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

CREATE TABLE doctors (
id INT NOT NULL AUTO_INCREMENT,
-- CODE OMITTED
PRIMARY KEY (id)
)

CREATE TABLE patients (
id INT NOT NULL AUTO_INCREMENT,
-- CODE OMITTED
PRIMARY KEY (id)
)

CREATE TABLE doctors (
id INT NOT NULL AUTO_INCREMENT,
doctorId INT NOT NULL,
patientId INT NOT NULL,

FOREIGN KEY (doctorId)
REFERENCES doctors(id),
FOREIGN KEY (patientId)
REFERENCES patients(id),
)

        SELECT d., p. dp.Id as doctorsPatientsId dp.doctorId as doctorId, dp.patientId as patientId FROM doctors_patients dp JOIN doctors d ON d.id = dp.doctorId JOIN patients p ON p.id = dp.patientId WHERE doctorId = @id;
