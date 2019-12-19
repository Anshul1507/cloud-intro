**Summary of Version-Control(Windows) Lessons**
===========================

## Table of Content

 - [Setup](#Setup)
 - [First Time Git Configuration](#FirstTimeGitConfiguration)
 - [EditorSetup](#EditorSetup)
 
 ## Setup
 - ```.``` working directory (current)
 - ```..``` parent directory
 - ```~``` home directrory
 - ```;``` allows you to write multiple commands in one line

__Note:__ some symbols are reserved like ```!!``` double-exclamation mark results in command repeatition

## FirstTimeGitConfiguration
-  **sets up Git with your name** <br/>
```git config --global user.name "<Your-Full-Name>"```

- **sets up Git with your email** <br/>
```git config --global user.email "<your-email-address>"```

- **makes sure that Git output is colored** <br/>
```git config --global color.ui auto```

- **displays the original state in a conflict** <br/>
```git config --global merge.conflictstyle diff3```

- **```git config --list```** <br/>


## EditorSetup
-  **Atom Editor Setup** <br/>
```git config --global core.editor "atom --wait"```

- **Sublime Text Setup** <br/>
```git config --global core.editor "'C:/Program Files/Sublime Text 2/sublime_text.exe' -n -w"```

- **VS Code Setup** <br/>
```git config --global core.editor "code --wait"```

## Additional Resources
 - [Git Terms pdf](http://video.udacity-data.com.s3.amazonaws.com/topher/2017/March/58d31eb5_ud123-git-keyterms/ud123-git-keyterms.pdf)
