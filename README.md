# a lightweight php+postgresql messageboard

### Requirements
* nginx
* PHP 5x
* PostgreSQL 14.4x
* Sphinx 0.9x

#### Caveats

* Currently the board software does not support being installed in a folder, ie: http://www.mywebsite.com/board/

### Installation

1. Create database in PostgreSQL.
1. Run the SQL creation scripts in /doc/ (skip 0-Migrate)
1. Rename /config.default.php to config.php and modify as needed.
1. Rename /lang/en.default.php to en.php and modify as needed.
1. Rename /lang/en_header.default.php to en_header.php and modify as needed.
1. Rename /lang/en_footer.default.php to en_footer.php and modify as needed.
1. Rename /class/Plugin.default.php to Plugin.php and modify as needed.

More details to follow.
