# mkchroot
A bash script to help manage users in a chroot jail for SSH usage.

##### Usage
```
usage: mkchroot [option]

example: mkchroot --create=acidvegas bash cp irssi ls mkdir mv rm screen wget

options:
	-c, --create=USER   <cmds>   create a new chroot jail
	-d, --destroy=USER           destroy a chroot jail
	-l, --list                   list chroot jails
	-h, --help                   display this help and exit
```