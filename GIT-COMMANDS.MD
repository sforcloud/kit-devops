 yum install git -y
 
 git config --global user.name shiva
 
 git config --global user.email sforcloud@gmail.com
 
 git config --list
 
 git config color.ui true

 git config ui.color true
 
 mkdir project-test
  
 cd project-test/
 
 git status
 
 git init
 
 git status
 
 git config --global color.ui auto
 
 ls
 
 touch README.MD
 
 vim README.MD
 
 vi README.MD
 
 ls
 
 git status
 
 git add README.MD
 
 git status
 
 touch index.html
 
 vi index.html
 
 git status
 
 git add index.html
 
 git status
 
 git commit -m "initial commit "
 
 ls
 
 git status
 
 git remote
 
 git remote -v
 
 git remote add origin https://github.com/sforcloud/kit-devops.git
 
 git remote -v
 
 git push origin master
 
 git branch
 
 git branch kit-devops-10172018
 
 git branch
 
 git checkout kit-devops-10172018
 
 git branch
 
 ls
 
 vim index.html vim
 
 vi index.html
 
 git status
 
 git commit -m "modified index file in branch"
 
 git commit -a -m "modified index file in branch"
 
 git push origin kit-devops-10172019
 
 git branch
 
 git push origin kit-devops-10172018
