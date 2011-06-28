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
