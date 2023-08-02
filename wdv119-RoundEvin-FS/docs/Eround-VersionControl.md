# Instructions

Update this document where indicated [look for the brackets!]. Replace text inside the brackets with your own information. For example: Course Name should be the name of this course, and not the generic words "Course Name".

<br>

## WDV119

- **Evin Round**
- **05-08-23**

This paper addresses some of the topic matter covered in research and activity this week. Be sure to include reference links below to the research and information you used to complete this assignment.

## Topic: Terminal

Professional developers use Terminal daily. It's essential to understand some fundamental commands to use the application.

Update the information below to demonstrate your knowledge on this topic.

**1. Using Terminal, there are essential commands to know.**

List the correct Terminal commands to do the actions listed below. Replace **CMD** with the correct command sequence. You can keep or enhance the brief description.

**The last bullet provides an example**.

-  **Ctrl + L**: Clear the Screen
-  **pwd**: Print the "Working Directory"
-  **ls**: List files and folders
-  **ls -la**: List files and folders, including invisible files
-  **ls -l**: List all files and folders, in human readable form
-  **cd[ ]**: Change directory
-  **cd/**: Change directory, go to root directory
-  **cd~**: Change directory and go to user home directory
-  **cd..**: Change directory, go up one folder level
-  **cd../..**: Change directory, go up two folder levels
-  **cd**: Change directory to my desktop!

**2. Using Terminal...**

**Folder Drop:** Try typing "cd" followed by a space, and then drag a folder into terminal and press return. Test this out and describe your results below.

It changes the working directory to the folder specified.

## Topic: Version Control & Git

Version control, also known as revision control, records changes to a file or set of files over time so that you can recall specific versions later. In this class, we are learning Git. Update the information below where indicated.

**1. There are three types of version control.**

The three types of version control are local, centralized, and distributed.  Local version control is when files are located on a single machiene. Centralized version control is when the files are located on a server but multiple machines can access the files. The master copy is kept on the server alone and the copies can only be applied one at a time. Distrubuted version control is when all machienes and the server have access to the same files real time and also keep multiple versions of every save instance.

**2. Using Terminal, there are also essential Git commands to know.**

List the correct Git commands to do the actions listed below in Terminal. Replace CMD with the correct command and keep or enhance the brief description.

- **git clone [ ]**: Clone a repository
- **git config --global user.name "[ ]"**: Set-up a global user name
- **git config --global user.email "[ ]"** Set-up a global email address (to match my GitHub account email)
- **git status**: Shows the current state of your directory and staging area
- **git add [ ]** Add modified files to the next commit
- **git commit -m "[ ]"** Make a commit with a new message
- **git log**: Show my commit history
- **git help**: Show Git's help screen

**3. Connecting to GitHub using Terminal.**
HTTPS is the the correct way to connect to GitHub in this course. Describe how you connect to GitHub from Terminal using this protocol. What steps do you take?

Cloning the repo from github  via the url under the code button is all you need. Enter **git clone** and past the url and then return.

**4. Using .gitignore and Why it's Important**  
Most repositories contain a .gitignore file.

- What is the purpose of this file?
  <br>
  It specifies file names you dont want git to make commit.

- What is the "**.DS_Store**" file and why would you want to ignore it?
  <br>
  It's an invisible file that MacOS creates every time you look in a folder with Finder. It contains information and metadata about files around it that could potentially open you up for hacking or other malicious activities.

- What other file or folder would you want to add to a .gitignore file and why?
  <br>
  We would want to ignore OS files, app files, language and framework files, package manager files, and credential files. None of these files are required for your project to be shared and no other teammember needs it for use. Anything outside of that is just bloat or potential for security breach.

<br>

# Reference Links

Replace the example references below with your own links and recommended resources. It is acceptable to provide multiple links for a single topic and to use material provided to you in this class. You are encouraged to link to your own independent research as well.

[ I think each of these are very useful in their own way and neither is less important than the other. They're all needed and required.]

**Terminal Commands**  
[MakeUseOf](https://www.makeuseof.com/tag/mac-terminal-commands-cheat-sheet/)

**Three Types of Version Control**  
[FullSail](https://online.fullsail.edu/class_sections/140796/modules/586762/activities/3416725)

**Git Commands**  
[Github](https://education.github.com/git-cheat-sheet-education.pdf)

**Connecting to GitHub using Terminal**  
[CodeAcademy](https://www.codecademy.com/article/f1-u3-git-setup)

**Using .gitignore and Why it's Important**  
[Zellwk](https://zellwk.com/blog/gitignore/)
