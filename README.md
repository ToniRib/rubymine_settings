# RubyMine Settings

Help RubyMine settings for a Rails + React based project. Follows [this tutorial](https://www.jetbrains.com/help/ruby/2016.2/customizing-profiles.html).

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
* `cmd + option + shift + down` - Move down
* `ctrl + option + cmd + g` - Open File in GitHub
* `ctrl + option + cmd + r` - Run all specs from anywhere in a spec file
* `ctrl + shift + a` - Open/close git annotations
* `ctrl + option + cmd + h` - Show git history of file

### LiveTemplates

#### JavaScript Testing

* `it` - inserts an it block
* `test` - inserts a test block
* `desc` - inserts a describe block
* `be` - inserts a beforeEach block
* `con` - inserts a context block

All of these are in ES6 syntax.

#### RSpec

* `saop` - inserts save_and_open_page
* `saos` - inserts save_and_open_screenshot
* `wait` - inserts wait_for_ajax

#### JavaScript/TypeScript
- `co` - adds the code owners annotation for the App Ecosystem team
- `cl` - adds `console.log('')` and puts your cursor inside the string
- `clv` - adds `console.log(':',)` and lets you type a variable which populates in the string and as the variable to log

#### Ruby
- `co` - adds the code owners annotation for the App Ecosystem team

### Custom Ruby Style Formatting

See file.
