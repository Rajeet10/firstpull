# Want to know me?
Join here and see the world my way!!
Its my first one
I created this repo for beginners to get in to their first open source contribution


## Hacktoberfest Practice Pull Requests

Repository for you to raise a Pull Request to **practice** open-source! 🎉

### Add your name to the alphabetical list and, optionally, a link to your GitHub account (in alphabetical order below your letter too)

### Option 1. Complete this process in Github (in your browser)

```mermaid
flowchart LR
    Fork[Fork the project]-->branch[Create a New Branch]
    branch-->Edit[Edit file]
    Edit-->commit[Commit the changes]
    commit -->|Finally|creatpr((Create a Pull Request))
    
 ```
1. Fork the project:

- Click the gray `Fork` button in the top right of this page. This creates _your_ copy of the project and saves it as a new repository in your github account

2. Create a New Branch:

- On your new repository's page, click the gray `main` button in the upper left to reveal a dropdown menu.
- Enter the name of your new branch in the text box. (Branch names usually make a reference to what is being changed. Example: `nameAdd`).
- Click on `Create branch <new branch name>` and this will automatically take you to your new branch. You can make edits on the main branch, but this may cause issues down the line. Best practice is to create a new branch for each separate issue you work on. That way your `main` branch remains in sync with Eddie's `main` branch.

3. Edit:

- On the top right of the Readme file, click on the pencil icon to edit the file by adding your name.
- After editing the Readme file, add a commit message and click on the green button saying "Commit Changes". Make sure you have selected the branch you have created.

4. Raise a Pull Request:

- Click `Pull Requests` (which is the third option at the top of this page after the options `Code` and `Issues`).
- Click the green `New Pull Request` button. This will prep the new pull request for you by autofilling the `base repository: base` with 'EddieGitHubCommunity: main' AND autofilling your `head repository: compare` with `your repository: main`
- Click on your head repository's `compare` dropdown, and switch branches from your 'main' branch to `<new branch name>`.
- Finally, click the green `Create Pull Request` button. Great job! You did it!

You can ask questions by raising an [issue](https://github.com/EddieHubCommunity/hacktoberfest-practice/issues/new).

### Option 2. Complete this process on your computer (locally)

- Fork the project:
  Click the gray `Fork` button in the top right of this page. This creates _your_ copy of the project and saves it as a new repository in your github account

- Click on the green `Code` button, then either the HTTPS or SSH option and, click the icon to copy the URL. Now you have a copy of the project. Thus, you can play around with it locally on your computer.

- Run the following commands into a terminal window (Command Prompt, Powershell, Terminal, Bash, ZSH). Do this to download the forked copy of this repository to your computer.

```bash
  git clone https://github.com/YOUR_GITHUB_USERNAME/hacktoberfest-practice.git
```

- Switch to the cloned folder. You can paste this command into the same terminal window.

```bash
  cd hacktoberfest-practice
```

- Make a new branch. Your username would make a good branch because it's unique.

```bash
  git checkout -b <name-of-new-branch>
```

- Open the `README.md` file

- **Add your name to the section that matches your Initial in [this list](https://github.com/EddieHubCommunity/hacktoberfest-practice#hacktoberfest-community), make sure that your name is in alphabetical order. Then save your changes.**

- For example
  `- [Full Name](https://github.com/your-username)`

- Stage your changes.

```bash
  git add README.md
```

or

```bash
  git add .
```

- Commit the changes.

```bash
  git commit -m "Add <your-github-username>"
```

- Check the status of your repository.

```bash
  git status
```

- The response should be like this:

```bash
On branch <name-of-your-branch>
nothing to commit, working tree clean
```

- Pushing your repository to GitHub.

```bash
  git push origin <name-of-your-branch>
```

or

```bash
  git branch -M main
  git push -u origin main
```

> **Warning**: If you get an error message like the one below, you probably forgot to fork the repository before cloning it. It is best to start over and fork the project repository first.

```bash
ERROR: Permission to EddieHubCommunity/hacktoberfest-practice.git denied to <your-github-username>.
fatal: Could not read from remote repository.
Please make sure you have the correct access rights and the repository exists.
```

- On the GitHub website, navigate to your forked repo - on the top of the files section, you'll notice a new section containing a `Compare & Pull Request` button!

- Click on that button, this will load a new page, comparing the local branch in your forked repository against the main branch in the EddieHub Hacktoberfest repository. Accept the default values in the dropdown boxes and click the green `Create Pull Request` button. After creating the PR (Pull Request), our GitHub Actions workflow will add a welcome message to your PR.
  Note: A pull request allows us to merge your changes with the original project repo.

- Your pull request will be reviewed and then eventually merged.

Hurray! You successfully have made your first contribution! 🎉

---
