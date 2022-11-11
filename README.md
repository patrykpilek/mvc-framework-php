
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



## Notes

[PHP Live Regex](https://www.phpliveregex.com/)