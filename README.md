# Rapidez Menu

This package provides a menu Blade component which uses the default Magento categories:
```
<x-menu/>
```

## Configuration

You can change the classes with the configuration file by publishing it with:
```
php artisan vendor:publish --provider="Rapidez\Menu\MenuServiceProvider" --tag=config
```
Keep in mind that if you're using TailwindCSS or running CSS purging with your own stack that the classes in this config file should be discoverable. So add it to the list of files!

## Full control

If you need more control you can publish the views as well with:
```
php artisan vendor:publish --provider="Rapidez\Menu\MenuServiceProvider" --tag=views
```
