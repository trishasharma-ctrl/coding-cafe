1. --global means that the entered Git name and email apply to all repositories for the user account. Without --global, the settings would only be applicable to the current repository rather than the whole account.

2. .git appeared in ls -a but not in ls because it is a hidden directory. It contains Git's internal repository data: HEAD  config  description  hooks  info  objects  refs

3. Git offers to track README.md and week02/. There were no outputs that did not look like anything I did not write

4. In my original output, there was no .venv/ so nothing disappeared. After creating .gitignore, Git continues to ignore .venv/ and other generated files listed in .gitignore

5. .gitignore should be committed as it records the rules for ignoring for the particular repository so that everyone working on the repository uses the same rules. 

6. README.md moved from Untracked Files to Changes to be committed. It moved from the working directory to the staging area, meaning it is now prepared for the next commit command.

7. Git created the commit "Lab work so far" and reported 8 files changed, with 2470 insertions. It also listed the files that were created in the commit

8. First 7 characters: e5c5c12. They are the short/abbreviated commit ID, used to uniquely identify and refer to a particular commit without having to type the full commit hash 

9. create a file, check its status, stage it, commit it.

10. README.md is given a special name and placed at the root of the repository because it introduces and explains the project. GitHub automatically displays the README.md on the repository's main page so that visitors can quickly understand what the repository contains.

11. gh auth login authenticated the GitHub account and saved authentication credentials for Git. This allows Git to authenticate future pushes without asking me to enter my GitHub authentication password each time

12. README.md is displayed as formatted content on the front page of my GitHub repository. GitHub automatically renders the repository's root README.md so visitors can immediately see information about the project.

13. No, pushing did not change my local commit history. The same three commits are still present; the push only copied the commits to GitHub and origin/main now points to the same latest commit.

14. A private repository exists on GitHub, but only I and people I give access to, such as the TAs, can view it. If the repository did not exist on GitHub at all, it would only be stored locally on my computer and nobody could access it through GitHub.

