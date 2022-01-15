download https://git-scm.com/downloads
git --version
git init 						// declare current folder as git master for this project
git status
git add . 						// all the files have been added from working directory to stagging area
git rm --cached <file>			// to unstage
git commit -m "version 1.0"		// commit files to include files from stagging area to git directory

git config --global user.email "sumeer@example.com"
git config --global user.name "Sumeer Riaz"

////////////////////////////////////////////////////////
Quick setup https://github.com/Sumeer-Riaz/Git-Tutes.git
Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.

…or create a new repository on the command line
echo "# Git-Tutes" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Sumeer-Riaz/Git-Tutes.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/Sumeer-Riaz/Git-Tutes.git
git branch -M main
git push -u origin main
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

///////////////////////////////////////////////////////

git remote add origin https://github.com/Sumeer-Riaz/Git-Tutes.git
git push -u origin master
ssh-keygen -t rsa -b 4096 -C "sumeer@example.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519 		// to add identity
clip < ~/.ssh/id_rsa.pub		// this command will copy public key
								// add this key in ssh key in github
git add .
git commit -m "changed in current file"
git push -u origin master
git pull origin master

git diff git-readme.txt
git reset git-readme.txt