## Splint - annotation-assisted static program checker
			 
### Splint Documentation

For documentation on Splint, please see https://www.splint.org.

### Splint Compilation

- Make sure to install these dependancies:
   - automake flex bison gawk ...

- Clone the project.

- Launch these commands:
```sh
$ aclocal
$ autoconf
$ autoheader
$ automake -a -c
$ ./configure
$ make
```

- Check if everything is ok by calling `src/splint --version`.
