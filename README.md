# RstudiolinkedwithGithub
A repository that will be linked with RStudio
After installing RStudio and Gib set on your computer in a GitHub account, It's time to link them together to maximize the benifts of using RStudio in your version control piopelines. 
**
To link RStudio in Git
**
If you want RStudio to help with your Git and GitHub work, it must be able to find the Git executable ("git.exe").
RStudio can only act as a GUI front-end for Git if Git has been successfully installed AND RStudio can find it.

In RStudio, go to "Toosl" tab, the go to "Global Options", then click on Git/SVN. 

![image](https://user-images.githubusercontent.com/59471339/113384718-3e656f80-93b9-11eb-9522-4e9f15b2fe41.png)

Sometimes the default path to the Git executable is not correct. 
Make sure file "git.exe" (git executable file). resides in the directory that RStudio has specified. Check it by going to drive C and find Git executable file. Next go to RStudio, click on "Tools" tab, and go to "Global options", click on Git/SVN and check Git executable file directory. Make sure, it's correct. 

![image](https://user-images.githubusercontent.com/59471339/113384675-25f55500-93b9-11eb-80a1-fffcae02c7a5.png)

Subversion (SVN) directory
SVN has the home directory listed when you are going to connect two softwares for the first time through Git.

##Linking RStudio and GitHub
In that same RStudio option window, click “Create RSA Key” and when this completes, click “Close.”

Following this, in that same window again, click “View public key” and copy the string of numbers and letters. Close this window.

![image](https://user-images.githubusercontent.com/59471339/113386739-7373c100-93bd-11eb-8009-a9bfa29766cf.png)

Generate an RSA key and copy the public key to your clipboard

You have now created a key that is specific to you which we will provide to GitHub, so that it knows who you are when you commit a change from within RStudio.

To do so, go to github.com/, log-in if you are not already, and go to your account settings. There, go to “SSH and GPG keys” and click “New SSH key”. Paste in the public key you have copied from RStudio into the Key box and give it a Title related to RStudio. Confirm the addition of the key with your GitHub password.

![image](https://user-images.githubusercontent.com/59471339/113386789-8dad9f00-93bd-11eb-81a7-ef624f600847.png)



Location of “SSH and GPG keys” on your profile settings


![image](https://user-images.githubusercontent.com/59471339/113386797-93a38000-93bd-11eb-8bb4-af96a18a7762.png)


Telling GitHub the public SSH key generated in RStudio

GitHub and RStudio are now linked. From here, we can create a repository on GitHub and link to RStudio.




