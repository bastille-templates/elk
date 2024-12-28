## Now apply template to container
```sh
bastille create elk 14.1-RELEASE YourIP-Bastille


# Edii file /usr/local/bastille/jails/elk/fstab
fdesc	/dev/fd		fdescfs		rw	0	0
proc	/proc		procfs		rw	0	0


bastille bootstrap https://github.com/bastille-templates/elk
bastille template elk bastille-templates/elk
```

## License
This project is licensed under the BSD-3-Clause license.
