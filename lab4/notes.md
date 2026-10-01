1) --gloabal means the git configuration applies to your whole user sccount on the computer, not just one repository. If you leave it out, the setting applies only to the current repository. If you leave it out, the setting applies only to the current repository.
2) ls -a shows hidden files and folders, including the .git folder. The .git folder stores the repository’s Git history, configuration, branches, and tracking information.
3) git status shows which files are untracked, so you can estimate how many files Git is not tracking yet. The actual project code is usually easy to identify because it appears by its filename or folder, while things like .venv are environment files.
4) After creating .gitignore, files and folders listed inside it stop appearing in git status. For example, .venv/ disappears because Git is now told to ignore it.
5) .gitignore should be committed because it is part of the project’s configuration. It helps everyone working on the repository ignore the same unnecessary files.
6) README.md first appears as untracked, then moves to “changes to be committed” after git add. After git commit, it becomes part of the repository history and no longer appears as an uncommitted change.
7) git commit creates a new commit and usually shows a commit ID, commit message, and summary of changed files. The output also tells you how many files were changed and how many lines were added or removed.
8) The first seven characters are called the short or abbreviated commit hash. They are used as a shorter unique identifier for a commit instead of typing the full hash.

