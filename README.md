# Student Management System — Excellence Academy

A web-based student management system built with Laravel and MySQL to help an academy manage its core academic and administrative activities in one place.

## Live Demo

[Try the system](https://lnkd.in/eSqYXgDX)

> The project is actively evolving. Some features and improvements are planned for future releases.

## Features

- **Student Management** — register students and manage their information.
- **Dashboard** — access key system sections from a central dashboard.
- **Attendance Management** — manage student attendance and absences.
- **Teacher Management** — maintain teacher records.
- **Classes and Subjects** — organize classes and academic subjects.
- **Authentication** — sign-in and account registration.
- **Responsive Interface** — designed to work across different screen sizes.

## Tech Stack

- **Backend:** PHP, Laravel
- **Database:** MySQL
- **Frontend:** Blade, HTML, CSS

## Getting Started

The steps below describe a typical local setup for a Laravel application. Check the project's actual configuration files for its required PHP and Laravel versions.

### Prerequisites

Make sure you have the following installed:

- PHP (a version compatible with the project)
- Composer
- MySQL
- Node.js and npm, if the project uses a frontend build process
- Git

### Installation

1. Clone the repository:

   ```bash
   git clone <YOUR_GITHUB_REPOSITORY_URL>
   cd <PROJECT_DIRECTORY>
   ```

2. Install PHP dependencies:

   ```bash
   composer install
   ```

3. Create your environment file:

   ```bash
   cp .env.example .env
   ```

   On Windows Command Prompt, you can use:

   ```bat
   copy .env.example .env
   ```

4. Generate the application key:

   ```bash
   php artisan key:generate
   ```

5. Create a MySQL database, then update the database settings in `.env`:

   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=your_database_name
   DB_USERNAME=your_database_username
   DB_PASSWORD=your_database_password
   ```

6. Run the database migrations:

   ```bash
   php artisan migrate
   ```

7. If the project contains frontend dependencies, install and build them:

   ```bash
   npm install
   npm run build
   ```

8. Start the local development server:

   ```bash
   php artisan serve
   ```

   Open the local URL shown in the terminal.

> If the project includes seeders, storage setup, or other project-specific configuration, follow the instructions in its source files. Do not run seeders unless you know what data they create.

## Roadmap

- Add a financial management module.
- Continue improving existing modules and the overall user experience.

## Project Status

The current version supports the core functions listed in the Features section. Development is ongoing, and additional capabilities are planned.

## Author

Developed as a practical web application project for managing student and academic information at Excellence Academy.
