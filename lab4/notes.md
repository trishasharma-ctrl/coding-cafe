1. --global means that the entered Git name and email apply to all repositories for the user account. Without --global, the settings would only be applicable to the current repository rather than the whole account.

2. .git appeared in ls -a but not in ls because it is a hidden file. It contains Git's internal repository data: HEAD  config  description  hooks  info  objects  refs

3. Git offers to track 2 files: README.md and week02/. There were no outputs that did not look like anything I did not write

4. In my original output, there was no .venv/ so nothing disappeared. After creating .gitignore, Git continues to ignore .venv/ and other generated files listed in .gitignore

5. .gitignore should be committed as it records the rules for ignoring for the particular repository so that everyone working on the repository uses the same rules. 

6. README.md moved from Untracked Files to Changes to be committed. It moved from the working directory to the staging area, meaning it is now prepared for the next commit command.

7. Git created the commit "Lab work so far" and reported 8 files changed, with 2470 insertions. It also listed the files that were created in the commit

8. First 7 characters: e5c5c12. They are the short/abbreviated commit ID, used to uniquely identify and refer to a particular commit without having to type the full commit hash 
