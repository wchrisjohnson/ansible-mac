1) Install 1Password from the Apple Store; sync with iCloud.
2) Install work related SSH keys from 1Password.
	- copy files from 1Password to ~/.ssh
	- chmod 700 ~/.ssh/id_rsa
3) Install xcode CLI developer tools
	- xcode-select --install
4) Install pip
	sudo easy_install pip
5) Install battleschool
	sudo pip install battleschool
6) Create code folder
- git clone git@github.com:wchrisjohnson/ansible-mac.git wchrisjohnson-ansible-mac
- git clone git@github.com:wchrisjohnson/ansible-osx.git wchrisjohnson-ansible-osx
7) mkdir ~/.battleschool
8) Copy config.yml from wchrisjohnson-ansible-mac to .battleschool
9) Run battle for the first time
	- battle -K
