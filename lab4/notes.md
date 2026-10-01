1. `--global` means the Git configuration applies to your whole user account on the computer, not just one repository. If you leave it out, the setting applies only to the current repository.

2. `ls -a` shows hidden files and folders, including the `.git` folder. The `.git` folder stores the repository’s Git history, configuration, branches, and tracking information.

3. `git status` shows which files are untracked, so you can see what Git is not tracking yet. The actual project code can be identified by its filenames or folders, while folders like `.venv` are environment files.

4. After creating `.gitignore`, files and folders listed inside it stop appearing in `git status`. For example, `.venv/` disappears because Git is now told to ignore it.

5. `.gitignore` should be committed because it is part of the project configuration. It helps everyone working on the repository ignore the same unnecessary files.

6. `README.md` first appears as untracked, then moves to “changes to be committed” after `git add`. After `git commit`, it becomes part of the repository history and no longer appears as an uncommitted change.

7. `git commit` creates a new commit and shows information such as the commit hash and commit message. It also shows how many files were changed and how many lines were added or removed.

8. The first seven characters are called the short or abbreviated commit hash. They are used as a shorter unique identifier for a commit instead of using the full hash.

9. The four steps are edit, check status, stage, and commit. This cycle is repeated whenever changes are made to the project.

10. `README.md` gives an overview of the project and explains what the repository contains. It is usually placed in the main or root folder so GitHub can display it automatically.

11. `gh auth login` securely connects the GitHub CLI to your GitHub account. After login, GitHub can authenticate future commands without asking for your password every time.

12. GitHub displays the `README.md` file on the repository’s main page. It does this because README files are meant to introduce and explain the project.

13. `git push` does not change or delete your local commit history. It sends your local commits to the remote GitHub repository.

14. A private repository exists on GitHub but can only be accessed by you and people you allow. No repository on GitHub means the project only exists locally on your computer and has not been uploaded.
