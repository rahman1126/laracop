## About Laracop

Laracop is a starter kit to speed up web development. Laracop is built on top of laravel 7.*.

## How to start :

###### Run :
<pre><code>
$ git clone https://github.com/rahman1126/laracop.git
$ cd laracop
$ cp .env.example .env
$ php artisan key:generate
$ sudo chmod -R o+W storage bootstrap public
$ php artisan serve
</code></pre>

###### Optional :
<pre><code>
$ sudo chmod -R 777 storage
$ composer dump-autoload
$ composer update
$ php artisan optimize
</code></pre>

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
