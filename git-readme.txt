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
clip < ~/.ssh/id_rsa.pub		// this command will copy --> ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQDP1esZJavYVvVY5hywuPNK3tZ/pHitGKEymHGavNYUsVOh70SQpUFUwmUN//D92tUUPn0wCWOFee2DIJfzw4hNhNQu0+mvhu3PikZ6SlSFSt6f18nWoeAJkXMeZfADb+7jExsG61GbdOjT42aVmSWDC/DQXQEX25mNm9aqaMIRokT8kxhrL8hzmFCaIDkoS0f/oSg21ztECplhQjg8lORj6GZMmZqSJPqC1OyEFXD6QjmRIK5wWJN7VQE0Jrt8IH3HdjEKm5p2NdH6MzTLOMYlxkfglH9M8mS5dEgiwWKmnMMWD16PAW/y/ikBmWRBGiCY7nCwbczSwi5/zFXc30ChRE1meyg/i8VqrRyoM36xp3+toZil90Df0ZaR6KfL2B+SgfasqiYDZr56dnCD2/NFbOp8FnkuXWjLHAsEDs8xBgVaLVzk+nAs8PfI8QAkk32DDdsPOaqr6BwyfYQQGTPdSzPlTi2eUqMoSpoZWjiX/qjBlZaTAal9XZeDQk+sbZ3XCHJaSwCOG96X3UC9d/i89C9y8ePzL8A3IAIP+/DWbLP970YCizUkk94wZjeHtDvF/bbIHOYrfn8LA/W1frRVCj/fBAcTVUeQzPE/On+pkEh7bvCmF1Ff0dWkBcSmfrlhk3Ho52KE2spPvH1lZSY58BM1OIJOcK0aCNnpUlg4ew== sumeer@example.com
								// add this key in ssh key in github
git add .
git commit -m "changed in current file"
git push -u origin master