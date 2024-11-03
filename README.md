# questden_BLICK2
Userscript to improve readablitiy of questden.org

WIP

## Feature Overview
* All features are optional
* Reading
  * Changes font-size, -type and paragraph-formatting
  * Invert-color option
  * Image fullview on mouse hover
* Reply form
  * Preview and autosave
  * Buttons for BBCODE-Formatting
  * Color-Picker with favourites
  * Icon-Picker with search and collections
* Watched threads
  * New sidebar and tabular display
  * Individual update and notification options
  * Import/export to website
  * Storing last-read position
* Export
  * Export threads to epub and cbz format
  * Settings to freely select posts for the output file
  * Automatic conversion of images formats
  * Multiple templates for generated epub files
  * One-click solution: "Save" to download epub/cbz
* Synchronization
  * Synchronize/Backup your settings and watched threads 
  * Export/Import to JSON-file for manual synchronization
  * Register an account to easily "upload"/"download" your settings
  * App: With an account, you can synchronize your watched threads and reading positions with my android app https://github.com/Dediggefedde/Questden_Blick_Reader

## How to install
Userscripts are basically little extentions for your browser.\
You will need to use an userscript handler to run scripts.\
I recommend [tampermonkey](https://www.tampermonkey.net/).\
In case you use google chrome, you will also need to [enable the extension developer mode](https://www.tampermonkey.net/faq.php?locale=en#Q209).

[Click here to install questden_blick2.user.js](/questden_blick2.user.js)

Confirm the prompt from Tampermonkey that you want to install the script and reload questden.org. Then the script is ready to run and will show a small blue nodge on the right.

To check wether the script is running, the Tampermonkey icon will show the number of active scripts as a red number next to it. If you click the icon, the script-name (questden_blick2) will show up in black and with a green switch next to it.

### Update/Disable/Delete
Tampermonkey will automatically update the script. To temporarily disable it, click the green switch next to the script name in the Tampermonkey menu to turn the font color grey. To remove the script, click on the entry and choose "delete".

## TODO
TODO here: images, #install, #manual\
TODO code: Spelling-check, App synchronization (different database)
