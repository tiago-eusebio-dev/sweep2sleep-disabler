sweep2sleep is a gesture that makes your device sleep if you slide right to left on the bottom of your screen.
This module Disables sweep2sleep on RR N ROMs (not tested on other ROMs) by running the following command in the "late_start" service:

`echo "0" > sys/sweep2sleep/sweep2sleep`