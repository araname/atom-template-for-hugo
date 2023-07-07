# Atom Template for Hugo
Allows Hugo to generate Atom feeds to your site

## Installation
Clone or download this repo to `<your-site-dir>/themes/atom-template-for-hugo` directory.

## Configuration
Append a line to the site configuration file, indicating the current theme:
1. Add `atom-template-for-hugo` as the left-most element of the theme list variable. For example:
    ```
    theme = ['atom-template-for-hugo', 'my-theme']
    ```
2. Add `Atom` to all the page kinds for which you want to create Atom feeds (Default is `['HTML', 'RSS']`):
    ```
    [outputs]
    home = ['HTML', 'Atom', 'RSS']
    section = ['HTML',  'Atom', 'RSS']
    taxonomy = ['HTML',  'Atom', 'RSS']
    term = ['HTML',  'Atom', 'RSS']
    ```
