# 0.3.0

### Update

- You can now pass `class` to the `product_variant` tag to style the select


# 0.3.0

### Update

- Docs have been updated with more relevant information that hopefully clears a few things up.

### Removed

- Removed the compile scripts as it didn't make sense.

# 0.2.0

### New

- Added in a way to check for qty changes on the cart screen.
- Tag for loading product variants with default settings.
- JavaScript can now be included compiled (with theme) or modular for you to customise.

### Update

- Completely rewrote the front end JavaScript so it's modular and you can import it at your will. Publishes to `resources/js/vendor/shopify`.
- Updated tag for loading in compiled js. `{{ shopify_scripts }}`
- Service provider no longer publishes everything on install.

# 0.1.2

### New

- Added trait for importing all products
- Added webhook for when a product is deleted

### Fix

- Fixing large data set imports

# 0.1

- Initial Release