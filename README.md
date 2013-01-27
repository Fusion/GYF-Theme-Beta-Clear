# What is this?

This is a sample theme for GYF Theme Launcher.

I expect lots of things to be broken so, well, you've been warned :)

-Chris.

# Documentation

Theming GYF is, at this point, very basic and requires no programming.

Simply clone this project, add the drawables needed and update the `theme_config.xml` file and that's it.

## Drawables

A rule of thumb is that you should make two drawables available: one for each side. The left one will be suffixed `_left` and the right one `_right`

Currently, only one drawable can be added: `list_background` which will provide a background for the list element itself. The top header and quick jump ribbon are not ready to get their own background.

Note that this background feature is buggy when scrolling the list up or down.

## Values

In the xml file mentioned earlier, you will be able to specify many more configuration settings than what can currently be done with the already busy preference settings screen.

For starter, the following settings are available:

`preferences_ui_list_bgnd_color` is the color selected for the list's background unless a background asset is made available, see _drawables_ above

`preferences_ui_list_text_color` is the color used to display the application names

`preferences_ui_list_alpha` is a decimal value between 0 and 1; if set to 1, a background image cannot be displayed at all and only the background color will be visible

`preferences_ui_ribbon_bgnd_color` is the color selected for the quick ribbon's background

`preferences_ui_ribbon_text_color` is the color used to display the quick jump letters

`preferences_ui_ribbon_alpha` is a decimal value between 0 and 1; 0 means that no background is visible



