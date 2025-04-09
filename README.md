# CarSell-PP
This is a simple Car Management System built using Laravel 11, based on the tutorial by The Codeholic. The project is designed to help users manage a list of cars, including their brand, model, production year, and availability.
📹 Tutorial Source
This project was created while following this YouTube tutorial by [The Codeholic]: 👉 Laravel 12 in 11 hours - Laravel for Beginners Full Course  

🛠 Features
Create, Read, Update, Delete (CRUD) operations for cars

Form validation

Flash messages for success & error notifications

Responsive UI with Tailwind CSS

Car availability status toggle (Available / Unavailable)

Data stored in MySQL database

🧰 Tech Stack
PHP 8+

Laravel 11

MySQL / MariaDB

Tailwind CSS

Blade Templating Engine

🚀 Installation
Clone the repository:

bash
git clone https://github.com/your-username/car-management.git
cd car-management
Install dependencies:

bash
composer install
npm install && npm run dev
Create a .env file:

bash
cp .env.example .env
Generate app key:

bash
php artisan key:generate
Configure database settings in .env, then run:

bash
php artisan migrate
Start the local server:

bash
php artisan serve
Now open http://localhost:8000 in your browser.

📚 License
This project is open-source and available under the MIT License.
