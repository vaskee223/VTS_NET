# VTS_NET
ASP .NET Core (8.0) project for the January exam

Library with class materials for students

- 3 roles (Student, Professor, Admin)
- JWT Authentication with Core Authentication JwtBearer
- XAMPP MariaDB MySQL DB
- Database seeding
- Pomelo Framework with MySqlConnector for MySQL compatibility
- Swashbuckle Swagger, Identity, Entity packages
- CRUD functionality for all models (User, Subject, Material)
- UserSubject pivot table for many-many relationship
- Custom configured SwaggerUI to match access ability of each role
- All endpoints are tagged and with descriptions
- 23 endpoints, of which some use different logic depending on user's role
