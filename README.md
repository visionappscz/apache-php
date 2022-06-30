# Apache PHP - Docker image

This is Docker Image with advanced configuration based on [official Apache-PHP image](https://github.com/docker-library/php)
with preconfigured Apache and PHP.

It was created to provide a simple hassle-free platform for CI use for small projects.

PHP includes the following extensions:

* GD
* exif
* mbstring
* intl
* mysqli
* pdo_mysql
* pdo_pgsql

Installed Databases:

* MySQL
* Postgres

Installed tools:

* Git
* Composer
* NPM
* Bower
* Grunt
* Gulp

## Releasing

* Build the container: `docker build . visionappscz/apache-php:<tag>`
* Push the image to the registry: `docker push visionappscz/apache-php:<tag>`
* Push the changes to GitHub and merge them into `master`
* Tag the release `git tag v<tag>` 
