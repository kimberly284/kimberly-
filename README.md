# kimberly-
<!-- README.md is generated from README.Rmd. Please edit that file -->




The installation tool kit, provided here, include:

  - Nginx web server
  - MadriaDB/MySQL used for Wordpress database
  - phpMyAdmin interface to connect to your MySQL database
  - WP-Cli: Wordpress Command Line Interface
  - Makefile directives for automatization.


``` bass
# Download a wordpress docker-compose example
https://github.com/kimberly284/kimberly-.git
cd wordpress-docker-compose
#Build and start installation 
docker-compose up -d --build
```

Visit your site at <http://localhost> and your database via phpMyAdmin
at <http://localhost:8080>.

Default identification for your wordpress website admin:

  - `Username: wordpress` and
  - `Password: wordpress`

Default identification for the phpMyAdmin interface:

  - `Username: root` and
  - `Password: password`

