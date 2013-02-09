# Auto MySQL Backup

A fork of http://sourceforge.net/projects/automysqlbackup/

## Install

### Git

As a submodule:

	git submodule add http://github.com/jadb/mysql-autobackup vendor/mysql-autobackup

Or a clone:

	git clone http://github.com/jadb/mysql-autobackup vendor/mysql-autobackup

### Composer

First, add `mysql/autobackup` as a dependency in your project's `composer.json` file:

	{
		"require": {
			"mysql/autobackup": "*"
		}
	}

Update your dependencies:

	php composer.phar update

That's it!
