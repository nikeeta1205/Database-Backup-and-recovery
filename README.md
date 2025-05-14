#Databse Backup and recovery

COMPANY : CODTECH IT SOLUTIONS

NAME : Nikeeta Nitin Sawant

INTERN ID : CT04DK245

Domain : sql

Duration : 4 WEEKS

MENTOR : Neela Santosh Kumar

# Description
BACKUP AND RECOVERY SCRIPTS, AND DOCUMENTATION OF THE PROCESS.
As part of my internship project, I was assigned a real-world task to demonstrate how to back up a database and restore it in case of failure. This task is very important in actual business environments where data loss due to corruption, human error, or system failure can cause serious problems. I used MySQL as the database system for this task, and I performed the entire activity on my personal system using MySQL Workbench and the terminal/command prompt for command-line operations. The task was divided into several key stages: database creation, data insertion, backup using mysqldump, simulating failure by dropping the database, and finally, restoring it using the backup file. I began by creating a new database called BackupDemo. Inside this database, I created a single table named Students which had three fields: StudentID, StudentName, and Department. This structure was chosen to keep the schema simple yet meaningful for demonstration. I inserted a few sample records representing real students to make the backup meaningful. After verifying that the data had been inserted correctly using a SELECT * FROM Students query, I proceeded to the backup stage. I exited the MySQL interface and used the mysqldump command from the terminal. The syntax I used was mysqldump -u root -p BackupDemo > backupdemo.sql. This command created a file named backupdemo.sql in the working directory, which contained the full SQL commands to recreate both the table and the data. This step made me realize the usefulness of mysqldump in taking quick and complete backups of a database in just one line of code. Once the backup was confirmed, I simulated a database failure scenario by dropping the entire database using the DROP DATABASE BackupDemo; command. This mimicked an accidental data loss situation, something that could realistically happen if a user deletes a database or if the server crashes. At this point, the database was gone from MySQL. The next step was to test whether I could restore it successfully using the backup I had created earlier. For this, I used the mysql -u root -p < backupdemo.sql command in the terminal. This command executed all the SQL statements from the backup file, and within a few seconds, the entire database was restored. I re-entered MySQL Workbench, used the USE BackupDemo; command, and ran SELECT * FROM Students; to verify the restoration. To my satisfaction, all the data was back exactly as it was before the deletion. This task taught me several important things. First, the importance of regularly taking backups, especially in environments where important data is handled daily. Second, it gave me practical experience with using terminal commands and understanding how tools like mysqldump and mysql can be used not just for backups, but also for migration and replication. Finally, I learned how to simulate real-life issues in a controlled environment and test disaster recovery steps safely. Overall, this was one of the most hands-on and educational tasks of my internship. It boosted my confidence in managing databases and helped me understand how professional organizations ensure data safety through regular backups and tested recovery plans. This task might look simple, but it carries deep responsibility when applied in the real world.



