# Installation
## Prepare
```sh
  # Clone
  $ git clone https://github.com/biswassampad/laravel-5.6-with-Materialize-1.0.0-rc.2.git materialize

  $ cd materialize

  # Install dependencies
  $ composer install

  # Configure .env and generate key
  $ cp .env.example .env
  $ php artisan key:generate
```

## Compile assets
```sh
  # Install packages
  $ npm install

  # Run all mix tasks
  $ npm run dev

  # Or mix using this, to watch all relevant files for changes
  $ npm run watch
```
## Run
```sh
  $ php artisan serve

  # Go to 127.0.0.1:8000
```
