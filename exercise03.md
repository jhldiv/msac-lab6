# Exercise 3 - Configuring your first repository

1. Enable color

        git config --global color.ui auto

2. Set your name

        git config --global user.name "John Doe"

3. Set your email address

        git config --global user.email "john.doe@somewebsite.com"

4. Why did we use the `--global` flag?  (What does that do?)
Git (an acronym of Global Information Tracker) is a distributed version control system that is used to store files/code and then the content can be accessed either locally or remotely. It facilitates the programmers to work in parallel manner and as it tracks the recent changes made in the code and the developers can fall back to the previous versions also.
It allows the user to configure settings in the "global" file. --https://linuxhint.com/

5. Check your git config to show the changes you have made

        git config -l
[jhl@truffle my_repository]$ git config --list
user.name=jhldiv
user.email=jhldiv@gmail.com
color.ui=auto
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
For more information, check out [Customizing Git Configuration](https://www.git-scm.com/book/en/v2/Customizing-Git-Git-Configuration)