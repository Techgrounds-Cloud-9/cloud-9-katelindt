# File permissions


## Key terminology

- Input
- Output
- Redirection
- Pipe

- Commands: 
    
    - echo - display line of text/string that are passed as an argument. The echo can be used with a redirect operator to output to a file and not standard output.
    - cat - one of its most common usages is to print the content of a file onto the standard output stream. Other than that, the cat command also allows us to write some texts into a file.
    - grep - command-line tool used to search for a string of characters in a specified file. 


## Exercise
- Create a text file.
- Make a long listing to view the file’s permissions. Who is the file’s owner and group? What kind of permissions does the file have?
- Make the file executable by adding the execute permission (x).
- Remove the read and write permissions (rw) from the file for the group and everyone else, but not for the owner. Can you still read it?
- Change the owner of the file to a different user. If everything went well, you shouldn’t be able to read the file unless you assume root privileges with ‘sudo’.
- Change the group ownership of the file to a different group.




### Sources




****

### Overcome challenges




### Results

![screenshot](/00_includes/linux_05_screenshot.png)

