# User Crud With NestJS

Simple user crud using all industry standards.

## Dependencies

- Node.js version 18 or higher.
- Docker.
- VS Code or similar.
- Insomnia or similar.
- NestJS CLI.
- Prisma ORM CLI.

## Project Requirements

### Business rules

- The name, email and password fields will be mandatory.
- The createdAt field will be optional.
- The user must not be able to register with a duplicate email address.

### Functional requirements

- It should be possible to register.
- It must be possible to authenticate.
- It must be possible to display a user's data.
- It must be possible to list all users.
- It must be possible to update a user's name.
- It must be possible to update a user's password.
- It must be possible to delete a user.

### Non-functional requirements

- The user's password must be encrypted.
- Application data must be persisted in a Postgres database.
- All data lists must be paginated with 15 items per page.
- The user must be identified by a JWT (JSON Web Token).
