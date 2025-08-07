# Laravel IdeaShow

**IdeaShow** is a Laravel-based platform designed for community interaction, allowing users to submit ideas, comment, evaluate, and discuss proposals in a structured environment. The application supports user-centric interaction with features such as idea submission, threaded commenting, and voting, all within a modern and responsive interface.

---

## Features

- User registration and simple authentication
- Idea submission and display functions
- Commenting system with reply support
- Voting or rating system for ideas
- Clean frontend design supporting interactivity and responsiveness
- Blade-based templates with dynamic JavaScript enhancements

---

## Technology Stack

- **Backend**: Laravel (PHP) with Blade templating
- **Frontend**: JavaScript and SCSS/CSS
- **Styling**: SCSS for modular and maintainable styles
- **Architecture**: MVC design using Laravel conventions

---

## Screenshots

### Admin Dashboard – Idea Overview and Metrics  
![Dashboard Overview](./screenshots/61099d8e-f19b-4d1f-848c-d79955f23673.png)

### Idea Detail Page – Comments and Interactions  
![Idea Detail Page](./screenshots/332e9cf0-0cc0-4e14-9a0d-8c84868a2220.png)

### Homepage – Feature Highlight and Navigation  
![Homepage](./screenshots/9265f019-6716-4ecf-8a0e-69900c46c53e.png)

---

## Installation

To get started with IdeaShow locally:

```bash
git clone https://github.com/M0BiN/laravel-ideashow.git
cd laravel-ideashow
composer install
npm install && npm run dev
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```
