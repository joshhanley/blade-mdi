Laravel Blade Material Design Icons
===================================

Blade MDI adds Material Design Icons as Laravel Blade UI Kit components. For more information regarding Material Design Icons, check https://materialdesignicons.com

## 🚀 Installation

You can install the package via composer:

```bash
composer require joshhanley/blade-mdi
```

This is not required, but if you want to publish the SVGs locally, you can do so:

```bash
$ php artisan vendor:publish --provider="BladeMdi\BladeMdiServiceProvider" --tag="blade-mdi"
```

## 🙌 Usage

Using [blade-ui-kit/blade-icons](https://github.com/blade-ui-kit/blade-icons), all icons can be shown as directives:

```blade
<x-mdi-account />
```

For a complete list of icons, check https://materialdesignicons.com

## Updating Icons

If you wish to contribute and update the latest icons, you can fork the repo, run `download.sh` and submit a PR. What `download.sh` does is to download the `master` branch of https://github.com/Templarian/MaterialDesign and copy the distributables svgs to local svgs.

## 🎉 Credits

This is a fork of https://github.com/renoki-co/blade-mdi

- [Alex Renoki](https://github.com/rennokki) - Original repo owner
- [All Contributors](../../contributors)

## 📄 License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
