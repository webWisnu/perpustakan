


## Instalasi

1. Clone repository
    ```bash
    git clone https://github.com/username/nama-proyek.git
    cd nama-proyek
    ```

2. Instal dependensi
    ```bash
    composer install
    ```

3. Salin file `.env.example` ke `.env` dan konfigurasikan
    ```bash
    cp .env.example .env
    ```

4. Generate application key
    ```bash
    php artisan key:generate
    ```

5. Jalankan migrasi database
    ```bash
    php artisan migrate
    ```

6. Jalankan server
    ```bash
    php artisan serve
    ```
