# Misc Startup Scripts
Various Startup Script Examples

Working examples are as follows:

0. startup_script_generic.sh           -  This is a generic startup script example, should work on most platforms as an example.

0. startup_script_openwrt.sh           - SSH example for OpenWRT Barrier Breaker SSH, will track SSH port based on Open WRT config.  Assumes SSH enablement file in /etc/weaved

0. startup_script_aria_arietta.sh      - SSH example for the Aria/Arietta G25 from http://www.acmesystems.it, Assumes SSH provisioning file in /etc/weaved and the weavedConnectd.arm-eabi-4.4.0.static binary (https://github.com/weaved/misc_bins_and_scripts/blob/master/connectd/weavedConnectd.arm-eabi-4.4.0.static) .  But script is useful for any Debian "Wheezy" system.



* The above scripts assume a Weaved enablement file (https://github.com/weaved/installer/tree/master/weaved_software/enablements) in /etc/weaved

* They can be modified to use other enablement files.  This scripts assume a seperate startup script that points to service you wish to enable.

## Example

-- TBD
 
