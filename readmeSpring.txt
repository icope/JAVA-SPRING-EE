Read me spring 

git config --global user.name ="Babu"
git config --global user.email= "faridbabu@outlook.com"


---------------

git init JAVA/SPRING-EE    //Initialize SPRING-EE folder as guit 

cd JAVA/SPRING-EE   // chenge the directory to  that folder 

--------------------

git status // know the status of this directory
git add . // all file that are not comitted will commit
git add test.txt   // will commit the specific file named test.txt
git commit -m "Has been comitted" // commit the directory's files those has been added  -m "Message to add for log"
git log // show the history of commit 
shift+ZZ //To get out of log report to command mode

#-----Short cut------
git log --online // show all commit report in summary 
git commit -a -m "Message" // short cut commit  all modified file in the directory without add command
git status -s // it will show the name of modified files 

#-------Generating ssh key-----------

ssh-keygen -t rsa -C "faridbabu@outlook.com" // Here we are creating an rsa key
git init  // Initialize empty repository ( current directory)