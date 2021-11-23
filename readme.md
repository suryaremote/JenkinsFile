calhostsurya jenkinsproject]# git status
# On branch master
nothing to commit, working directory clean
[root@localhostsurya jenkinsproject]# git log
commit 4dd7fda97e8db96b359c19636ff57a4be6b708fa
Author: jay <surya29.v@gmail.com>
Date:   Tue Nov 23 19:23:28 2021 +0530

    Helloworld.html
[root@localhostsurya jenkinsproject]# ls
Helloworld.html
[root@localhostsurya jenkinsproject]# vim readme

  so need to config the user name

  added incorrect config , edited using " git config --global -e" command

  git add <file >
  git status

 git commit -m "Helloworld.html"

 git log --oneline (to get commit id in single line )

  git remote add origin https://github.com/suryaremote/JenkinsFile.git (added repo ref)

  git remote -v ( to get list )
  
  git push origin master
  
    
    we use maven as build tool 
    
    we create a package 
    
    sudo yum install maven
    

