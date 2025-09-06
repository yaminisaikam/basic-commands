# Basic Linux Terminal Commands
1.echo :- displays a line of text in the terminal
          Example: echo "Hello World"
2.date :- prints the current system date and time
          Example: date 
3.calculator in Terminal :- you can perform arithmetic using 'expr'. Make sure to leave spaces around operators.
          Example: `expr 3 + 5` 
          Output: 8
          here we can use +,-,*,/ operators
4.figlet :- turns text ino ASCII art
          Example: figlet "Hello"
          -here it can also show the ASCII art in different fonts 
          Example: figlet -f slant "I Love Github"
          here
            -f is a command option in linux. It specifies which font style to use.
             slant creates slanted effect.

Note: we call folders as 'directories' in Terminal and file names and directory names are case sensitive.
5.pwd :- 
         -pwd stands for print working directory.
         -As the name it prints the directory you currently working on
          Example:pwd
          output:/home/user_name
6.cd :-
          -cd stands for change directory.
          -As the name says it is used to change the current directory in the terminal.
          Example1: cd /home/username/Documents #go to specific directory
          Example2: cd ..                       #go up one directory level
          Example2: cd ~                        #go to your home directory
7.ls :-
          -ls(list) shows all the files & directories in your current location.

8.mkdir :- 
          -makes(creates) a new directory
          Example: mkdir linux_practice     #creates a new directory named linux_practice
          (look in Creation of Files and Directories.txt file for step by step process of the creation)
9.touch :- 
          -command that creates an empty file if it doesn't exists.
          Example: touch github.txt             #a file can be of any type like .txt or .py etc
10.cat :- 
          -short for concatenate; but often used to display 'file contents'.
          Example: cat github.txt               #a file can be of any type like .txt or .py etc
11.help :-
          -one of the best thing about linux is its extensive build-in help system.
          -to get quick summary of a command you can use '--help' option.
                Example: ls --help             #shows brief description of ls and its most common options.
          -for more detailed information use the 'man' command (short for mannual)
                Example: man ls                #opens full mannual page for ls.
12.file :- 
          -find out what kind of file  a file is.
          -It will show you description of the file's contents.
                Example: file github.txt
13.less :-
          -if you use 'less' command then text is displayed in paged manner, so you can navigate through text file page by page.
                 Example: less /home/user/Documents/github.txt
          use the following commants to navigate through 'less'
          q for quit(go back to you shell(dotn't worry you'll know about what shell mean in following updates))
          page up ,page down ,up,down for navigate through the page
          g to move to the beginning of the file
          G to move to the end of file
          /search    (in search place after / you type the word or sentence you need to search for)
          h if help needed
14.mv :-
          -mv command is used for moving files and also for renaming them.
          -quiet similar to 'cp' command in terms of flag and functionality.
          a)renaming file 
             mv oldfile_name newfile_name
          b)move a file to a different directory
             mv file2 /home/user/Documents
          c)move more than one file
             mv file_1 file_2 /directory
          d)renameing directory
             mv old_director new_directory
          ""note: use files that already exists""
15.find :-
          a)finding files
             Example: find /home -name puppies.jpg
          b)finding directories
             Example: find /home -type d -name Myfolder
          -one cool thing about find is, it will look inside any subdirectories that directory may have as well.
16.whatis :-
          -if you are feeling doubtful about what a command does use 'whatis' command.
          -it provides brief description of command line programms.
              Example: whatis cat     #gives brief description of cat.
17.alias :-
          -you can create an alias name for a command.
              Example: alias hi='ls'
          -now instead of typing 'ls' you can type 'hi'.
          -but remember that the alias name will be removed once you rebooted your terminal.
          -And to remove alias without rebooting use 'unalias' command.
              Example: unalias hi
