# A03
## **How to use Git and Github:**
1) Install Git as a Local Program from https://git-scm.com/downloads
2) Create a Github account on https://github.com/join
3) Connect Github with your IDE. In this case I will use Webstorm which is a jetbrains based IDE from https://www.jetbrains.com that can be used to edit css and html files. In Webstorm press Ctrl+Alt+S to view system preferences, then select Version control Git and enter the path to the git.exe file you downloaded in step 1
4) While still using Webstorm, go to system preferences again and select Appearance & Behavior|System Settings|Passwords, then select the location of the password file
5) Goto your github page then on the top right click the + sign and select "Create New Repository", name the repository what you want your project to be called. This will be like a file where all the project code and the history of all the changes made to the code will be stored
6) Open Webstorm and select "Check out from Version Control" on the right hand side, and select git
7) Then enter the url of your repository it should look like this "github.com/YourUserName/ProjectName"
8) You will then be prompted for your Github username and email. If this is your first time useing Github on your PC you will be prompted to log into your github account
9) You should now see a project open up with the title of the repository. You can now create and edit files within the repository file.
10) When you want to push the edited files to the online repository create a "Commit" using the green checkmark on the top right on the Webstorm window. Its recommended that you add a short description to your commit to make the repository easier to read.
11) After you create a commit you will still have to "Push" the commit to the online repository
12) You can use the shortcut on Webstorm which is Ctrl+Shift+K, or you can selec the "VCS" tab then the "Git" option then select "Push", which is a green arrow pointing up and to the right.
13) You are now finished creating a git repository, creating a commit, and pushing the commit to the onlin github repository!
## **Definitions:**

GIT: This is a version control system that is used to keep track of changes in source code by taking snapshots of committed code, and keeping track of these snapshots over time.

GITHUB: This is a website that uses cloud based storage to help developers manage their code using GIT

Repository: This is a feature of GITHUB that contains your projects files and the history of all changes made to those projects files.

Clone: This allows your to download an entire GIT repository onto your local machine

Commit: This is when a revision to a file is made in the repository, the commit also records who made the commit and when they made the commit. It is also reccommended that the person making a commit leaves a short description of the changes

Push: A push takes a commit made locally and sends it to the remote repository(usually GITHUB)

Pull: Pull allows you to get a edited file from the local machine of someone else using the repository and add those changes to your local repository.

Branch: A branch is like a "copy" of a repository. It allows you to make changes to the branch with the safety net of not actually affecting the live branch or the "master branch" until the branch is merged with the master branch

Merge: This command takes changes from 1 branch and applies to another branch. This is often done using a pull request

Merge Conflict: This occurs when people make different changes to the same line of the same file. All merge conflict must be fixed in order to merge a pull request

Fetch: This command gets the most recent changes of the online repository but it doesnt merge them with your local repository, it allow you to compare it to the code on your local repository 

Remote: This is something that can be hosted on a server, for example GITHUB hosts your code online on their server


### **Reference List**

Introduction to Github and Webstorm by Arther H Hendela, Ph.D. Senior University Lecturer, NJIT
