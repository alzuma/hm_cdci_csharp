# Homework Assignment: CI/CD Pipeline for a C# Todo API with SQLite

## Objective
The objective of this assignment is to set up a CI/CD pipeline for a C# API that implements a Todo application, storing data in SQLite. This assignment will test your ability to automate the build and deployment process of a C# API with a database backend.

## Requirements

### C# API - Todo Application
- Create a C# API using a framework like ASP.NET Core.
- Implement a Todo application with the following endpoints:
  - `GET /api/todos` - Retrieve a list of all todos.
  - `GET /api/todos/{id}` - Retrieve a single todo by ID.
  - `POST /api/todos` - Create a new todo.
  - `PUT /api/todos/{id}` - Update an existing todo by ID.
  - `DELETE /api/todos/{id}` - Delete a todo by ID.
- Use SQLite as the database to store todo items.
- Ensure that the API is stored in a version control system (e.g., Git) with a repository on GitHub or GitLab.

### CI/CD Pipeline
- Use a CI/CD tool of your choice (e.g., Jenkins, Travis CI, GitHub Actions, GitLab CI/CD) to automate the build and deployment process.
- Set up a CI pipeline that:
  - Builds the C# API.
  - Runs unit tests on the API.
  - Generates a build artifact (e.g., a deployable package).
- Set up a CD pipeline that:
  - Deploys the built API to a staging environment (can be a virtual machine, container, or any cloud platform).
  - Performs any necessary database migrations.
  - Ensures that the API is up and running in the staging environment.
  - Promotes the API to a production environment after successful staging testing.

### Version Control Integration
- Configure the CI/CD pipeline to trigger automatically whenever changes are pushed to the repository.

### Documentation
- Provide clear and concise documentation on how to set up and run the CI/CD pipeline.
- Include a README file in your repository with instructions for setting up the development environment, building, deploying, and testing the API.

### Bonus Points (Optional)
- Implement a rollback mechanism in your CD pipeline in case of deployment failures.
- Use infrastructure as code (IaC) tools like Terraform or AWS CloudFormation to provision the staging and production environments.

## Submission
Share the link to your GitHub or GitLab repository containing the C# API for the Todo application and the configured CI/CD pipeline. Include any necessary instructions or documentation in the repository.

## Evaluation Criteria
Your assignment will be evaluated based on the same criteria as the previous assignment, with a focus on the correctness and functionality of the Todo API and the integration of SQLite as the database backend.
