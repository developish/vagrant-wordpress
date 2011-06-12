# Vagrant Wordpress Theming #

This is a [Vagrant][vagrant] setup for creating Wordpress themes. Uses
[Chef Solo][chef] recipes for provisioning. The recipes are copied from
[my fork][cookbooks-developish] of [those by Opscode][cookbooks-opscode], which
allows for their use with Chef Solo and for a blank MySQL root password.

## Requirements ##

* [Vagrant][vagrant]

## To get started ##

    $ git clone git://github.com/developish/vagrant-wordpress.git
    $ cd vagrant-wordpress
    $ vagrant up
    $ open http://localhost:8080

Copy a base theme (like [Starkers][starkers]) into the theme directory, choose
it in the Wordpress dashboard, and get to work!

[vagrant]:http://vagrantup.com
[chef]:http://wiki.opscode.com/display/chef/Chef+Solo
[cookbooks-developish]:https://github.com/opscode/cookbooks
[cookbooks-opscode]:https://github.com/opscode/cookbooks
[starkers]:http://starkerstheme.com
