# customerAWP
Framework: Laravel 10
Frontend: Blade + Bootstrap 5
Database: MySQL / MariaDB
Version Control: Git + GitHub
Hosting Ready: VPS / Shared Hosting / Laravel Forge

#Project Structure
customerAWP-laravel/
│-- app/              # Core application files (Models, Controllers, etc.)
│-- bootstrap/        # Laravel bootstrap files
│-- config/           # Configuration files
│-- database/         # Migrations, Seeders, Factories
│-- public/           # Public files (index.php, assets, etc.)
│-- resources/
│   ├── views/        # Blade templates (login, dashboard, etc.)
│   ├── css/          # Custom CSS
│   └── js/           # Custom JavaScript
│-- routes/           # Web & API routes
│-- tests/            # Unit & Feature tests
│-- .env.example      # Example environment file
│-- artisan           # Laravel CLI

1. Clone Repository
git clone https://github.com/username/customerAWP.git
cd customerAWP/customerAWP-laravel

2. Install Dependencies
composer install
npm install && npm run dev

3. Setup Environment
cp .env.example .env
php artisan key:generate

4. Run Migrations
   php artisan migrate
