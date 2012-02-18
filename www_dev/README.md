# USRP Commission Tracker

## Installation

1. If using git-svn, clone the Subversion repository.

        $ git svn clone https://www.centretekpreview.net/svn/usrp-ct

1. If using Subversion, checkout the repository.
1. Ensure that the `app/tmp/` directory structure exists and is writable.

        $ mkdir -p app/tmp/cache/{brief,day,hour,models,persistent,views,week}

1. Create a local `database.php` file.

        $ cp app/config/database.sample.php app/config/database.php
        
1. Open the new `database.php` file and update the configuration as required.
1. Create a local `bootstrap.local.php` file.

        $ cp app/config/bootstrap.local.sample.php app/config/bootstrap.local.php
        
1. Install the database.

        $ cd _scripts/sql
        $ mysql < release.sql

# CakePHP

CakePHP is a rapid development framework for PHP which uses commonly known design patterns like Active Record, Association Data Mapping, Front Controller and MVC. Our primary goal is to provide a structured framework that enables PHP users at all levels to rapidly develop robust web applications, without any loss to flexibility.

The Cake Software Foundation - promoting development related to CakePHP
http://cakefoundation.org/

CakePHP - the rapid development PHP framework
http://www.cakephp.org

Cookbook - user documentation for learning about CakePHP
http://book.cakephp.org

API - quick reference to CakePHP
http://api.cakephp.org

The Bakery - everything CakePHP
http://bakery.cakephp.org

The Show - live and archived podcasts about CakePHP and more
http://live.cakephp.org

CakePHP TV - screen casts from events and video tutorials
http://tv.cakephp.org

CakePHP Google Group - community mailing list and forum
http://groups.google.com/group/cake-php

#cakephp on irc.freenode.net - chat with CakePHP developers
irc://irc.freenode.net/cakephp
