# Options

You can make use of these options either by invoking zellij with
`zellij options [OPTION]` or binding them in the configuration file.

Eg. `zellij options --simplified-ui` is equivalent to `simplified_ui: true` in the config file.

|Option         | Config            |      Default   | Description
|---------------|-------------------|:--------------:|------------|
| default-mode  | default_mode      | normal         | The first mode on startup. |
| default-shell | default_shell     | $SHELL         | The default shell.         |
| disable-mouse-mode | disable_mouse_mode     | false         |  Disable the mouse capabilities.         |
| simplified-ui | simplified_ui     | false          | Request the Plugins to use a more compatible ui.  |
| theme         | theme             | default        | Switch to a theme configured under the `themes` section.  |
