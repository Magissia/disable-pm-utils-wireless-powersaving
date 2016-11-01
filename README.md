# disable-pm-utils-wireless-powersaving
On some WLAN controller, drivers do a poor job at power saving (1Mbps throttle is not bearable when browsing internet), this package aim to provide an easy solution to disable pm-utils power saving for wireless specifically.

This package does nothing fancy, it only adds a "wireless" empty file in /etc/pm/power.d/, it is easy to do the same thing without a package, but packages allows to track files and help people that don't want to touch the terminal.
