# Rental Car System

A Laravel web application for managing a car rental business: vehicles, vehicle owners, customers, locations and bookings.

## Features

- Vehicle management (CRUD) with vehicle details and owner assignment
- Booking form and booking management
- Customer and user details management
- Locations and contact form
- Authentication (register, login, profile, settings) with role/permission support
- Multi-language welcome, register and booking pages (`/{lang}/...`)

## Tech Stack

- PHP ^8.1, Laravel ^10
- MySQL
- Vite and Tailwind CSS

## Getting Started

```bash
git clone <repo-url>
cd Rental-Car-System

composer install
npm install

cp .env.example .env
php artisan key:generate
```

Set your database credentials (`DB_*`) in `.env`, then:

```bash
php artisan migrate
npm run dev        # or: npm run build
php artisan serve
```

The app is served at http://127.0.0.1:8000.

## Testing

```bash
php artisan test
```

## License

Open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
