# Facade Documenter

```sh
# Configure composer
composer config repositories.facade-documenter vcs git@github.com:hypervel/facade-documenter.git

# Install the package
composer require --dev hypervel/facade-documenter:dev-main

# Update the docblocks:
php -f vendor/bin/facade.php -- \
    Hypervel\\Support\\Facades\\App \
    Hypervel\\Support\\Facades\\Artisan \
    Hypervel\\Support\\Facades\\Auth \
    ...

# Lint the docblocks:
php -f vendor/bin/facade.php -- --lint \
    Hypervel\\Support\\Facades\\App \
    Hypervel\\Support\\Facades\\Artisan \
    Hypervel\\Support\\Facades\\Auth \
    ...
```
