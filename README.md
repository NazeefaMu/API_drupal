# Drupal API for employer dashboard

Display data fetched from

## Getting Started

##Current Support

- XT to The Iconic SellerCenter


### Prerequisites

- PHP 7
- Laravel Framework 7
- MySQL
- Redis


### Installing

- RUN <code>composer install </code> to install necessary libraries
- Except Laravel Default ENV keys, you have to define following necessary env keys
  - API_PREFIX=api
  - JWT_SECRET <code>very important. keep this confidential.</code>
  - REDIS_CLIENT=predis (because we use predis composer package here)
  - APP_TIMEZONE=better to set the time zone to sydney
- RUN <code>php artisan  jwt:secret </code> to generate a new JWT Secret
- RUN <code>php artisan serve </code> to spin up the Laravel Development Server


### Schedules Tasks
- RUN <code>php artisan schedule:run</code> to execute scheduled tasks

### Emails
- Configure SMTP Mail Account as in normal Laravel Applications


### Getting Access
- RUN <code> php artisan seometrix:makesuper </code> to create the Super Administrator User
- RUN <code> php artisan seometrix:updatesuper </code> to attach new permissions to Super Admin


### Testing
- RUN <code>php artisan test</code> to run all tests

## Built With

* Dingo API (https://github.com/dingo/api/wiki/Installation)
* JWT Authentication (https://jwt-auth.readthedocs.io/en/develop/)
* Laravel (https://laravel.com/)

## Changes

Please read [CHANGELOG.md](/CHANGELOG.md) for details.

## Versioning

- We use [SemVer](http://semver.org/) for versioning.
- See our git branch model (https://nvie.com/posts/a-successful-git-branching-model)


## Authors

* **Prageeth Peiris** - *Initial work* - [iamprageeth](https://github.com/iamprageeth)

* **Akila Anuranga** - *Developer*





## Acknowledgments

* DARTX Pvt. Ltd. Made with ❤
