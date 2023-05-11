# Useful commands for developers in CMD
1. **Pwd** : shows your current working directory
> output: /C/Users/JohnDoe/commandPrompts
2. **Ls** : List all files and directories in the folder
   - Ls -a : show all hidden directories and files
   - Ls -al : detailed info about the files and directories
> output: cmdPrompts.md&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;gitBashPrompts.md
3. **Clear** : clear current cmd screen
4. **Cd** : change directory (navigate through the folders)
   - cd .. : navigate back one directory
   - cd - : navigate to the previous directory your were in
   - cd (path) : go to a directory directly
   - cd : go back home directly
5. **Mkdir** : create a new directory
> command: mkdir newFolder1  -> creates a new directory with name newFolder1
6. **Touch** : create a new file
> command: touch newFile1  -> creates a new directory with name newFile1
7. **Cp**: copy file 
> command: cp new-file.txt newFolder -> creates a copy of new-file.txt and move it to newFolder
8. **Mv**: move file
> command: mv new-file.txt newFolder -> move new-file.txt  to newFolder
9. **Rm**: remove files and directories
   - rm -r (folderName): to remove folders 
   > CAREFUL can delete everything and can't retrieve it back
   - rm (fileName): to remove files
10. **Cat**: concat the output of the files
    - cat (fileName): show file content
    - cat (file1) (file2): concat the two files content
11. **\>** : push content into a file (greater than sign)(anything with output can be pushed)(Overwrites)
    - cat (file1) > (file2) 
    > pushes the file1 content into file2
    - cat (file1) (file2) > (file3)
    > pushes the file1 and file2 content into file3
    - Ls > (file3)
    > pushes the Ls output into file3
> NOTE: >> doesn't overwrite it adds to the end
12. **Man** : documentation about commands
> Command:  man Ls

