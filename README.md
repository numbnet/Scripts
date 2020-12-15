#create a new repository on the command line

echo "# Scripts" >> README.md
git switch NN
git init
git add README.md
git commit -m "first commit"

git branch -M numbnet
git remote add origin https://github.com/numbnet/Scripts.git
git push -u origin numbnet
#git push --set-upstream origin NN
                
# push an existing repository from the command line
git remote add origin https://github.com/numbnet/Scripts.git
git branch -M numbnet
git push -u origin numbnet