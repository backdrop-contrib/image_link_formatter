# Image Link Formatter

This module allows you to format image fields to link to a specified `Link`
field.

## Installation

- Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules).

## Dependencies

- The core Image and Link modules must be enabled.

## Configuration and Usage

After successful installation, browse to the "Manage Display" settings page
for the entity (e.g. for a content type or taxonomy vocabulary), which has an
image and a link field, to configure the formatter. Select "Image Link 
Formatter" and in the configuration you should be able to specify to link
to the `Link` field value. When a user sees the image for this display, it
will be linked to the URL provided in the `Link` field.

More details may be found (or added) in the [Wiki](https://github.com/backdrop-contrib/image_link_formatter/issues)

## Developers

If your module requires the library provided by this wrapper, you can access the
JavaScript by:

- Requiring this module as a dependency in your module
- Loading the file as follows: `backdrop_add_js(  backdrop_get_path('module', 'image_link_formatter') . '/js/image_link_formatter.js' );`

## Issues

Bugs and Feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/image_link_formatter/issues)

## Current Maintainers

- [Laryn Kragt Bakker](https://github.com/laryn), [CEDC.org](https://CEDC.org) 

## Credits

- Ported to Backdrop by [Laryn Kragt Bakker](https://github.com/laryn), [CEDC.org](https://CEDC.org)
- Maintained for Drupal by [DYdave](https://www.drupal.org/u/dydave)

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.