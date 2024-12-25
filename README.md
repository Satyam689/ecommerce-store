# E-Commerce Project

## Overview
This is a feature-rich e-commerce web application developed using Laravel, MySQL, and Livewire. The project provides a seamless shopping experience with efficient management of products, orders, users, and payments.

## Features
- **User Authentication**: Secure registration, login, and profile management.
- **Product Management**: Add, edit, delete, and categorize products.
- **Shopping Cart**: Add-to-cart functionality with dynamic updates.
- **Order Management**: Users can place, view, and manage their orders.
- **Payment Gateway Integration**: Secure and reliable payment processing.
- **Admin Panel**: For managing users, orders, and products.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Real-time Updates**: Powered by Livewire for dynamic content updates without full page reloads.

## Tech Stack
- **Backend Framework**: Laravel  
- **Frontend Framework**: Laravel Blade with Livewire  
- **Database**: MySQL  
- **Styling**: Tailwind CSS 
- **Version Control**: Git

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Satyam689/ecommerce-app.git
   cd your-ecommerce-project
   ```

2. Install dependencies:
   ```bash
   composer install
   npm install && npm run dev
   ```

3. Set up the environment:
   - Copy the `.env.example` file and rename it to `.env`.
   - Configure database and other environment variables in the `.env` file.

4. Generate application key:
   ```bash
   php artisan key:generate
   ```

5. Run migrations and seed the database:
   ```bash
   php artisan migrate --seed
   ```

6. Start the development server:
   ```bash
   php artisan serve
   ```

## Usage
1. Visit the application at `http://localhost:8000`.
2. Register as a user or log in as an admin to access the admin panel.
3. Explore features like browsing products, adding them to the cart, and checking out.

## Project Structure
- `app/` - Contains the application logic.
- `database/` - Includes migrations and seeders.
- `resources/views/` - Blade templates for the frontend.
- `routes/` - Application routes.
- `public/` - Publicly accessible assets.




