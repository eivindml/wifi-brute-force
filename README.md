# Wifi Brute-force Script

<p align="center">

<a href="license">
<img alt="License" src="https://img.shields.io/github/license/eivindml/wifi-brute-force.svg">
</a>

<a href="https://www.paypal.me/eivindml">
<img alt="Donate" src="https://img.shields.io/badge/$-donate-ff69b4.svg?maxAge=2592000&amp;style=flat">
</a>

<br />
<br />
</p>

<p align="center">
AppleScript to brute-force wifi passwords. Takes a couple of seconds for each try, so only realistic to try a couple of hundred different passwords. Usuful for public wifi's where the have a fixed core password, and changes a prefix or suffix each day (this is the purpose this was intended for).

<br />
<br />
</p>

## Table of Contents

- [Wifi Brute-force Script](#wifi-brute-force-script)
	- [Table of Contents](#table-of-contents)
	- [Usage](#usage)
	- [Installation](#installation)
	- [Acknowledgements](#acknowledgements)
	- [License](#license)

## Usage

Change the following variables in the script, and run.

```
set BSSID to "NetworkBSSID"
set startString to "pwdStartString"
set computerUsername to "username"
set computerPassword to "password"
```

## Installation

Copy `wifi-brute-force.applescript` to where ever you like on your computer.

## Acknowledgements

First version of script was written by `danhje`.

## License

[MIT](license) © [Eivind Mikael Lindbråten](http://madebymist.com)