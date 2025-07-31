FROM mcr.microsoft.com/vscode/devcontainers/php:8.3

RUN apt-get update && apt-get install -y libzip-dev unzip libonig-dev \
    && docker-php-ext-install bcmath exif pcntl zip \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
