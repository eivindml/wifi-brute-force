# Wifi Brute-force Script

AppleScript to brute-force wifi passwords. Takes a couple of seconds for each try, so only realistic to try a couple of hundred different passwords. Usuful for public wifi's where the have a fixed core password, and changes a prefix or suffix each day (this is the purpose this was intended for).

## Usage

Change the following variables in the script, and run.

```
set BSSID to "NetworkBSSID"
set startString to "pwdStartString"
set computerUsername to "username"
set computerPassword to "password"
```

## Licensing

MIT.
