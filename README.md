sweep2sleep Disabler
==========

sweep2sleep is a gesture that exists on some Android ROMs (eg. Resurrection Remix) that makes your device sleep if you slide right or left on the bottom of your screen.

This module disables sweep2sleep by running the following command in the "late_start" service:

`echo "0" > sys/sweep2sleep/sweep2sleep`


## Changelog
* v3   (18.11.2018) - Update to Magisk v17000 template
* v1.2 (07.09.2017) - Update to MAgisk v1400 template
* v1.1 (25.07.2017) - Added to GitHub repo
* v1.0 (25.07.2017) - Initial release


## Notice
* Take a full backup before installing the module.
* You should use latest Magisk Manager to install this module. If you meet any problem under installation from Magisk Manager, please try to install it from recovery.


## Links
* [![XDA Thread](https://img.shields.io/badge/XDA-Thread-orange.svg)](https://forum.xda-developers.com/apps/magisk/magisk-sweep2sleep-disabler-t3681631)
* [![Magisk](https://img.shields.io/badge/Magisk-v17%2B-brightgreen.svg)](https://forum.xda-developers.com/apps/magisk/official-magisk-v7-universal-systemless-t3473445)


## Credits
* <a href="https://forum.xda-developers.com/member.php?u=4470081">topjohnwu@xda</a> for developing Magisk


Copyright (C) 2017-2018 tfae (tfaeusebio@gmail.com)
