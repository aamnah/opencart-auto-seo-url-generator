
# Auto SEO URL Generator 2.0

This OpenCart extension will generate automatically the keywords to create Friendly URLs, using only characters and numbers, with no special chars, based on title. If the URL generated already exists, a number will be added to make it unique.

Based on Edir Pedro's [Simple SEO URL Generator](https://github.com/edirpedro/opencart-simple-seo-url-generator). Updated to work with Opencart 2.x and converted to OCMOD.

## Works with

- Products
- Categories
- Manufacturers
- Information Pages

## How it works

Get the title to generate the URL and write it on SEO Keyword field automatically. If you wish to edit manually, just write something on this field, when the url exists, a number will be added to the URL.

If you wish to rebuild the URL, when you change the title for example, clear any text on SEO Keyword field and a new URL will be generated based on the new title.

## Examples

URL appearance

	Title: Acessórios e Presentes
	URL: acessorios-e-presentes

A URL that has been taken

	Title: Duplicated Title
	URL: duplicated-title-2

## Force Updates

You can force keyword updates to make sure your client is using the proper URL, but doing that you won't be able to customize keywords. Open the `.xml` file from this extension and find the variable `$force_keyword`, then set it to `true` to force keyword updates on every change or `false` to update only when the field keyword is empty.

## Requirements

1. This module uses vQmod to work.
2. The option `System > Settings > Server > Use SEO URL's` has to be enabled.

## Installation

Use the **Extension Installer** to upload the file. Go to Modifications page and click the **Refresh** button for the changes to take effect.

## Compatibility

OpenCart 2.x (2.0.0, 2.0.1.1, 2.0.2.0)

## See also

- [GitHub](https://github.com/edirpedro/opencart-simple-seo-url-generator)
- [OpenCart](http://www.opencart.com/index.php?route=extension/extension/info&extension_id=18305)
