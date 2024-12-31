# Questden_BLICK2
Userscript to improve readability of questden.org

A detailed documentation of the features can be found in the [Wiki](https://github.com/Dediggefedde/questden_BLICK/wiki).

## Feature Overview
* All features are optional
* **Reading** <img align="right" width="100" src="/Screenshots/01_readability.jpg" />
  * Changes font-size, font-type, and paragraph formatting
  * Invert-color option
  * Image full view on mouse hover
* **Reply Form** <img align="right" width="100" src="/Screenshots/02_replyform.jpg" />
  * Preview and autosave
  * Buttons for BBCODE formatting
  * Color picker with favorites
  * Icon picker with search and collections
* **Watched Threads** <img align="right" width="100" src="/Screenshots/03_watchedThreads.jpg" />
  * New sidebar and tabular display
  * Individual update and notification options
  * Import/export to website
  * Storing last-read position
* **Export** <img align="right" width="200" src="/Screenshots/04_exportEpub.jpg" />
  * Export threads to EPUB and CBZ format
  * Settings to freely select posts for the output file
  * Automatic conversion of image formats
  * Multiple templates for generated EPUB files
  * One-click solution: "Save" to download EPUB/CBZ
* **Synchronization** <img align="right" width="100" src="/Screenshots/05_syncSite.jpg" /><img align="right" width="100" src="/Screenshots/06_app.jpg" />
  * Synchronize/backup your settings and watched threads
  * Export/import to JSON file for manual synchronization
  * [Register an account](https://phi.pf-control.de/tgchan/reg.php) to easily "upload"/"download" your settings
  * App: With an account, you can synchronize your watched threads and reading positions with my Android app [Questden Blick Reader](https://github.com/Dediggefedde/Questden_Blick_Reader)

## How to Install
Userscripts are basically little extensions for your browser.\
You will need to use a userscript manager to run scripts.\
I recommend [Tampermonkey](https://www.tampermonkey.net/).\
If you use Google Chrome, you will also need to [enable the extension developer mode](https://www.tampermonkey.net/faq.php?locale=en#Q209).

Here is an install link: https://greasyfork.org/en/scripts/522343-questden-blick2
Otherwise, you can view the file ["questden_blick2.user.js"](https://github.com/Dediggefedde/questden_BLICK/raw/refs/heads/main/questden_blick2.user.js?raw=true) from the list above.

Confirm the prompt from Tampermonkey that you want to install the script and reload questden.org. Then the script is ready to run and will show a small blue button on the right.

To check whether the script is running, the Tampermonkey icon will show the number of active scripts as a red number next to it. If you click the icon, the script name (questden_blick2) will show up in black, with a green switch next to it.

### Update/Disable/Delete
Tampermonkey will automatically update the script. To temporarily disable it, click the green switch next to the script name in the Tampermonkey menu to turn the font color grey. To remove the script, click on the entry and choose "Delete".
