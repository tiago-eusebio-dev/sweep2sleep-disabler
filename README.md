## Description
sweep2sleep is a gesture that exists on some Android ROMs that makes your device sleep if you slide right to left on the bottom of your screen.

This module disables sweep2sleep on ResurrectionRemix N ROMs (not tested on other ROMs) by running the following command in the "late_start" service:

```sh
echo "0" > sys/sweep2sleep/sweep2sleep
```

#### Current Version
1.1

#### Changelog

* 1.1 - Added to GitHub repo
* 1.0 - Initial release

#### Magisk Template
v4

#### NOTICE

* You should use latest Magisk Manager to install this module. If you meet any problem under installation from Magisk Manager, please try to install it from recovery.