# Cordada's Pico CSS
This repository is a fork of [Pico CSS](https://picocss.com) with some modifications used on our custom themes.

## Create a new theme
In order to create a new theme first of all create a scss file in the `cordada` folder. You can use the `timetracker` as an example. In this file you'll set the $theme-color variable to your new theme.

You need to update the following files with your new theme:
- `pico/scss/themes/cordada/_theme_colors_.scss`
- `pico/scss/colors/_index.scss` # notice here you need to add all the colors and then the theme to the map.

## Other modifications
- `pico/scss/themes/cordada/_dark.scss` added the $cordada-dark-background. 
- `pico/scss/colors/_index.scss` updated the white color.