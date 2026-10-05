# Command Line Practice

## Points to Ponder

*Look through these now and then use them to test yourself after doing the assignment*

* What is the command line?

The command line is a text based interface that allow interaction with the computer's operative system by typing command directly into the terminal,shell, or console. 

* How do you open it on your computer?

On a mac you can press  command + space bar and type 'terminal'. It should find it. Click to open the terminal. 
In VSCode click on terminal in the top bar. In the drop down menu, click New Terminal. 

* How can you navigate into a particular file directory?
    - Where will `cd .` navigate you to? 
        Keeps you in your current directory.
    - Where will `cd ..` navigate you to?
        Navigates you one level up to the parent directory.
    - Where will `cd ~` navigate you to?
        Navigates you to your home directory.
    - Where will `cd /` navigate you to?
        Navigates you to the root directory.


* How can you display the name of the directory you are currently in?
    Type <pwd> into the terminal.

* How can you display the contents of the directory you are currently in?
    Type <ls> into the terminal.

* How can you create a new directory?
    Type <mkdir> into the terminal.

* How can you create a new file?
    Type <touch> into the terminal.

* How can you destroy a directory or file?
    Type <rm> into the terminal.

* How can you rename a directory or file?
    Type <rmdir> into the terminal.

## Assignment:

1. Complete this interactive course to get a great handle on the essentials of using a command-line interface and navigating directories - [Terminal Tutor](https://www.terminaltutor.com/)

2. Complete the below exercise locally on your own computer.

> Unlike Terminal Tutor, your own local terminal can autocomplete file names based on the directory you are in. For example, if you had a directory structure like:
> ```
> home
> |- essays
> |- documents
> |- doodles
> |- code
>```
> and you were currently at home (`~`) all you would need to type is `e` and then hit tab to autocomplete. If you typed `d` and hi tab it would list the two possible matching options (`documents`, `doodles`) prompting you to type enough for it to know for sure what you mean when you hit tab. Tab autocomplete is a powerful feature when navigating a filesystem through the terminal as it let's you know what is available at any given level and allows you to not have write out entire file/folder names completely. Try to take advantage of it!

## Exercise:

In this exercise you will practice creating files and directories and deleting them.

1. Navigate to your home directory (`~`)
1. Create a new directory in your home directory and  name it `test`
2. Navigate into the `test` directory
3. Create a new file called `test.txt` using the `touch` command
4. Open this file with VSCode (from the command line using `code test.txt`) give it some content, and then save
5. From within the cli, view the contents of the file you just created (`head`, `tail`, `less`)
4. Navigate one level up from the `test` directory to it's parent directory
5. Delete the `test` directory (it contains files now, so you might need to add an option to `rm`!)

## Saipher's notes

1. Installfest: done

2. Update Software: done

3. Get better internet service: done 

4. Replace Macbook Pro battery: Still need to complete
