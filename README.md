[![Stories in Ready](https://badge.waffle.io/laraToolkit/lara.png?label=ready&title=Ready)](https://waffle.io/laraToolkit/lara)
lara
====

Toolkit for the Laravel Framework

![lara Header](https://raw.githubusercontent.com/laraToolkit/Assets/master/Header/Header_1000x200_TRANS.png)

The best Laravel-Tools in a bundle

##### Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)

Requirements
------------

The Laravel Tookit has a few system requirements such as the Laravel Framework:

-    PHP >= 5.4
-    Mcrypt PHP Extension
-    OpenSSL PHP Extension
-    Composer (Preferred to be installed globally)

As of PHP 5.5, some OS distributions may require you to manually install the PHP JSON extension. When using Ubuntu, this can be done via `apt-get install php5-json`.

Installation
------------

First, download the Laravel Toolkit using Composer.

`composer global require "lara-toolkit/lara"`

Make sure to place the `~/.composer/vendor/bin` directory in your PATH so the `lara` executable can be located by your system.

Once installed, the simple `lara project:new` command will create a fresh Laravel installation in the directory you specify. For instance, `lara project:new blog` would create a directory named blog containing a fresh Laravel installation with all dependencies installed. This method of installation is much faster than installing via Composer.