
# PHP - MVC Framework From Scratch

- [x] Routing
  - Create a central entry point to the framework: the front controller
  - Configure the web server to have pretty URLs
  - Create amd require (not include) the router class
  - Create the routing table in the router, and add some routes
  - Match the requested route to the list of routes in the routing table
  - Get the controller and action from a URL with a fixed structure
  - Get the controller and action from a URL with a variable
  - Add custom variables of any format to the URL
- [x] Controllers and Actions
  - Dispatch the route: create the controller object and run the action method
  - Load classes automatically: add namespaces and an autoload function
  - Remove query string variables from the URL before matching to a route
  - Pass route parameters from the route to all controllers
  - Action filters: call a method before and after every action in a controller
  - Addendum: fix for a potential security bug introduced with the action filters
  - Organise controllers in subdirectories: add a route namespace option
- [x] Views
  - Display a view: create a class to render views and use it in a controller
  - Pass data from the controller to the view
  - Make vies easier to crate and maintain: add a template engine
  - Remove repetition in the view templates: add a base template to inherit from
- [x] Manage code using Composer
  - Install the template engine library using Composer



## Notes

[PHP Live Regex](https://www.phpliveregex.com/)

[Twig is a modern template engine for PHP](https://twig.symfony.com/)

[Smarty PHP Template Engine](https://www.smarty.net/)

[Laravel Blade templates](https://laravel.com/docs/9.x/blade)

[Phalcon Bolt template engine](https://docs.phalcon.io/5.0/en/introduction)

[Composer - The Dependency Manager for PHP](https://getcomposer.org/)

[Composer - How to Specify Package Versions](https://getcomposer.org/doc/articles/versions.md)

[Composer - Installation Instructions](https://getcomposer.org/doc/00-intro.md)

[Packagist - The PHP Package Repository](https://packagist.org/)

[Install the template engine library using Composer](https://twig.symfony.com/doc/3.x/intro.html#installation)
