Sample readme file for autotools-example project.

Use the following commands to build the project:

```bash
aclocal
autoconf
automake -a
./configure
make
```

The generated binary file is `src/hello`

`make install` will copy it to `/usr/local/bin/hello` by default which needs root privilege.
`make clean` removes generated files during build process.
`make dist` creates an archive of the current project source files.