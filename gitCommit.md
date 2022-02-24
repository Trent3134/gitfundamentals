

The command  will take all tracked changes (items added with  and package them up in what is called a commit.

Commits come with commit messages that are required for each commit. You add a message to a commit command by using the  flag followed by a message in quotes. A commit message  be anything, but best practice dictates that you should use that message to indicate the changes included in the commit.

For example, if we have an application we're working on where we just built out the ability to register new accounts, then you might have some variation of the following:
git add . 
git commit -m "add register functioality "
 then viewing the history of a git repo you can pinpoint the registration functionality was added

 

