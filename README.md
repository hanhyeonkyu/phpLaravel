# PHP LARAVEL

## SETTING

### php (step by step)

1. `brew install php` on mac terminal
2. `php -v`, `apachectl -v` check your php & apachectl
3. `sudo apachectl start` or `sudo apachectl stop` or `sudo apachectl restart` you can manage apachectl server
4. `curl -sS https://getcomposer.org/installer | php` and then `sudo mv composer.phar /usr/local/bin/composer` composer install
5. `vi ~/.zshrc` and add it `export PATH=$PATH:$HOME/.composer/vendor/bin` and then `source ~/.zshrc`
6. `composer global require laravel/installer` laravel install
7. Go to `/usr/local/bin` and then change file `composer.phar` => `composer`
8. `laravel new [your project name]` and `cd [your project name]` and then `php artisan serve` exceute server
9. Setting your env copy `.env.example` to `.env`

Done 😀 ~!
