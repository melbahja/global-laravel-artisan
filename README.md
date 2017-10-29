# global-laravel-artisan
make laravel artisan command global

## How to install
```
git clone https://github.com/melbahja/global-laravel-artisan.git
sudo mv ./global-laravel-artisan/artisan /usr/local/bin/artisan
sudo rm -fr ./global-laravel-artisan
sudo chmod +x /usr/local/bin/artisan
```
now you can use the global command ```artisan``` :)

Note: if you using LAMPP server replace ```#!/usr/bin/env php``` with ```#!/opt/lampp/bin/php``` in artisan file

