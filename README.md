# Simbir.Health

Simbir.Health is a microservice application for managing clinical processes, allowing the registration of patients, doctors, managing appointment schedules, medical records, and documentation. The project is focused on improving the efficiency of healthcare institutions and ensuring data security.

## Main Task

### Account Service
- URL: `http://localhost:8090/ui-swagger`
- Description: User management, authentication, and authorization.

### Hospital Service
- URL: `http://localhost:9080/ui-swagger`
- Description: Manage hospital data.

### Timetable Service
- URL: `http://localhost:9060/ui-swagger`
- Description: Manage schedules for doctors and hospitals.

### Document Service
- URL: `http://localhost:9070/ui-swagger`
- Description: Manage patient medical records.

## Technologies Used

- **Java**: Used for developing microservices, leveraging its robust ecosystem for building scalable applications.
- **PostgreSQL**: The primary relational database used for data storage and management, providing strong ACID compliance and support for complex queries.
- **JWT (JSON Web Tokens)**: Utilized for secure authentication and authorization between services, allowing for stateless session management.
- **Docker**: Employed for microservice containerization, ensuring consistency across development and production environments while simplifying deployment.
- **Swagger**: Used for API documentation, enabling interactive API exploration and facilitating easier integration with front-end applications.
- **Feign**: A declarative web service client for simplifying the HTTP API consumption in microservices, allowing for cleaner and more maintainable code.
- **Gradle**: The build automation tool used for managing dependencies, compiling code, and packaging applications, facilitating a smooth development workflow.

## Running the Application

To run all microservices and the database, execute the following command:

```bash
git clone --recurse-submodules https://github.com/Dr-EljanNajafov/simbirSoft-hackathon
cd simbirSoft-hackathon
docker-compose up -d
