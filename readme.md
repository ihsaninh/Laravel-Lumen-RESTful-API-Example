# Lumen Framework RestAPI Example

Laravel Lumen is a stunningly fast PHP micro-framework for building web applications with expressive, elegant syntax. We believe development must be an enjoyable, creative experience to be truly fulfilling. Lumen attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as routing, database abstraction, queueing, and caching.

## Features

Available Endpoint

    1. User Routes
    
    - GET /users - Fetch all users resource
    - POST /users - Create a new user resource
    - GET /users/{user} — Fetch a user resource by id
    - PUT /users/{user} — Update a user resource by id
    - DELETE /users/{user}- Delete a user resource by id
    
    2. Feed Routes

    - GET /feeds - Fetch all feeds resource
    - POST /feeds - Create a new feed resource
    - GET /feeds/{feed} — Fetch a feed resource by id
    - PUT /feeds/{feed} — Update a feed resource by id
    - DELETE /feeds/{feed}- Delete a feed resource by id
    
    3. Auth Routes
    
    - POST /register - register new user
    - POST /login - login user

## How To Run

You can follow step bellow to run this project

1. Clone this repository
   ```
   $ git clone https://github.com/ihsaninh/Laravel-Lumen-RESTful-API-Example.git
   ```
2. Extract zip file and Install all depedencies
   ```
   $ composer install
   ```
3. Create generate key
   ```
   $ php artisan key:generate
   ```
4. Rename .env.example to .env and change database setup to your own
   ```
   DB_CONNECTION=mysql // your db driver
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=homestead // your db_name
   DB_USERNAME=homestead // your db_username
   DB_PASSWORD=secret //your db_password
   ```
5. Migrate database table 
   ```
   $ php artisan migrate
   ```
6. Run the project 
   ```
   $ php -S localhost:8000 -t public
   ```

## License

The Lumen framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
