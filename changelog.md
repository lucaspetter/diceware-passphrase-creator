# Diceware Passphrase Creator Changelog


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
