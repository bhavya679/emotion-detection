This is an android app for emotion detection


how to setup your git to update your work on github

1) make a new directory for the project (say "software")
2) change directory to "software" directory
3) if git is installed in your pc do "git init" 
4) do git remote add "url of your repository" (e.g mine is "https://github.com/ritveeka/emotion-detection/")
5) you can see the url listed twice after typing the command "git remote --verbose"
6) do "git checkout -b "your name" (e.g git checkout -b ritveeka) 
7) do "git branch" you can see two branches master and "your name", the highlighted branch is the branch you are currently working on 
   make sure the branch with your name is in green , otherwise do "git checkout "your name" " now your branch will change 
8) make files the way you do in linux normally , after completing your work do "git add "file name" " and then "git commit "file name"" 
9) now whenever you are satisfied with your work change your branch to master "git checkout master" 
10) do "git push origin master" this will update your work on your repository.

***the other branch can be anything like (development or working) your name is just for example***
