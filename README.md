## Description
sweep2sleep is a gesture that exists on some Android ROMs that makes your device sleep if you slide right-to-left or left-to-right on the bottom of your screen.

This module disables sweep2sleep on ROMs with this feature by running the following command in the "late_start" service:

```sh
echo "0" > sys/sweep2sleep/sweep2sleep
```

#### Current Version
1.3

#### Changelog

* 1.3 (23.11.2017) - Updated description
* 1.2 (07.09.2017) - Updated to v1400 template
* 1.1 (25.07.2017) - Added to GitHub repo
* 1.0 (25.07.2017) - Initial release

#### Magisk Template
v1400

#### NOTICE

* You should use latest Magisk Manager to install this module. If you meet any problem under installation from Magisk Manager, please try to install it from recovery.