<!-- DO NOT EDIT THIS FILE! -->
<!-- Instead edit contrib/webpack_encore.php -->
<!-- Then run bin/docgen -->

# webpack_encore

[Source](/contrib/webpack_encore.php)


## Installing

Add to your _deploy.php_

```php
require 'contrib/webpack_encore.php';
```

## Configuration

- **webpack_encore/package_manager** *(optional)*: set yarn or npm. We try to find if yarn or npm is available and used.

## Usage

```php
For Yarn
after('deploy:update_code', 'yarn:install');
For npm
after('deploy:update_code', 'npm:install');

after('deploy:update_code', 'webpack_encore:build');
```


* Requires
  * [npm](/docs/contrib/npm.md)
  * [yarn](/docs/contrib/yarn.md)

## Configuration
### webpack_encore/package_manager
[Source](https://github.com/deployphp/deployer/blob/master/contrib/webpack_encore.php#L31)





### webpack_encore/env
[Source](https://github.com/deployphp/deployer/blob/master/contrib/webpack_encore.php#L39)



```php title="Default value"
'production'
```



## Tasks

### webpack_encore:build
[Source](https://github.com/deployphp/deployer/blob/master/contrib/webpack_encore.php#L42)

Run webpack encore build.




