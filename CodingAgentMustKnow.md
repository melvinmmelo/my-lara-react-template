## 🧠 Laravel 12 Project Brief for Coding Agent

You’ll be working with **Laravel 12**, the latest release of the Laravel PHP framework (released February 2025), known for its stability, improved DX (developer experience), and performance optimizations.

---

### 🚀 Project Stack

* **Backend**: Laravel 12 (PHP 8.2+)
* **Frontend**: React + Inertia.js + Tailwind CSS + TypeScript + Shadcn UI
* **Database**: SQLite
* **Starter Kit**: Laravel 12's React preset (with TypeScript and Tailwind pre-configured)

---

### 🌟 Laravel 12 Key Features to Note

* ✅ **Zero-Breaking Changes**: Easily upgradeable from Laravel 11 without major rewrites.
* ⚡ **React + Inertia Starter Kit**:

  * Tailwind CSS and Shadcn preconfigured
  * TypeScript support out of the box
  * Modern UI components ready to use
* 🧹 **Unified Scaffolding**: Use `php artisan scaffold` to generate models, migrations, and controllers together.
* 🧠 **AI Debugging Tool**: New `debug()` helper offers smart suggestions and real-time diagnostics.
* 🔐 **Improved Security**:

  * New `secureValidate()` method for safer validation
  * Better token and session management
* 🏎️ **Performance Upgrades**:

  * Asynchronous caching
  * Faster job queues
  * Memory efficiency enhancements

More details: [Laravel 12 Release Notes](https://laravel-news.com/laravel-12)

---

### 📂 Project Directory Structure (Reference: [Laravel Docs](https://laravel.com/docs/12.x/structure))

The Laravel application is structured as follows:

```
app/                # Core application code
├── Console/        # Artisan commands
├── Exceptions/     # Custom exception handling
├── Http/           # Controllers, middleware, and form requests
    ├── Controllers/
    ├── Middleware/
    └── Requests/
├── Models/         # Eloquent models
├── Policies/       # Authorization policies
├── Providers/      # Service providers
├── Notifications/  # Notifications
├── Jobs/           # Jobs
├── Services/       # Services
├── Notifications/  # Notifications
├── Broadcasting/   # Broadcasting
bootstrap/          # App bootstrap files (e.g., app.php)
config/             # Configuration files
database/           # Migrations, seeders, factories, and SQLite file
docker/             # Docker-related files (if applicable)
lang/               # Localization files
public/             # Public assets and index.php entry point
resources/          # Blade templates, JS, CSS, React components
  ├── js/           # JavaScript files
    ├── components/ # React components
    ├── pages/      # Page components used by Inertia
    ├── layouts/    # Layout components
    ├── hooks/      # Custom hooks
    ├── lib/        # Utility function
    ├── types/      # Custom types
    ├── app.tsx     # App entrypoint
    └── ssr.jsx     # Component configuration
  ├── css/          # CSS files
  └── views/        # Blade templates
    ├── app.blade.php  # App template
routes/             # Route definitions (web.php, api.php, etc.)
storage/            # Logs, cache, compiled views, file uploads
tests/              # Automated tests
vendor/             # Composer dependencies

.env                # Environment configuration
artisan             # Artisan CLI entry point
composer.json       # PHP dependencies and scripts
package.json        # Node dependencies
vite.config.js      # Vite configuration (frontend assets)

```

---

### ⚙️ Database Notes

* The project uses **SQLite** for lightweight, file-based local development.