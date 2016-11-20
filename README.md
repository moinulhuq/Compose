# Composer

Install composer in Ubuntu

sudo apt-get update

Install wget for file download in ubuntu

sudo apt-get install wget

Download the composer.phar from https://getcomposer.org/download via wget or built-in curl

wget https://getcomposer.org/composer.phar

Rename composer.phar to composer

sudo mv composer.phar composer

Make composer executable

chmod +x composer

Make composer available globally move it to /user/local/bin by

sudo mv composer /usr/local/bin

Now composer will be available anywhere by simply

composer
