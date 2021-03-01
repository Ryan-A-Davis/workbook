# SQL

## What is the difference between a primary key and a foreign key

A primary key is n identifier on a table that distinguishes it from other tables. A Foreign key is a local key, that identifies and joins on foreign tables.

# What is an Alias?
An alias is an abstraction or renaming of a variable. It gives reference to an original variable under a different name.

## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  
  PRIMARY KEY (id)

)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctorspatients (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)

SELECT 
patient.*,
doctor.*

FROM patients patient
JOIN doctors doctor ON doctor.doctorId = doctorId
WHERE patient.doctorId = doctor.doctorId;
