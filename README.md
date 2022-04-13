# Eletronorte.github.io 
##  How to change the URI (URL) for a remote Git repository

git remote -v
--> View existing remotes
--> origin  https://github.com/... (fetch)
--> origin  https://github.com/... (push)

git remote remove origin

git remote set-url origin https://github.com/eletronorte/eletronorte.github.io.git
--> Change the 'origin' remote's URL

git remote -v
--> Verify new remote URL
--> origin  https://github.com/eletronorte/eletronorte.github.io.git (fetch)
--> origin  https://github.com/eletronorte/eletronorte.github.io.git (push)