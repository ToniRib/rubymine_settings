# RubyMine Settings

Shared RubyMine settings for the web app team at GoSpotCheck. Follows [this tutorial](https://www.jetbrains.com/help/ruby/2016.2/customizing-profiles.html).

## Importing

1. Clone this repository to your local machine
2. In RubyMine, go to File -> Import Settings
3. Navigate to where you cloned this repo and select the settings.jar file
4. Click Open
5. Allow all components to be imported
6. Once imported, allow RubyMine to restart
7. Once it restarts, open the preferences menu (`cmd` + `,`)
8. Navigate to Keymap
9. Under the listed keymaps, select 'GSC Inappropriators Keymap'
10. Click 'Apply' to select your new settings
11. From the preferences window, navigate to Editor -> Code Style
12. Select the GSC Inappropriators Code Style scheme
13. Click 'Apply' to select your new settings

## Team Settings

### Custom Keymap

* `ctrl + s` - Split Vertically
* `ctrl + w` - Increase font size
* `ctrl + q` - Decrease font size
* `ctrl + shift + o` - Move to opposite group
* `cmd + shift + p` - Open recent (project)
* `ctrl + shift + right` - Move right
* `ctrl + option + cmd + g` - Open in GitHub
* `ctrl + option + cmd + r` - Run all specs from anywhere in a spec file
* `ctrl + shift + a` - Open/close git annotations
* `ctrl + option + cmd + h` - Show git history of file

Want something different or a new keymap added? Let's discuss as a team!

### LiveTemplates

In JSX spec files, you can type:

* `it` - inserts an it block
* `test` - inserts an test block (new, preferred method for main web app)
* `desc` - inserts a describe block
* `be` - inserts a beforeEach block

All of these are in ES6 syntax.

In RSpec spec files, you can type:

* `saop` - inserts save_and_open_page
* `saos` - inserts save_and_open_screenshot
* `wait` - inserts wait_for_ajax

### Custom Ruby Style Formatting

See file.
