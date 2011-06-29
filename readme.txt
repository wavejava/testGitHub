mkdir testGitHub
  cd testGitHub
  git init
  touch README
  git add README
  git commit -m 'first commit'
  git remote add origin git@github.com:wavejava/testGitHub.git
  git push -u origin master
      
Existing Git Repo?
  cd existing_git_repo
  git remote add origin git@github.com:wavejava/testGitHub.git
  git push -u origin master

git clone  git@github.com:wavejava/testGitHub.git

git remote show origin 
git pull git

git tag v0.1 
git push origin v0.1
git push origin --tags

git checkout --track origin/br_NoCoreData

git merge br_NoCoreData2
git branch --merged
git branch -d br_NoCoreData2