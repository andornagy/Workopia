# Workopia

Workopia - PHP Learning project

In order to run this, you'll need to create a MySQL database

## Step 1

Importing the workopia-db.sql. It is empty so you'll have to populate it yourself.

## Step 2

Create a `config/db.php` in the root directory, and add your mysql details.

```php
<?php
return [
    'host' => 'localhost',
    'port' => 3306,
    'dbname' => 'workopia',
    'username' => 'root',
    'password' => 'root'
];
```
