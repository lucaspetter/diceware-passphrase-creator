# Diceware Passphrase Creator Changelog

## v1.2.0
###### August 9, 2015

Diceware-Passphrase-Creator-1.2.0.zip

SHA256: 83e90415a6669e9a97d81ddfa97dfe6410e7dc77b6e317d8d5ec38ac79b76a10

- Much simpler process: choose how many words, enter the dice roll numbers, done. No need to search through the word list, the program now looks up words automatically.
- Redesigned the large header area into a simpler menubar at the top.
- Rearranged text: descriptions for the main steps are now shorter and easier to follow, and more detailed information is now accessible from both the top menubar and the "more info..." links throughout the main steps.
- Renamed to "Diceware Passphrase Creator" because it's now more of a tool than an instruction guide.
- Changed the red dice icon image from a grid of 4 dice to a single die. This fits better in the new menubar and as a favicon.
- For Mac OS X, added the red dice icon to the file to replace the system's generic HTML document icon, making it look more like an application. The icon was compiled with [Icon Composer 2x](https://github.com/lemonmojo/IconComposer2x). This isn't possible on Windows or GNU/Linux, which can only do custom icons using separate files.
- Changed recommended number of passphrase words from 5 to 6.
- Changed the word count selector from a textbox to a pulldown menu to more reliably validate user input.
- Only allow numbers 1-6 to be entered into the dice roll text box.
- New counter shows how many remaining dice rolls are needed to get the desired number of words.
- Simpler options for adding random numerals and special characters, as well as new capitalization and spacing options. Just check or uncheck a box to apply the option to the passphrase automatically.
- Added icons to external links to visually differentiate them from links internal to the program.
- Advise clearing the clipboard when finished. This prevents others from learning your passphrase if you've copied it to the clipboard.
- Added strict [content security policy](http://content-security-policy.com/) <meta> header, allowing only inline elements and nothing external.
- Moved the PGP signature to a detached signature file rather than in the HTML.


## v1.1.0
###### July 23, 2015

Diceware-Passphrase-Instructions-1.1.0.zip

SHA256: 94d47d6b162b3dd8ac6948d2c1de6480d9ca8002164ac18a37c85dd08f5be12b

- Redesigned guide, with a nicer-looking header area.
- Added the red dice logo image to the header and set a favicon using "data:image/png;base64," [method](https://css-tricks.com/data-uris/).
- Added a link to Micah Lee's Diceware [article](https://firstlook.org/theintercept/2015/03/26/passphrases-can-memorize-attackers-cant-guess/) on The Intercept.
- Added "Back to top" link to make scrolling easier.
- Added step 0: "Set up." Ask whether the user trusts this computer and whether the user has dice available. Depending on choices, show different guide content.
- In step 1, briefly explain threat modelling and describe when to use more words in your passphrase.
- In step 1, parse the user's input in the textbox in case it's blank or has words like "five" instead of numbers like 5.
- In step 2, if the user has no dice, generate enough dice rolls for the number of words chosen in step 1.
- Added step 6: "Close this web browser." Recommend closing the browser windows (quitting on Mac) as a last step to clear temporary data such as cached CTRL-F searches, JavaScript variables, and scroll positions.
- Now using [semantic](http://semver.org/) version numbering.


## v1.0.0
###### June 3, 2015

Diceware-Passphrase-Instructions-1.0.0.zip

SHA256: 579a2099e6eac1fbca95ce1ae55a0bdd394f416a0546ed8205ea636a5d05b238

- Initial release
