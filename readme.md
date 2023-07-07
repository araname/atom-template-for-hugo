# Atom Template for Hugo
Allows Hugo to generate Atom feeds to your site

## Applying
1. Clone or download this repo to `<your-site-dir>/themes/atom-template-for-hugo` directory.
2. Add these your site’s `config.toml`:
    1. Add `atom-template-for-hugo` as the left-most element of the theme list variable. For example:
    ```
    theme = ["atom-template-for-hugo", "my-theme"]
    ```
    2. Add `Atom` to all the page kinds for which you want to create Atom feeds (Default is `["HTML", "RSS"]`):
    ```
    [outputs]
    home = ["HTML", "RSS", "Atom"]
    section = ["HTML", "RSS", "Atom"]
    taxonomy = ["HTML", "RSS", "Atom"]
    term = ["HTML", "RSS", "Atom"]
    ```
