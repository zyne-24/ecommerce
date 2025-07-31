FROM mcr.microsoft.com/vscode/devcontainers/php:8.3

# Install ekstensi tambahan yang dibutuhkan Laravel & Lunar
RUN apt-get update && apt-get install -y unzip libzip-dev libonig-dev \
    && docker-php-ext-install bcmath exif pcntl zip \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
