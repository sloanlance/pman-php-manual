# pman-php-manual
PHP documentation in manpage format from the official PEAR package and a wrapper script, `pman`, to display them using the common `man` command.

## Installation

0. Be sure `~/.composer/vendor/bin` is included in the path.
0. Use Composer to install:

  `composer global require sloanlance/pman-php-manual:dev-master`
  
  It's important to note that the installation command shown at the top of the Packagist page for this package will **_not_** work.
  Be sure to use this command instead.
  
## Usage

Use the `pman` script to display documentation pages:

* `pman DateTime`
* `pman realpath`
* Etc.
