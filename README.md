## Phone Book App Guide

This application is split in two parts and connected using REST API.
- [Backend Application Built With Laravel](https://github.com/edemking/phone-book-app-backend.git)
- [Frontend Application Built With VueJS](https://github.com/edemking/phone-book-app-frontend.git)

To run full applications

## Backend

## Project Setup

```sh
composer install
```
### Compile and Hot-Reload for Development

```sh
php artisan run serve
```

## Local Server Configuration 

After you compile and serving the backend, copy the location it is being served at mostly [http://127.0.0.1:8000]

Go to fontend/src/main.js
Paste in axios configuration where you see baseUrl

## Frontend

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

After you compile and running the frontend, copy the location it is being served at mostly [http://localhost:5173] and paste in browser.

Your application is ready.