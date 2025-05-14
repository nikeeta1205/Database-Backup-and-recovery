#Databse Backup and recovery

COMPANY : CODTECH IT SOLUTIONS

NAME : Nikeeta Nitin Sawant

INTERN ID : CT04DK245

Domain : sql

Duration : 4 WEEKS

MENTOR : Neela Santosh Kumar

#Description
During my internship, I was assigned a critical task to understand and demonstrate how to back up a database and restore it in case of failure.
I used MySQL for this task and performed all steps using MySQL Workbench and the terminal/command prompt. The objective was to simulate a real-
world scenario where a database might be accidentally deleted or corrupted and needs to be recovered without losing any data.I started by creating 
a simple database called BackupDemo which included one table Students. I added three records with sample student information to simulate real data. 
Once the database and data were ready, I exited MySQL and used the mysqldump command in the terminal to back up the entire database. This created a 
.sql file that contains all SQL commands needed to recreate the database with its structure and data.To simulate a failure scenario, I dropped the
entire BackupDemo database. This was a scary but essential part of the process to test whether the backup works or not. After dropping the database, 
I restored it using the backup file through the MySQL terminal. The restore was successful, and all data came back exactly as it was before.Through 
this exercise, I learned the importance of regular backups, especially in production environments where data loss can cause serious issues. I also 
understood how mysqldump works and how to restore a .sql file. This task gave me confidence in handling real-world data recovery scenarios and helped 
me develop my problem-solving and practical database management skills. This hands-on learning was one of the most useful parts of my internship.
