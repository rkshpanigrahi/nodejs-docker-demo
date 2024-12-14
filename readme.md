# Express.js Application

This is a simple Express.js application that serves a "Hello World!" message.

## Prerequisites

- Node.js
- npm (Node Package Manager)

## Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```sh
    cd <project-directory>
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

## Running the Application

To start the application, run the following command:
```sh
npm start
```
 

 
The application will be available at
http://localhost:3000.

## Files

- `index.js`: Main application file that sets up the Express.js server.
- `index-db.js`: Application file that connects to a MySQL database and tracks visits.
- `docker-compose.yml`: Docker Compose configuration file.
- `Dockerfile`: Dockerfile for building the application image.
- `Jenkinsfile`: Jenkins pipeline configuration.
- `Jenkinsfile.v2`: Version 2 of the Jenkins pipeline configuration.
- `misc/Vagrantfile`: Vagrant configuration file.
- `package.json`: Project metadata and dependencies.
- `test/test.js`: Test file for the application.

## Environment Variables

For `index-db.js`, the following environment variables need to be set:

- `MYSQL_HOST`: MySQL database host
- `MYSQL_USER`: MySQL database user
- `MYSQL_PASSWORD`: MySQL database password
- `MYSQL_DATABASE`: MySQL database name

## License

This project is licensed under the MIT License.