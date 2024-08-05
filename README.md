# Task Management App

This is a task management application built with Svelte for the frontend, Flowbite for UI components, Directus as the backend, and MySQL as the database.



## Prerequisites

Make sure you have the following installed on your system:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [MySQL](https://www.mysql.com/)
- [Git](https://git-scm.com/)
- [Directus CLI](https://docs.directus.io/getting-started/installation/)

## Installation

### Backend Setup

1. *Clone the repository:*

    bash
    git clone https://github.com/your-username/task-manager-backend.git
    cd task-manager-backend
    

2. *Install dependencies:*

    bash
    npm install
    

3. *Configure Directus:*

    Create a .env file in the root of your backend directory with the following content:

    env
    DB_CLIENT=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_USER=your_mysql_username
    DB_PASSWORD=your_mysql_password
    DB_DATABASE=your_database_name
    

4. *Run Directus:*

    bash
    npx directus start
    

### Frontend Setup

1. *Clone the repository:*

    bash
    git clone https://github.com/your-username/task-manager-frontend.git
    cd task-manager-frontend
    

2. *Install dependencies:*

    bash
    npm install
    

3. *Run the development server:*

    bash
    npm run dev
    

## Usage

- *Backend:* The backend will be running at http://localhost:8055.
- *Frontend:* The frontend will be running at http://localhost:5000.

You can access the Directus admin panel at http://localhost:8055/admin.

## Project Structure

### Backend

- src/ - Contains the Directus configuration and custom code.
- .env - Environment configuration for Directus.

### Frontend

- src/ - Contains the Svelte components and application logic.
- public/ - Static assets.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes.
4. Commit your changes (git commit -am 'Add new feature').
5. Push to the branch (git push origin feature-branch).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.