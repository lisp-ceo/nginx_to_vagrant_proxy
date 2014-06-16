nginx\_to\_vagrant\_proxy 
=========================

Probably a bad idea but I want to use NGINX to route to software installations contained within Vagrant virtual machines

Design:
  1) Request: chronicle.us
  2) Route from NGINX at 108.5.178.59:80 to localhost:8080
  3) NGINX proxies all requests

Pros:
  - Contain development environment within virtual machines
  - Automated configuration of virtualized Vagrant environments
  - Portable, scalable environments

Cons:
  - NGINX configuration and routing maintenance

TODO:
  - Create NGINX configuration for each virtual hsot
  - Maintain route from NGINX configuration to virtual machine
  - Co-ordinate Vagrantfile configurations with NGINX host
