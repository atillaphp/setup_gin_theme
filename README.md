# Setup Gin Theme Recipe

A Drupal recipe to set up the Gin theme for a cleaner admin interface.

## Description

This recipe installs and configures the Gin theme and related modules (block, help, gin_login, gin_toolbar) for Drupal admin pages. It also imports the necessary configuration to set Gin as the admin theme.

## Installation

To use this recipe in your Drupal project:

1. Require the recipe in your composer.json:

   ```json
   "require": {
       "soganbilisim/setup_gin_theme": "*"
   }
   ```

2. Run `composer update` to install the recipe.

3. Apply the recipe:
   ```bash
   drush recipe recipes/setup_gin_theme
   ```

## Requirements

- Drupal 11+
- Gin theme [https://www.drupal.org/project/gin]
- Gin Toolbar module [https://www.drupal.org/project/gin_toolbar]
- Gin Login module [https://www.drupal.org/project/gin_login]

## Configuration

The recipe imports the following configuration:

- Enables dblog, syslog, views_ui, field_ui, config, devel modules

## License

GPL-2.0-or-later
