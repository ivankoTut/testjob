# The test job
CRUD app to manage some product list.
## Used technologies:
* [AngularJS] - HTML enhanced for web apps!
* [Symfony2] - High Performance PHP Framework for Web Development
* [Twitter Bootstrap] - great UI boilerplate for modern web apps
* [Bower] - a package manager for the web

[Symfony2]:http://symfony.com
[Twitter Bootstrap]:http://twitter.github.com/bootstrap/
[AngularJS]:http://angularjs.org
[Bower]:http://bower.io/

## To install
* `composer install`
* `bower install`
* `php app/console doctrine:database:create`
* `php app/console doctrine:migrations:migrate`
* `php app/console assetic:dump --no-debug`
* `php app/console cache:clear --no-debug`