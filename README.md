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

**Package Control:**

1. Open `Command Palette` using menu item `Tools → Command Palette` or `CMD/CTRL` + `SHIFT` +`P`.
2. Choose `Package Control: Install Package`.
3. Type `Theme - DAneo` and press `ENTER`.

**Manually:**

##### Mac OS

```sh
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/
git clone "https://github.com/SublimeText/Theme-DAneo.git" "Theme - DAneo"
```


##### Linux

```sh
cd ~/.config/sublime-text-3/Packages
git clone "https://github.com/SublimeText/Theme-DAneo.git" "Theme - DAneo"
```


##### Windows

```sh
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
`"show_tab_close_buttons_on_left"` | `false`    | Show a close button on the left of the tab label _(ST 4075+)_
`"themed_title_bar"` (ST 4094+)    | `true`     | Enable themed title bar with hamburger menu.

For information about them please refer to the official [Sublime Text 3 Documentation](https://www.sublimetext.com/docs/3/themes.html#settings).


### Custom Theme Settings

#### Global Settings

Setting                                 | Default | Description
----------------------------------------|---------|-------------------------------------------------------------------
`"thin_scroll_bars"`                    | `false` | Controls whether to display a thin scrollbar by default. If `true` full sized scrollbars are displayed only if cursor is hovering.

#### Sidebar Settings

Setting                                 | Default | Description
----------------------------------------|---------|-------------------------------------------------------------------
`"show_disclosure_buttons"`             | `true`  | Controls whether to show the disclosure buttons in the sidebar
`"show_sidebar_icons"`                  | `true`  | Controls whether to show folder and file icons in the sidebar
`"show_sidebar_vcs_badges"`             | `true`  | Controls whether to show vcs status badges in the side bar
`"show_sidebar_closed_dir_badges"`      | `true`  | Controls whether to show vcs status badges for collapsed directories in the side bar if `show_sidebar_vcs_badges` is `true`
`"show_sidebar_opened_dir_badges"`      | `false` | Controls whether to show vcs status badges for expanded directories in the side bar if `show_sidebar_vcs_badges` is `true`
`"show_sidebar_ignored_label_colors"`   | `true`  | Controls whether to show vcs status of ignored files and folders by the color of their labels in the sidebar.
`"show_sidebar_tracked_label_colors"`   | `true`  | Controls whether to show vcs status of tracked files and folders by the color of their labels in the sidebar.
`"show_sidebar_untracked_label_colors"` | `true`  | Controls whether to show vcs status of untracked files and folders by the color of their labels in the sidebar.

#### Tab Settings

Setting                                 | Default | Description
----------------------------------------|---------|-------------------------------------------------------------------
`"file_tab_size"`                       | `"normal"` | Controls size of file tabs. Valid values are `"normal"` and `"small"`.
`"show_scroll_tabs_buttons"`            | `true`  | Controls whether to show the tab scroll buttons
`"show_new_tab_button"`                 | `true`  | Controls whether to show the create new tabs button
`"show_tabs_dropdown_button"`           | `true`  | Controls whether to show the tabs dropdown button

#### Panel Settings

Setting                                 | Default | Description
----------------------------------------|---------|-------------------------------------------------------------------
`"panel_input_highlighting"`            | `true`  | Controls whether to highlight background of highlighted panel input controls.
`"show_panel_close_button"`             | `false` | Controls whether to show the close button of the find and replace panels

### Editing the Theme

Most relevant theme attributes are defined as "variables" in the base theme so the themes can be tweaked just like a normal preferences file. This project is in early development state so there is no stable predefined list of variables to be exposed for quick user customization so far.
