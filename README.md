# Elgentos Laravel Coding Standards

The Elgentos Laravel Coding Standards packages adds coding standards for your
Laravel proect. It is based on the generic MediaCT coding standards, but with
framework specific changes made for Laravel.

## Installation

To install this package, run the following Composer command in your project.

```bash
composer require --dev elgentos/laravel-coding-standard
```

## Usage

To let PHPCS in your project know that these coding standards should be used,
make sure you add the following lines to your project's `phpcs.xml` file:

```xml
<?xml version="1.0"?>
<ruleset>
    <rule ref="./vendor/elgentos/laravel-coding-standard/src/ElgentosLaravel"/>
</ruleset>
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to 
discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
