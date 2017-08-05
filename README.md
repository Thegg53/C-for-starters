# Latest files
Execises and when to do them

snake.html (a simple JS version of snake, inside a html page to run in any browser)

# C-for-starters
Helping my cousin out to learn C. There will be a few links and sample programs until he works is way up to a snake game.

### How to Compile and execute a program: 

    gcc -o nameOfExecutable nameOfProgram.C (press enter)

    nameOfExecutable (press Enter)


### Windows installations:

MinGW link: 
  
  https://sourceforge.net/projects/mingw/?source=typ_redirect

How to install MinGW: 
  
  https://www.youtube.com/watch?v=0Gj5TZORCE0

setting environment variable: 
  
  https://superuser.com/questions/949560/how-do-i-set-system-environment-variables-in-windows-10



### codeBlocks:


http://www.codeblocks.org/downloads



### Ubuntu:

gcc should be pre-installed.

You can use gedit to edit text, or download sublime text 3. Call sublime by writing subl in the terminal.

##### How to configure the path to avoid writing ./ after code compillation:


http://www.akira.ruc.dk/~keld/teaching/CAN_e14/Readings/How%20to%20Compile%20and%20Run%20a%20C%20Program%20on%20Ubuntu%20Linux.pdf


Open the terminal in the root:

    gedit .profile


Copy and paste the following in the .profile, save and close it:

    export PATH=.:$PATH


Back in terminal:

    source .profile
    
    
There might be a need to call __source .profile__ every time  you call a terminal window. __Otherwise__, just get used to write __./__ before calling the new file. Example:
        
        gcc -o hi helloWorld.c
        ./hi



### The New Boston series of tutorials:


https://cosmolearning.org/courses/introduction-c-programming-by-thenewboston/



## Basic debugging:

using console and basic gdb 

https://www.youtube.com/watch?v=d_LG0PBj-xI



online debugger:

https://www.onlinegdb.com/



quick guide on how to use the online debugger:

https://www.onlinegdb.com/blog/brief-guide-on-how-to-use-onlinegdb-debugger/
