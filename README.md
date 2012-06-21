# secret-ninja

A Collection of Markdown files containing useful links and information.

## Heroku

## Php on Heroku

* http://hakre.wordpress.com/2012/05/20/php-on-heroku-again/
* https://github.com/winglian/Heroku-PHP/tree/master/conf

## Composer support

Using Composer in heroku ing custom build packs:
 * https://devcenter.heroku.com/articles/buildpacks
 * https://devcenter.heroku.com/articles/buildpack-api
 * http://bergie.iki.fi/blog/using_composer_to_manage_dependencies_in_heroku_php_apps/

Might be able to use custom build pack to set the webroot directory to */public for zf2 applications: 
Fork https://github.com/heroku/heroku-buildpack-php and change settings. (Would be awesome to have composer support as well.)

Composer code for buildpack: 
 * https://github.com/bergie/heroku-buildpack-php/blob/master/bin/compile#L49

Build pack to compile classmaps at update?

## Nginx
 * http://arstechnica.com/business/2011/11/a-faster-web-server-ripping-out-apache-for-nginx/ (be sure to note the over friendly php error)
 * http://wiki.nginx.org/Pitfalls#Pass_Non-PHP_Requests_to_PHP.

## Capistrano

## Cleaning Logs and Strucuture

 * http://jondavidjohn.com/blog/2012/04/cleaning-up-capistrano-deployment-output
 * http://guides.beanstalkapp.com/deployments/deploy-with-capistrano.html

## ZF 2 

* http://framework.zend.com/zf2
* http://akrabat.com/
* http://blog.evan.pro/
* http://mwop.net/blog.html
* http://ralphschindler.com/

## Configuration

 * http://www.spiffyjr.me/2012/06/17/how-does-configuration-work-in-zf2/
 
## JSON ViewStrategy

 * http://akrabat.com/zend-framework-2/returning-json-from-a-zf2-controller-action/

## Example Applications

 * https://github.com/akrabat
 * https://github.com/akrabat/ZF2TestApp

# Exceptions and handling errors in Php

 * http://framework.zend.com/wiki/display/ZFDEV2/Proposal+for+Exceptions+in+ZF2
 * http://www.php.net/manual/en/spl.exceptions.php
 * http://mwop.net/blog/on-error-handling-and-closures.html

# Mocking and PHPUnit

## Stubbing/Mocking Hardcoded Dependancies

* http://stackoverflow.com/questions/2031385/phpunit-stub-methods-undefined
* http://sebastian-bergmann.de/archives/885-Stubbing-Hard-Coded-Dependencies.html
