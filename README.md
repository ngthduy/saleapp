﻿# Version

* Ruby version: 2.7.0

* Rails version: 5.1.4

* Database management system: postgres

* Database name: saleapp

# Install and Deloyment

### Clone repository

```php
    $ git clone https://github.com/ngthduy/saleapp.git
    $ cd saleapp
```
### Check version
User ruby version 2.7.0 and rails version 5.1.4
```php
    $ ruby -v
    $ rails -v
```
if not have to install the correct version
```php
    $ gem install rails -v 5.1.4
```

### Install dependencies
```php
    gem install bundler
```
### Install & update Gemfile
```php
    $ bundle install
```

### Initialize the database
```php
    $ rails db:create db:migrate db:seed
``` 
* db:create     -> create database
* db:migrate    -> create table and data structure
* db:seed       -> create seed data

### Run server
```php
    $ rails s
```
* Run on browser
```php
    http://localhost:3000/
```
* User login
username: admin / password: admin
