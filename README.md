# GitHub Tutorial

_by Belinda Vargas_

---
## Git vs. GitHub
**_Git_**
 * Version control   
 * Takes snapshots of code 
 
**_Github_**  
 * It stores code into the "clouds" known as the website   
 * Github visually tracks changes  since the code is stored into the clouds   
 * Able to collaborate on a same project  
The difference between these two is that Git doesn't require Github, but Github does require Git 

---
## Initial Setup
### Signing up to github
![screenshot](https://cloud.githubusercontent.com/assets/15129114/19668093/3c494cf6-9a23-11e6-8d8d-211b0a0d6a8d.png)
* You must use an email and password 
* After making an account you will need check your email to verify with github
*Next you'll need a ssh key. This could be used only one time, it's very helpful 
* On github: go to settings  
![screenshot](https://cloud.githubusercontent.com/assets/15129114/19669263/eda93742-9a2b-11e6-8ff7-db2ab82e1a3b.png)
* click on SSH 
* after clicking on ssh key you'll see that there is a "key" needed  
  * you will need to go to c9 and get a key   
![screenshot](https://cloud.githubusercontent.com/assets/15129114/19669403/0fb7ef58-9a2d-11e6-9804-733185d656aa.png)
![screenshot](https://cloud.githubusercontent.com/assets/15129114/19668387/863abe92-9a25-11e6-8c70-e46f635bba80.png)
* copy and paste the key onto github
![screenshot](https://cloud.githubusercontent.com/assets/15129114/19671767/1ec54132-9a3f-11e6-9ddf-88b7b1e0404c.png)



---
## Repository Setup
### Making a first-repo    
*screenshot*  
On github you'll need to...
* Make a file called first-repo
  *mkdir makes a new directory  
* cd into first-repo 
  * always change directory to the new file 
* git init 
  * never initialize on workspace  
* touch README.md  
  * touch could be used within the directory 
* type something on the file! 
  * ex: "This is my first repo!!"  
* After you're done you will need to use git add
  *One of the important commands you'll need to use
* Afterwards git commit -m "message"
  * It is always important to add a message, this would be able to show what you have added/edited
* Git push
  * don't push unless you already made a repo on c9
 * There you go! you made your first repo :)  
On cloud9 you'll need to...
 *



---
## Workflow & Commands
### These lists of commands will be helpful on github 

*`git init`  
  * This command initializes git in directory which is now called a repository. This can only happen once at the beginning

*`mkdir`  
  * makes a file in the workspace  

*`cd`  
  * Allows to change directory    

*`git add file`  
  * adds file to the stage   
    
*`git commit -m "message"`  
  * takes a snapshot of the current files that are on the stage, the messag eshould also state what has been edited on the file    

*`git status`  
  * One helpful tool/command that shows current files which are commited   

*`git push`  
  * stores code into the cloud 

## Error Handling 
At times you will come across some errors, don't panick. There is a way you can solve the issue!
Sometimes we make mistakes, If you initialize in a wrong directory such as workspace. There is an easy solution
  * Use...    
Removing a repository is easy and simple!

`fork`  
  * Allows to collaborate with others on the same repository
  * You're able to approve or deny changes
`cloning`  
  * Makes a copy of a repository 