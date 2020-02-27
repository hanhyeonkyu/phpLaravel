# PHP LARAVEL

## SETTING

### php (step by step)
- `brew install php` on mac terminal
- `php -v`, `apachectl -v` check your php & apachectl
- `sudo apachectl start` or `sudo apachectl stop` or `sudo apachectl restart` you can manage apachectl server
- `curl -sS https://getcomposer.org/installer | php` and then `sudo mv composer.phar /usr/local/bin/composer` composer install
- `vi ~/.zshrc` and add it `export PATH=$PATH:$HOME/.composer/vendor/bin` and then `source ~/.zshrc`
- `composer global require laravel/installer` laravel install
- Go to `/usr/local/bin` and then change file `composer.phar` => `composer`
- `laravel new [your project name]` and `cd [your project name]` and then `php artisan serve` exceute server
- Done 😀 ~!
