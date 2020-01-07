**TODO APP**

Brief

This application is meant to prepare us for the forth coming project.

 Back-end stack.

- C# (ASP.NET CORE)

- POSTGRESSQL

- SWAGGER for Documentation

Below is a simple ER diagram that translates to entities in the database.

![](file:///C:/Users/muyin/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

Design Principles to be followed.

1) We intend to develop a rest application following the DRY principle for each entity.

2) The API should follow the known API standards such as (POST, GET, PUT, DELETE) however for the DELETE, we are using safe delete. We don't delete a record in the database.

3) We are using stateless principle, meaning for every endpoint, validation and authentication is required

4) We are following an MVC architecture, but using Small Controller Fat Services. This means logic is being put in the Service Layer

5) We are following TDD approach

6) The permissions data relates to every single function in the service layer.
