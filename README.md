Aist Git Tools
==============

Module providing git toolbar for the [Zend Developer Tools](https://github.com/zendframework/zend-developer-tools).

About
=====

Information of the application repository data like this :
![Show ZF2 Git data](data/docs/toolbar.png)
[x] git version info
[x] directory info
[x] repository size
[x] branches list
[x] highlight current branch
[x] tags list
[x] enabled hooks list
[x] remotes list

Installation
============

Installation of this module uses composer. For composer documentation, please refer to
[getcomposer.org](http://getcomposer.org/).

1. Install the module via composer by running:
    ```sh
    $ php composer.phar require aist/aist-git-tools dev-master
    ```
   or download it directly from github and place it in your application's `module/` directory.
2. Add the `AistGitTools` module to the module section of your `config/application.config.php`

Credits
-------

Git Logo by Jason Long is licensed under the Creative Commons Attribution 3.0 Unported License.
