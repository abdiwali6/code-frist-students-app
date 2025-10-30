# code-frist-students-app
Description
This is a simple C# console application that uses Entity Framework Code-First to create a database called StudentDB and add one student record to it.
What is Code-First?
Code-First means we create the database using C# classes instead of designing it first in SQL. Entity Framework automatically creates the database based on our code.

How It Works
A Student class defines the data (Id, Name, EnrollmentDate, etc.).
A StudentContext class connects to the database.
When the app runs, it creates the database and adds one student automatically.
