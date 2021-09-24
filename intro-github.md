# Introduction to GitHub

## Create a GitHub account

1. Go to <https://github.com>
2. Click the "Sign up" button
3. Enter your email and create a username and password to complete the sign up process

## Create a GitHub Repository
1. Make sure you're logged in to your account on [GitHub](https://github.com)
2. Scroll to the top of the [foundations-github](https://github.com/learn-static/foundations-github/) repository and click the green "Use This Template" button (appears on the right side above the code area)
4. This brings you to a "Create a new repository" form. Follow these steps:
    1. **Repository name**: Use a lowercase name without spaces or odd characters.
    2. Choose "Public" repository.
    3. Leave the "Include all branches" option **Unchecked**! (you do not want all branches, only the main branch)
    4. Click on the green button "**Create repository from template**". This will take you to your new repository.

## Edit README file

Below the contents of your repository, a "README.md" file is displayed.
The README file is a place to describe your repository.
By default, GitHub displays the README on the repository home page, so it is often the first place visitors will look for information about your project.

1. Click on the pencil button in the top right corner of the README file. 

![GitHub repository files](https://github.com/learn-static/foundations-github/blob/main/images/readme-pencil.png)

You are now in GitHub's editing mode.

The first line at the top of the template file will look like this:

```
# foundations-github

```

2. Leaving the `#`, edit that line to be a title you choose instead. For example: `# My Project`.
3. Once you're happy with your project title, proceed to the following section to learn how to save or "commit" your changes.

## Make a Commit
When you make a commit, Git takes a snapshot of the changes you made and permanently stores it in your repository's history.
Every commit records a user name, email, and message along side the exact details of the changed files:

![GitHub repository files](https://github.com/learn-static/foundations-github/blob/main/images/commit1.png)

Your "commit message" is a short description of what the changes do or why you made them--this is your note to the future to help everyone understand the code and history.

1. To commit the changes you just made to the README, scroll to the bottom of the page, where you'll see a box titled "Commit changes."
2. In the box directly underneath the "Commit changes" title, record a brief message indicating what changes you made. For example: `update project title`.

![GitHub repository files](https://github.com/learn-static/foundations-github/blob/main/images/commit2.png)

3. Skip the option to add an extended description to the commit, and keep the box checked next to "Commit directly to the main branch".
4. Click on the green "Commit changes" button. This will take you back to the base of your repository.
5. Scroll down to the bottom of your repository to view the new title you added to the README file.

## Add a New File

1. Locate and click the "Add file" button, situated to the right above your code. When this button is clicked, a drop down menu will appear with the options "Create new file" and "Upload files."
2. Select "Create new file."

![GitHub repository files](https://github.com/learn-static/foundations-github/blob/main/images/add-file.png)

3. An option to name your file will appear toward the top of your screen. Give your file the name: `new-file.txt`

![GitHub repository files](https://github.com/learn-static/foundations-github/blob/main/images/name-file.png)

4. Add the following sentence to your text file:
```
This is a new file in my GitHub repository.

```

5. Commit your new file to your repository by adding a commit message (just as you did in the "Make a Commit" section above) and pressing the green "Commit new file" button.

## Check Out the Repository's History



## Make an Issue

## Optional: Add a GitHub Collaborator

Most digital projects are collaborative, so you will probably want to add your collaborators to your GitHub project repository.

1. On the repository home page, click "Settings" tab
2. On left side nav, click "Manage access"
3. Click the green "invite teams or people" button
4. Type in a GitHub user name to add. The search bar will show suggestions based on what you type, select the correct account to add.
5. Select their level of access to the repository. Generally if you want people to be able to edit code in the repository, give them "Write" access. Then click the green "Add" button.

Once added your collaborator will receive an email with the invitation to join your repository.
They will have to confirm the invitation before being added!