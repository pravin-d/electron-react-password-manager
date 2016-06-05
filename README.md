# electron-react-password-manager

*Yay another useless password manager!*

**Frontend needs some love, but it all works**

## > Installation

### Downloads

-   [win32-x64](kappa)
-   [win32-ia32](kappa)
-   [linux-ia32](kappa)
-   [linux-x64](kappa)
-   [darwin-x64](kappa)

**After download:**
 *Unzip contents somewhere and run the executable, easy as that.*

### Development

-   `cd src`
-   `gulp`

*Every time you change files in the src folder;*
*gulp will transpile, minify, concat or restart the process for you*

## > Features

-   Node.js, ES6, Built with [Electron](http://electron.atom.io/)
-   Frontend built with [React](https://facebook.github.io/react/) And [React Bootstrap](https://react-bootstrap.github.io)
-   Random salt for PBKD2F that is generated on first run
-   up to 400k PBKD2F iterations
-   up to 4096bit RSA passphrase encryption (will take you about 1 minute)
-   Stores only passwords encrypted, to save time for decryption :)
-   No accounts just a password you come up with to rule them all
-   Your password is your passphrase for your encryption key

## > Showcase

![](http://i.imgur.com/yJsAW7u.png)
![](http://i.imgur.com/x87128U.png)
![](http://i.imgur.com/GECgz3D.png)
