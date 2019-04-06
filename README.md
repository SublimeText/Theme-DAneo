# Theme - DAneo

_Theme - DAneo_ is an adaptive theme for Sublime Text 3 inspired by the popular _DA UI_.

The package is built up from scratch without any runtime code. It uses the new ST 3.2 _sublime-theme_ format to provide the different theme variants without duplicating every single theme rule.


### DAneo - Classic

![Classic](docs/assets/DAneo%20-%20Classic.png)


### DAneo - Elegant

![Elegant](docs/assets/DAneo%20-%20Elegant.png)


### DAneo - Minimal

![Minimal](docs/assets/DAneo%20-%20Minimal.png)


### DAneo - Origin

![Origin](docs/assets/DAneo%20-%20Origin.png)


### DAneo - Sodish

![Sodish](docs/assets/DAneo%20-%20Sodish.png)


### DAneo - Sublime

![Sublime](docs/assets/DAneo%20-%20Sublime.png)


## Installation

This package is not available via Package Control at the moment, so you need to manually clone the repository to your Data/Packages directory.

##### Mac OS

```shell
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/
git clone "https://github.com/SublimeText/Theme-DAneo.git" "Theme - DAneo"
```


##### Linux

```shell
cd ~/.config/sublime-text-3/Packages
git clone "https://github.com/SublimeText/Theme-DAneo.git" "Theme - DAneo"
```


##### Windows

```shell
cd "%APPDATA%\Sublime Text 3\Packages"
git clone "https://github.com/SublimeText/Theme-DAneo.git" "Theme - DAneo"
```


## Customization

The most general aspects of the GUI can be modified by the following settings in the _Preferences.sublime-settings_.

_Note: With [PackageDev](https://packagecontrol.io/packages/PackageDev) installed, all preferences are available via auto completion._


### Default Settings

The following general settings defined by Sublime Text are supported.

Setting                            | Default    | Description
-----------------------------------|------------|-------------------------------------------------------------------
`"always_show_minimap_viewport"`   | `false`    | Always visualise the viewport on the minimap, as opposed to only showing it on mouse over
`"bold_folder_labels"`             | `false`    | Show folders in the side bar in bold
`"enable_tab_scrolling"`           | `true`     | Allows tabs to scroll left and right, instead of simply shrinking
`"highlight_modified_tabs"`        | `false`    | Makes tabs with modified files more visible
`"mouse_wheel_switches_tabs"`      | `false`    | Use mouse wheel to change tabs, if `enable_tab_scrolling` is `false`
`"overlay_scroll_bars"`            | `"system"` | If `true` scrollbars are displayed only while scrolling. If `false` scrollbars are always visible. The default `"system"` enables overlay scrollbars on MacOS only.
`"show_tab_close_buttons"`         | `true`     | Show a close button on each tab.

For information about them please refer to the official [Sublime Text 3 Documentation](https://www.sublimetext.com/docs/3/themes.html#settings).


### Custom Theme Settings

Setting                            | Default | Description
-----------------------------------|---------|-------------------------------------------------------------------
`"show_disclosure_buttons"`        | `true`  | Controls whether to show the disclosure buttons in the sidebar
`"show_sidebar_icons"`             | `true`  | Controls whether to show folder and file icons in the sidebar
`"show_sidebar_closed_dir_badges"` | `true`  | Controls whether to show vcs status badges for collapsed directories in the side bar if `show_sidebar_vcs_badges` is `true`
`"show_sidebar_opened_dir_badges"` | `false` | Controls whether to show vcs status badges for expanded directories in the side bar if `show_sidebar_vcs_badges` is `true`
`"show_sidebar_vcs_badges"`        | `true`  | Controls whether to show vcs status badges in the side bar
`"show_scroll_tabs_buttons"`       | `true`  | Controls whether to show the tab scroll buttons
`"show_tabs_dropdown_button"`      | `true`  | Controls whether to show the tabs dropdown button
`"show_panel_button"`              | `true`  | Controls whether to show the _show panel button_ in the left corner of the status bar
`"show_panel_close_button"`        | `false` | Controls whether to show the close button of the find and replace panels


### Editing the Theme

Most relevant theme attributes are defined as "variables" in the base theme so the themes can be tweaked just like a normal preferences file. This project is in early development state so there is no stable predefined list of variables to be exposed for quick user customization so far. 
