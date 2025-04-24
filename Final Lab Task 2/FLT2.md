# Finals Lab Task 2 - Transforming ER Model to Relational
In this lab assignment, we were provided with a sample Entity-Relationship (ER) diagram and asked to transform it into a relational database using MySQL. The task involved recognizing the relevant entities and their attributes to create a well-structured and functional database. Additionally, we had to define suitable primary and foreign keys to correctly establish the relationships between the tables.


In this activity, i’ll show how to transform ER Model to Relational Tables using mySQL Workbench.
The following are the data attributes that we have to create inside a table:


![Act](https://github.com/user-attachments/assets/0a3ff0ac-b85c-451c-a0d2-427f87bba7df)


## Queries
1. Query for Student Table

Relation: One-to-Many

![1](https://github.com/user-attachments/assets/22fb6d50-4aac-4a16-9925-9a6f358260dd)

2. Query for Assignment Table

Relation: One-to-Many

![22](https://github.com/user-attachments/assets/313acc78-edae-450b-aa1e-2e106d3329f7)

3. Query for Submission Table

Relation: Many-to-One

![3](https://github.com/user-attachments/assets/9317f549-0673-4774-be7d-7977bc70f6ef)


## Table Structures
1. Student Table Structure
   
Meaning: One Student can have Many Submissions, Each Submission requires a valid Student.

![4](https://github.com/user-attachments/assets/e404d978-d31e-464a-a342-43a920f59610)

2. Assignment Table Structure

 Meaning: One assignment can have Many Submissions connected with it.

![5](https://github.com/user-attachments/assets/a072338e-0497-4d86-9b6e-cda278a155e0)


3. Submission Table Structure

 Meaning: Many Submissions belong to One Student.

 Meaning: Many Submissions are linked to a One Assignment.

 
![6](https://github.com/user-attachments/assets/49ac3f01-3985-46f5-bfda-102ae0f012ef)

## Relational Tables


![er](https://github.com/user-attachments/assets/40e1b741-ab31-445c-abde-c06e169f48a5)

## Relational Tables


![rt](https://github.com/user-attachments/assets/3b68f25e-00a7-410e-bfb9-ee19827d7e78)
