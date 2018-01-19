## PHP .docx replacer

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Total Downloads][ico-downloads]][link-downloads]

### Replace your variables to text or even to images

### Install

Require this package with composer using the following command:

```bash
composer require irebega/docx-replacer
```

### Text to text replace

This code will replace **$search** to **$replace** in **$pathToDocx** file

```php
$docx = new IRebega\DocxReplacer($pathToDocx);

$docx->replaceText($search, $replace);
```

### Text to image replace

This code will replace text **$search** to image that are located in **$path** in **$pathToDocx** file

```php
$docx = new IRebega\DocxReplacer($pathToDocx);

$docx->replaceTextToImage($search, $path);
```
### License

The Laravel IDE Helper Generator is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)


[ico-version]: https://img.shields.io/packagist/v/barryvdh/laravel-ide-helper.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/barryvdh/laravel-ide-helper.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/irebega/docx-replacer
[link-downloads]: https://packagist.org/packages/irebega/docx-replacer
[link-author]: https://github.com/igorrebega