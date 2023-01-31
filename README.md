
## Running Locally
Larabank is built with Laravel Framework 8.18.1 which would require [PHP](https://php.net) 7.4+ to run smoothly.

1. Open your terminal and `cd` to any directory of your choice
    ```bash
    cd your-directory
   ```
2. Clone this repository
    ```bash
    git clone https://github.com/Jdjannat/larabank.git
    ```
3. `cd` into the folder created for cloned project:
    ```bash
    cd larabank
   ```

4. Install packages with composer (Make sure composer is installed already)
    ```bash
    composer install
   ```

5. Make a copy of .env.example as .env
    ```bash
    cp .env.example .env
   ```

6. Generate app key
    ```bash
    php artisan key:generate
   ```

7. Create an empty database and add the database credentials to `.env` file
 
8. Run migration
   ```bash
   php artisan migrate
   ```
9. Start laravel local server
   ```bash
    php artisan serve
    ```

10. open http://127.0.0.1:8000/ in your browser, You should see larabank login page.

11. Create new account and login. You should create two separate accounts to enable you transfer funds from one account to another.

