# Awesome Laravel
A curated list of awesome Laravel packages, tools, articles, tutorials and other related resources. Inspired by [Frontend Dev Bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks).

Complementing this list, you may also want to check out [Awesome PHP](https://github.com/ziadoz/awesome-php): a curated list of amazingly awesome PHP libraries, resources and shiny things.

*Looking for other awesome lists for PHP, Frontend Development, etc? Check out [Awesome - A curated list of awesome lists](https://github.com/sindresorhus/awesome).*

## Official Resources
- [laravel/laravel](https://github.com/laravel/laravel): The default project structure to start developing with Laravel framework. The project itself does not contain the framework's code.
- [laravel/framework](https://github.com/laravel/framework): The project that contains Laravel frameworks's code. Use this project for forking, submit pull requests, etc.
- [Laravel.io](http://laravel.io): The official Laravel Framework forum.

## Articles & Tutorials
- Articles/tutorials on specific subject
  - [Exploring Laravel’s IoC container](http://culttt.com/2014/03/24/exploring-laravels-ioc-container/) by Philip Brown.
  - [Testing Laravel Controllers](http://code.tutsplus.com/tutorials/testing-laravel-controllers--net-31456) by Jeffrey Way.
  - [Best places to put custom helpers](https://stackoverflow.com/questions/17088917/what-are-the-best-practices-and-best-places-for-laravel-4-helpers-or-basic-funct) on StackOverflow.
  - [Laravel + Grunt + Bower + Bootstrap](http://blog.elenakolevska.com/using-grunt-with-laravel-and-bootstrap/) by Elena Kolevska.
  - [Laravel + HHVM + Nginx](http://fideloper.com/hhvm-nginx-laravel) by Fideloper.
  - [Using Repository Pattern](http://heera.it/laravel-repository-pattern): to decouple the hard dependencies of models from the controllers.
  - Autoloading
    - [Laravel PSR-0 auto-loading](http://stackoverflow.com/questions/21320775/laravel-psr-0-auto-loading)
    - [Re-organising Laravel applications with PSR-4](http://laravelish.wordpress.com/2014/03/05/psr-4/)
- Series of articles/tutorials
  - [Code Bright](http://daylerees.com/codebright) by Dayle Rees.
  - [Cribb @ culttt.com](http://culttt.com/tag/cribbb/)
  - [Laravel 4 Tutorials on Medium.com](https://medium.com/laravel-4)
- Frequently asked questions
  - [Laravel requires the Mcrypt PHP extension](https://stackoverflow.com/questions/16830405/laravel-requires-the-mcrypt-php-extension).
  - [php artisan dump-autoload vs. composer dump-autoload](https://stackoverflow.com/questions/20274082/what-are-differences-between-php-artisan-dump-autoload-and-composer-dump-auto)
- Laravel on shared hosting
  - [Laravel 4 on a shared host](http://driesvints.com/blog/laravel-4-on-a-shared-host/) by Dries Vints.
  - [Install Laravel 4 without Composer](https://stackoverflow.com/questions/15940140/can-i-install-laravel-4-without-using-composer).
  - [Install to a web host without publicly exposing /app/ folder?](https://stackoverflow.com/questions/16683046/how-to-install-laravel-4-to-a-web-host-subfolder-without-publicly-exposing-app)
- Integration with Paas/Saas
  - _(coming soon)_

## Popular/Notable Packages

- Authentication & Authorization
  - [Laravel's built-in authentication](http://laravel.com/docs/security).
  - [lucadegasperi/oauth2-server-laravel](https://github.com/lucadegasperi/oauth2-server-laravel): OAuth 2.0 server package for Laravel. Uses [thephpleague/oauth2-server](https://github.com/thephpleague/oauth2-server).
  - [artdarek/oauth-4-laravel](https://github.com/artdarek/oauth-4-laravel): An OAuth client wrapper for Laravel. Uses [Lusitanian/PHPoAuthLib](https://github.com/Lusitanian/PHPoAuthLib).
  - [zizaco/confide](https://github.com/Zizaco/confide): An authentication solution for Laravel 4. Includes account confirmation, login throttling, etc.
  - [zizaco/entrust](https://github.com/Zizaco/entrust): Role-based Permissions for Laravel 4.
- Developer's tools
  - [barryvdh/laravel-debugbar](https://github.com/barryvdh/laravel-debugbar): Laravel 4 Debugbar (Integrates PHP Debug Bar).
  - [way/generators](https://github.com/JeffreyWay/Laravel-4-Generators): Easily generate model, view, controller, migrations, etc. via `php artisan` commands.
  - [aws/aws-sdk-php-laravel](https://github.com/aws/aws-sdk-php-laravel.git): A simple Laravel 4 service provider for including the AWS SDK for PHP.
  - [anahkiasen/former](https://github.com/anahkiasen/former): A powerful form builder for Laravel and other frameworks.
- Building an API
  - [dingo/api](https://github.com/dingo/api): A RESTful API package for the Laravel framework. Supports API versioning, data transformers, error handling, rate limiting, etc.
  - [barryvdh/laravel-cors](https://github.com/barryvdh/laravel-cors): Adds CORS (Cross-Origin Resource Sharing) headers support in your Laravel application.
- Database
  - [laravelbook/ardent](https://github.com/laravelbook/ardent): Self-validating smart models for Laravel 4's Eloquent O/RM.
  - [cviebrock/eloquent-sluggable](https://github.com/cviebrock/eloquent-sluggable): Easy creation of slugs for your Eloquent models in Laravel 4.
- Testing
  - ~~[way/laravel-test-helpers](https://github.com/JeffreyWay/Laravel-Test-Helpers): A set of helpers for easier testing in Laravel~~ (no longer maintained).
- Other notable packages
  - [mewebstudio/Purifier](https://github.com/mewebstudio/Purifier): HTMLPurifier for Laravel 4.
  - [intervention/image](https://github.com/Intervention/image): Image handling and manipulation library. Supports Laravel 4 out of the box.
  - [greggilbert/recaptcha](https://github.com/greggilbert/recaptcha): reCAPTCHA Validator for Laravel 4.
  - [frozennode/administrator](https://github.com/FrozenNode/Laravel-Administrator): An administrative interface builder for Laravel.
  - [thujohn/pdf-l4](https://github.com/thujohn/pdf-l4): A simple Dompdf package for Laravel 4.

## Tools
- [Sublime Text's Laravel Blade Highlighter](https://sublime.wbond.net/packages/Laravel%20Blade%20Highlighter): Laravel Blade syntax highlighter support for Sublime Text..
- [Laravel Cheat Sheet](http://cheats.jesse-obrien.ca/).

## Community
- [Laravel.io](http://laravel.io): The official Laravel Framework forum.
- [Laracasts Forum](https://www.laracasts.com/forum): A community of Laravel developers at Laracasts.com. Sign up does not require paid subscription at Laracasts.com.

## Books
- [Laravel: From Apprentice To Artisan](https://leanpub.com/laravel): a book by the creator of Laravel himself!
- [Laravel 4 Cookbook](https://leanpub.com/laravel4cookbook) by Christopher Pitt and Taylor Otwell.
- [Code Bright](https://leanpub.com/codebright): by Dayle Rees.
- [Laravel Testing Decoded](https://leanpub.com/laravel-testing-decoded) by Jeffrey Way.

## Other Awesome Laravel Resources
- [Laracasts](https://www.laracasts.com): Paid video tutorials site not limited to, but generally based on Laravel.
- [Packalyst](http://packalyst.com/): A directory of Packages for your Laravel projects.
- [Laravel Snippets](http://laravelsnippets.com/): Code snippets in Laravel.
- [Built with laravel](http://builtwithlaravel.com/): A collection of sites build with Laravel.
- [Larajobs](https://larajobs.com): Will code Laravel for food.
- [Pongo CMS](http://pongocms.com/): A content management system (CMS) built with Laravel.
