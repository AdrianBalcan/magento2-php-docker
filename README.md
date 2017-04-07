
# Description

This image is built from the official [`php`](https://hub.docker.com/_/php/) repository and contains PHP configurations for Magento 2.

# What's in this image?

This image installs the following base packages:

- `composer`
- `php-fpm`

This image also installs the following PHP extensions, which are the minimally required extensions to install and run Magento 2:

- `bcmath`
- `gd`
- `intl`
- `mbstring`
- `mcrypt`
- `pdo_mysql`
- `soap`
- `xsl`
- `zip`

# Variables

The following variables may be set to control the PHP environment:

- `PHP_MEMORY_LIMIT`: (default `2048M`) Set the memory_limit of php.ini
- `PHP_PORT`: (default: `9000`) Set a custom PHP port
- `PHP_PM`: (default `dynamic`) Set the process manager
- `PHP_PM_MAX_CHILDREN`: (default: `10`) Set the max number of children processes
- `PHP_PM_START_SERVERS`: (default: `4`) Set the default number of servers to start at runtime
- `PHP_PM_MIN_SPARE_SERVERS`: (default `2`) Set the minumum number of spare servers
- `PHP_PM_MAX_SPARE_SERVERS`: (default: `6`) Set the maximum number of spare servers
- `APP_MAGE_MODE`: (default: `default`) Set the MAGE_MODE

