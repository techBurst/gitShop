# gitShop
Workshop notes from April 13, 2015

git - distributed version control system
  invented by liz torvald (linux guy) in 2005
branching as a "parallel universe"
  git checkout <branch_name>
github - web based hosting service for projects using git version control system
  provides repositories, places to keep track of files using git
  provides both public and private repositories
creating repository: git init <repo_name>; cd to that directory, create file(s)
add files to repository:
  working - make the file
  stage the new/modified file to be committed
    git add <my_file>
  commit your staged content as a new "commit snapshot"
    git commit -m "<descriptive log message>"
clone is exact copy of master branch, changes allowed
fork is copy of master that needs permission to make changes
