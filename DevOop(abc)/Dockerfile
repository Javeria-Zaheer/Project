# Use official PHP image with Apache
FROM php:8.1-apache

# Copy files to web server directory
COPY . /var/www/html/

# Enable Apache rewrite module (if needed)
RUN a2enmod rewrite
