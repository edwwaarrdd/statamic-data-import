# Just used for some very specific changes to import for a client.


```
git diff main..brepols-fix > file.patch

```

# Data Import plugin for Statamic

Import data from a CSV into a collection.

![Data Import](https://github.com/riasvdv/statamic-data-import/raw/master/docs/img/data-import.png)

## Installation

Require it using Composer.

```
composer require rias/statamic-data-import
```

Publish the assets:

```
php artisan vendor:publish --provider="Rias\StatamicDataImport\DataImportServiceProvider"
```

Brought to you by [Rias](https://rias.be)
