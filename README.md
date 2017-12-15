# Security Checker shim

`composer.lock` Security Checker shim that includes only executable file with no other dependencies

## Usage

Install the package

```bash
composer require --dev mhlavca/security-checker-shim
```

and use it like the original executable

```bash
php vendor/bin/security-checker.phar security:check /path/to/composer.lock
```

Check out the main repo for more options https://github.com/sensiolabs/security-checker
