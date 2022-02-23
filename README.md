# laravel-docker
docker compose up -d build

# install laravel
composer create-project laravel/larave/ src "9.*.*"

# masuk ke directori aplikasinya
cd src

#install vendor
composer install

#cek apakah sudah berjalan dengan baik
http://localhost:8080
