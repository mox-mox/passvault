passvault
=========

Passvault is a tool to manage your passwords in a gpg-encrypted text file that I created out of challenge of sort. To privide security, passwords will only be written encrypted, all unencrypted processing is done within pipes.

Things this program relies upon:
  * gpg
  * grep
  * bash (maybe some other shell might work as well, but that is untested)

Usage:
  * Install into Your $PATH, for example in ArchLinux in /usr/bin
  * Make Passvault executable
  * Make Passvault editable only editable by root
  * Call passvault -s to setup
  * (optionally) call passvault -e </path/where/to/save/the/encrypted/passwords/to> to set a location for the password vault
  * Call passvault -a to passwords
  * Call passvault -d to delete passwords
  * Call passvault -l <some fragment of the line you want to see> to look up a password line
