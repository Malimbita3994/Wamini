# Msimamizi wa Kanisa (MWK)

Church Management System — modular foundation (v0.1.0).

- **Default UI language:** Kiswahili  
- **Secondary:** English  
- **Stack:** Laravel, MySQL, Inertia.js, React, TypeScript, Tailwind CSS v4, shadcn/ui  
- **Theme:** Modern Teal  

See:
- [docs/FOUNDATION.md](docs/FOUNDATION.md) — modules, routes, localization, permissions  
- [docs/INERTIA_SHADCN.md](docs/INERTIA_SHADCN.md) — React/Inertia/shadcn UI architecture  
- [docs/ui-interaction-standards.md](docs/ui-interaction-standards.md) — motion, forms, loading, accessibility  

`Template/` remains a TailAdmin design reference only.

## Quick start

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
npm install
npm run build
php artisan serve
```

Login: `admin@mwk.local` / `password`

```bash
npm run dev        # Vite HMR
npm run typecheck  # TypeScript
php artisan test
```
