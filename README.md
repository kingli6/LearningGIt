//READ ME FILE

//md stands for markdown "It's an easy way to format text in a file..?"

# One hashtag for main header

## Two hashtags for subheader 
https://www.youtube.com/watch?v=RGOj5yH7evk     //tutorial for git

>git clone <link>, to download files to computer through terminal.
>git status // in terminal to see the status of all files.
>git add .   //in terminal, . refers to all the files.
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

>git diff main //or git diff "branch name, without quotes" to see the difference on that file.
                //press q to quit
>git branch -d branch_name        //deleting branch

//extra commands
>cat filename.txt    //to print out the contents of the file.
>pbcopy < "path of your file"    //copies to clipboard
