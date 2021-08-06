//READ ME FILE

//md stands for markdown "It's an easy way to format text in a file..?"

# One hashtag for main header

## Two hashtags for subheader 
https://www.youtube.com/watch?v=RGOj5yH7evk     //tutorial for git

>git clone <link>, to download repo folder to computer through terminal.
>git status // in terminal to see the status of all files.
>git add .   //Your asking git to track the file.  . refers to all the files.
>git commit -m "message here" -m "second message"    //-m is for message, you need to have a message to commit your files.

git commit -am "message"    /-am adds and commits. which skips the add . step. Only available if the file has been submitted before.

>git push
>git push -u origin "nameofthebranch"    //-u is short for --set-upstream
>git init    //Initialized empty Git repository in D:/C#programming/02Git/Own projects/.git/
On branch master

>git remote add origin "ssh link"  //when git push origin master doesn't work
>git remote -v     //to check if the above worked. and now you can type
>git push origin master    //if you don't want to type origin master everytime, you can do "git push -u origin master"

>git branch // to check which branch your in
>git checkout -b branch_name //creating branch with -b (without -b, you'll be switching to other branches)

press tab to auto complete
press spacebar to scroll down

>git diff main //or git diff "branch name, without quotes" to see the difference on that file. or diff against main, if you're on another branch.
                //press q to quit
>git branch -d branch_name        //deleting branch

>git merge master        // if your on another branch, you can merge with master

If you regret doing a git add . or git add filename
>git reset README.md OR git reset
>git reset HEAD     //to reset a commit. "HEAD" is a pointer to the last commit
>git reset HEAD~1   //for resetting 1 commit further

>git log        //will show all the commits in chronological order.
>git reset 15181e15123213123sdsf //the numbers are hash of the commit.
>git reset --hard cec454523424      //will remove completely till that commit, got to test this

//extra commands
>cat filename.txt    //to print out the contents of the file.
>pbcopy < "path of your file"    //copies to clipboard
