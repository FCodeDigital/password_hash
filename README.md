# Instalando

##### Composer

```
composer require fcodedigital/passwordhash
```

# Como utilizar.
```
$passwordhash = \FCodeDigital\PasswordHash\PasswordHash();
$passwordhash->HashPassword('string');
$passwordhash->CheckPassword('string', 'stored_hash');
```