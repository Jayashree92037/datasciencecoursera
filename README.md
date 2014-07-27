datasciencecoursera
===================

Coursera Class
This is a readme file -
In order to start a new repository, we do the following steps - 
Create a directory for your repo. I have a directory named gitprojects in my home directory; all projects I want to track with Git get their own directory in that one. You can create this directory either in the Finder or from within Terminal (via the mkdir command).
In Terminal, change to the new directory (from here on known as your local repo).
Type git init to start tracking your local repo and all subfiles and folders.
Create your remote repo on GitHub. Once you're finished, click on the Copy to Clipboard icon at the right side of the Quick Setup window: 
If you've already created the repo and are looking at the regular page, use the Copy to Clipboard icon in the Clone URL section in the bottom right (click on the HTTPS link first (circled in blue), then on the Copy button (circled in red)):

Back in Terminal, type in git remote add origin, then paste the URL that is on your clipboard (Command-V); hit enter to accept it.
Type in git pull origin master to merge any files that exist in your remote repo (such as the README.md file which is created by default in GitHub) into your local repo. Note that you can actually do this step any time before step 10.
Create your files in your editor of choice. If we're talking the HelloWorld.md file, for Mac users I'd recommend TextWrangler: it's free, and is focused on text editing for programmers. If you want to use TextEdit, which comes with your Mac, make sure you switch to plain text (Format >> Make Plain Text) before saving it. For Windows I like Notepad++; Linux users probably already have a favorite text editor. Save your file(s) into your local repo with the correct name and extension.
Type git add -A to stage all new and changed files (this is the equivalent of git add . followed by git add -u).
Type git commit -m "this is my clever comment about what changes have been made" to commit the changes. If you forget to include the comment, Git will open the default text editor your shell uses. For OS X, that's Vim: type in your comment, then hit the Escape key and type in :x to save the text and quit.
Finally, type in git push origin master to push all of your changes up to the remote repo. Go there and verify that they are indeed there (you may have to refresh the page if it's been open all this time).
