# Facade Documenter

```sh
# Configure composer
composer config repositories.facade-documenter vcs git@github.com:laravel-hyperf/facade-documenter.git

# Install the package
composer require --dev laravel-hyperf/facade-documenter:dev-main

# Update the docblocks:
php -f vendor/bin/facade.php -- \
    LaravelHyperf\\Support\\Facades\\App \
    LaravelHyperf\\Support\\Facades\\Artisan \
    LaravelHyperf\\Support\\Facades\\Auth \
    ...

# Lint the docblocks:
php -f vendor/bin/facade.php -- --lint \
    LaravelHyperf\\Support\\Facades\\App \
    LaravelHyperf\\Support\\Facades\\Artisan \
    LaravelHyperf\\Support\\Facades\\Auth \
    ...
```
