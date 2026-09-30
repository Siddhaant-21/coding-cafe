Solutions to lab 4 (Git and Github)

Ans1) --global means that now the name and email I provided will be used for commits in all Git repositories for me (wherever I am a user). It writes to the global file instead to just my specific repository. Leaving it out only means that any settings or changes saved only for my repository.

Ans2) ls -a showed an additional .git file that ls did not. This file stores the commit history, and other metadata/information.

Ans3) git is offering to track 2 files and there are 2 files in the 'untracked' section. Everything seems to be the same as the files I myself created.

Ans4) Since I did not have any .venv or other hidden files in git status beforehand, nothing essentially disappeared, but it would've if that were the case. I do see 
.gitignore in the untracked files under git status now though.

Ans5) Yes, it should be committed since it includes all the files that git should ignore and leave out of the repository, so its helpful to track that as well.

Ans6) The README.md file moved from the "Untracked" to the "Changes to be committed" heading. From the 3-stage model perspective, it moved from the working directory to the staging area, and is now ready to be committed.

Ans7) After the commit, git printed;

[master (root-commit) c832065] Lab work so far
 5 files changed, 245 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 lab04/lab04notes.md
 create mode 100644 week02/lab01-log.txt
 create mode 100644 week02/notes.md

 it showed that 5 files were changed, and named all the files.

 Ans8)c832065 were the first 7 characters of my commit, and they are called the Short Commit Hash (SHA). They allow identification of the specific commit without having to to type the longer version of the commit hash.

 Ans9) The 4 steps were: Create file --> check status using git status --> use git add to push files to staging area --> use git commit to push these files to the repository.

 Ans 10) This file gets a special name as README is specially recognised by git and github, unlike notes.md which just a regular markdown file.

 Ans 11) gh auth login authenticates my github account. Because GitHub has already authenticated my computer, Git can use those credentials when you commit instead of asking for password each time.

 Ans 12) The repository page shows the file we remotely connected and pushed as an existing repository on the command line, along with the README file data as README is automatically recognized by the repository and appears on the github homepage.

 Ans13) No pushing did not change the local history in any way, as there was no new commit made.

 Ans14) A private repository existing means anyone with access can view and make changes to it, while it not existing at all means that there is no repository whatsoever and there is no record or history of it online, and is available only locally on the computer.