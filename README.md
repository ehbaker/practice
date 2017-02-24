#Place to practice the collaborative coding workflow

### Note: this is a workflow where one person (me, Emily) is the owner of a repository.
#### Workflow is slightly different if multiple people are _collaborators_ on a project (i.e. have write permissions)

###### If you're working inside the USGS network, you'll need to complete an additional step to work inside the firewall. Directions are [here](https://docs.google.com/a/doi.gov/document/d/18M6IHL_dfdypAHX8gUTr6LCsNRQA82rMdYfrEeBk6tg/edit?usp=sharing). Change this before proceding.

To change a document here, do the following:
+ Click on **'fork'** in the upper right habd of this page, to create YOUR personal branch of this repository. Create it under your username, as prompted.
+ This should create a copy of this repository on *your* github page - under yourusername/practice (will no longer say ehbaker/practice at top of page).
+ Nice work! You have a personal copy of this repository... online. But we want to get it onto your personal machine.
+ To make a local copy, you will **clone** the repository.
+ Open Git Bash on your machine (if you don't have it yet, [download](https://git-for-windows.github.io/)).
+ Use `cd` (change directory) and tab-completion in this command line interface to move to the folder where you want to keep your local copy of this GUI.
  + If you want to put it on your desktop, navigate to your desktop (a folder called mbGUI will be created during clone).
  + The text in yellow gives your location; also typing `pwd` in the prompt will print your current location.
  + `..` means 'go up a directory'; from _c/Users/yourusername_, type `cd Desktop` to go to the desktop.
+ Back on your github page (**yourusername/practice**), click the green 'Clone or Download' button. Copy the address of the git repository shown there, something like https://github.com/yourusername/practice.git
+ Clone the directory with Git Bash by entering `git clone https://github.com/yourusername/practice.git` (with copied git address)
+ A new folder will appear titled **practice** - this has all the files in this repository.

### Yay! Now you can use and edit the files on your local machine!! Woop!!

### To push changes back up to github:
+ Make changes. Since these are text files, notepad, notepad ++, Subline text would all work to edit. Save and close file.
+ Commit the changes you've made to the git tracking on your local machine: `git commit filenameOfFileYouChanged -m " short message about the changes you've made"
  * The -m "message" flag is important; Git will not accept your commit without it. If you forget to enter, the default text editor that ships with Git Bash is Vims... an old-school text editor which is hard to escape. If you end up here, quit by hitting Esc, then :, then q! . Phew! In the future, don't forget the -m "msg".
+ Push the changes you've made up to YOUR version of this project ONLINE: `git push origin master`
  * If you go to https://github.com/yourusername/practice.git, you'll see the new changes you've made (may need to refresh page).
  
### On Github, request that the repository owner (me, Emily) incorporate your changes into the master document
* Go to your github page, and hit the **"New Pull Request"** button (mid/upper left).
* Hit green **"Create Pull Request"** button on next page (you can see your proposed changes highlighted below).
* You will now see a message that "This branch has no conflicts with the base branch. Only those with write access to this repository can merge pull requests.". The repository owner (me) has recieved a notification that you're requesting a change, and can now review and either accept or reject.

# Feel free to practice this process here, before going on to work with more difficult projects!
