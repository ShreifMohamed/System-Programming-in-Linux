# System-Programming-in-Linux

Implement the following simple Unix utilities:

1. **pwd:** print working directory (check `man getcwd`).

2. **echo:** print a user input string on stdout (for example: `echo Hello World`).

3. **cp:** create a copy from a given source file to a given destination. For example,

''' bash
cp file.txt /tmp/file_copy.txt
'''
This is a simple version of Unix cp program that supports only copying a file to an explicit destination as in the example.

4. **mv:** move a file to another place (might be with different name). For example,

''' shell 
mv /tmp/file.txt /tmp/new_name.txt

mv /tmp/file.txt /home/reda/new_name.txt

mv /tmp/file.txt /home/reda/file.txt
'''

This is a simple version of Unix mv program that supports only moving files to an explicit destination as in the examples.

## Important notes:

1. Check on the return values of the system calls / library routines you will use.

2. Each utility is a separate program / separate c file.

3. Ensure you match the Unix specs while implementing your utility (you can learn from the     
   behavior of the original utilities on your Linux machine).

4. Upload your code to your github (DO NOT upload the generated object files or executables).

5. Please include an organized README file that describe your repository, the compilation command(s) you used, and example of the output.
