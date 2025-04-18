# System-Programming-in-Linux

Implement the following simple Unix utilities:

1. **pwd:** print working directory (check `man getcwd`).

2. **echo:** print a user input string on stdout (for example: `echo Hello World`).

3. **cp:** create a copy from a given source file to a given destination. For example,

``` bash
cp file.txt /tmp/file_copy.txt
```
This is a simple version of Unix cp program that supports only copying a file to an explicit destination as in the example.

4. **mv:** move a file to another place (might be with different name). For example,

``` shell 
mv /tmp/file.txt /tmp/new_name.txt

mv /tmp/file.txt /home/reda/new_name.txt

mv /tmp/file.txt /home/reda/file.txt
```

This is a simple version of Unix mv program that supports only moving files to an explicit destination as in the examples.

# Simple Unix Utilities in C

This repository implements simple versions of some classic Unix commands:

- `pwd`: print working directory
- `echo`: print user input to standard output
- `cp`: copy a file to a new location
- `mv`: move/rename a file

## Compilation

Each utility is a separate program. Compile them using `gcc`:

```bash
gcc pwd.c -o pwd
gcc echo.c -o echo
gcc cp.c -o cp
gcc mv.c -o mv
