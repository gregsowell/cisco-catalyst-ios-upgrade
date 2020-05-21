# cisco-catalyst-ios-upgrade
Scripts for upgrading Cisco catalyst switches<br>
<br>
ios-list-version.yml - shows the currently running firmware on a catalyst switch<br>
<br>
ios-3550-upgrade.yml - Checks running version of IOS, and upgrades if required<br>
new_image: should be the desired image to be installed<br>
The TFTP server holding the image should be hardcoded in the "tftp the new image" play<br>
<br>

