# SQL Relationships

![replace_me](https://codeworks.blob.core.windows.net/public/assets/img/illustrations/placeholder.svg)

> **📖 [Relationships](https://codeworksacademy.com/fs-student-guide/resources/wk11/02-MySQL-Relationships)**

## Questions

1. What is the difference between a `primary key` and a `foreign key`

A primary key is used to assure the value in the particular column is unique. The foreign key provides the link between the two tables. A primary key generally focuses on the uniqueness of the table. It is a column or a set of columns that uniquely distinguishes every row in the database. It means it should not have any duplicate value. Also, it doesn’t contain a NULL value. A foreign key is generally used to build a relationship between the two tables. The major purpose of the foreign key is to sustain data integrity between two separate instances of an entity.

2. What is an `Alias`?

A renaming convention to create aliases for lengthy fully qualified names or class names. This can come in handy if there is a long namespace or class name that you do not want to have to keep typing out each time. It is also a useful tool to resolve namespace clashes within your code when identical types are imported into your code base.

3. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

SELECT
* FROM doctors
JOIN * FROM patients;
WHERE patient.doctorId = doctors.id

```SQL
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

```

## Afternoon Assignment Link

**[Repo](https://github.com/fullmer24/AllSpice)**

Identify at least 1 takeaway from today's assignment
