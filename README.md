### Project Dropbox Clone using Laravel and Vite.js

## Link http://dropbox.dilnozzt.beget.tech/login

## Task
The main tasks of this project include:

1. Creating a user authentication system.
2. Implementing file upload and download functionality.
3. Building a file management system including folder creation, deletion, and organization.
4. Enabling file sharing with other users via secure links.
5. Implementing real-time updates for file changes.

## Description
This project is a Dropbox clone built using Laravel and Vite.js. It aims to provide a file storage and sharing platform similar to Dropbox, allowing users to upload, download, and share files securely. The application is built with Laravel, a powerful PHP framework, for the backend logic and Vite.js, a fast frontend tooling for Vue.js, React, and vanilla JS, for the frontend development.

## Installation
To install and run this project locally, follow these steps:

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd project-dropbox-clone
   ```

3. Install PHP dependencies using Composer:
   ```
   composer install
   ```

4. Install Node.js dependencies using npm or yarn:
   ```
   npm install
   ```

5. Create a copy of the `.env.example` file and rename it to `.env`. Update the database configuration in the `.env` file with your database credentials.

6. Generate an application key:
   ```
   php artisan key:generate
   ```

7. Run migrations to create the necessary database tables:
   ```
   php artisan migrate
   ```

8. Start the Laravel development server:
   ```
   php artisan serve
   ```

9. In a separate terminal window, start the Vite.js development server:
   ```
   npm run dev
   ```

10. Access the application in your web browser at `http://localhost:8000`.

## Usage
Once the application is set up and running, you can perform the following actions:

1. Register a new account or login with existing credentials.
2. Upload files by navigating to the upload section and selecting the desired files.
3. Create folders to organize your files.
4. Share files with other users by generating secure links.
5. Download files or view them directly in the browser.
6. Manage your files and folders efficiently using the provided interface.
