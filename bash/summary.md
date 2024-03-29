**Summary of Bash Lessons**
===========================

## Table of Content

 - [Symbols](#Symbols)
 - [Bash Commands](#Bash-Commands)
 - [File Patterns](#Patterns)
 - [Additional Resources](#Additional-Resources)
 
 ## Symbols
 - ```.``` working directory (current)
 - ```..``` parent directory
 - ```~``` home directrory
 - ```;``` allows you to write multiple commands in one line

__Note:__ some symbols are reserved like ```!!``` double-exclamation mark results in command repeatition

## Bash Commands
 - ```echo hello``` prints hello on shell
 - ```$path='./Desktop' ``` declares a variable with value './Desktop'
 - ```cd $path``` navigates to the mentioned directory
 - ```pwd``` prints working directory
 - ```ls``` lists working directory
    - ```-l``` long description (works with __ls__ to list long description of the files) e.g ```ls -l```

 - ```mv [From] [To]``` moves files from __[From]__ to __[To]__
 - ```mkdir [DirectoryName]``` makes directory with given name __[DirectoryName]__
 - ```curl [URL]``` downloads the files from given url __[URL]__, put url in single-quotes to avoid special characters
    - ```-L``` follows the redirects (works with __curl__) e.g ```curl -L 'googel.com'``` redirects to 'https://www.google.com'
    - ```-o``` outputs the file (works with __curl__) e.g ```curl -o File.html 'https://www.google.com'``` outputs the downloaded page in File.html

 - ```cat [FileName]``` list all the content on the given file __[FileName]__ in the bash
 - ```less [FileName]``` list less of the given file contents, search with forwardslash ```/[KeyWord]```, quite with ```q```, move with spacebar or arrows
 - ```rm [FileName1] [FileName2]``` permanently removes files with given names [FileName1] and [FileName2]
    - ```-i``` prompts the user (works with __rm__) e.g ```rm -i File.html``` prompts user before permanently deleting the file

 - ```rmdir [Directory]``` removes a given [Directory] (directory must be empty otherwise it won't delete)

## Patterns
 - ```*.[extention]``` all files of given extenions e.g ```ls *.pdf``` lists all pdf files
 - ```Foo*``` all files starting with __Foo__
 - ```*Foo*``` all files containg __Foo__ key-word
 - ```*Bar*.[extenstion]``` all files containing __Bar__ key-word and having given extension

__Note:__ Bash is case-sensitive. ```cd /Desktop``` and ```cd /desktop``` are not equal

## Additional Resources
 - [The Bash Academy](http://www.bash.academy/)
 - [Bash Beginners Guide](http://www.tldp.org/LDP/Bash-Beginners-Guide/html/)
 - [Bash Programming HOWTO](http://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html)
