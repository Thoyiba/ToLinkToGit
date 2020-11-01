# ToLinkToGit
How to link an already existing project in Rstudio with Git\
1)Create a normal project in Rstudio (example :named as 'ToLinkToGit')\
2)Open bash in this project folder\
3)git init   ====>this initialises our project directory as a git repo\
4)git add .  ====> adds all files to this repo created (please check the '.' at the end)\
5)git commit -m "Initial Commit" =====> first commit done in this repo\
6)Open github and craete a new repository with the exact same project name (ToLinkToGit), do not create Readme.txt,license and .ignore files\
7)Now you will see a page with below commands to be done in bash "inorder to push an existing repo from commandline"\
        git remote add origin https://github.com/Thoyiba/ToLinkToGit.git\
        git branch -M main\
        git push -u origin main\
8)Reload the github page , there it is with your initial commit\
9)Now check the Rstudio.You will find the 'Git' tab in the Environment section of your ToLinkToGit project.
