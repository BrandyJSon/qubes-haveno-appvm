# qubes-haveno-appvm
dom0 script to create a haveno appvm

# Usage
./haveno-qubes-install.sh [options]

	-c : Reinstall template if already exists
	-s : Build haveno from source instead of deb package
	-r [git repo url] : Install an unoffical haveno fork hosted at the suppplied web url
	-u : Do not harden appVM
	-f [compressed haveno deb] : Specify release asset that contains zipped haveno deb (default: haveno-linux-deb.zip)
	-n [appVM name] : Name of haveno appvm (default: haveno)
`
# Functionality
Allows for automatic creation of a haveno AppVM based on debian-12-minimal template. Ensures tor over tor is not occuring when using haveno. Performs hardening and minimzes the attack surface of the vm by default. Allows for install of unoffical haveno clients for easy access to mainnet trading. 
