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

Your new repository contains a few files:

![GitHub repository files](https://github.com/learn-static/foundations-github/blob/main/images/repo2.png)

Below the list of filenames, the contents of a "README.md" file are displayed.
The README file is a place to describe your repository and its contents.
By default, GitHub displays the README on the repository home page, so it is often the first place visitors will look for information about your project.

Click on the pencil button in the top right corner of the README file. 

[screen shot]

You are now in GitHub's editing mode.

The first line at the top of the template file will look like this:

```
# foundations-github

```

Leaving the `#`, edit that line to be a title you choose instead.
For example: `# Example Project`.

Once you're happy with your project title, scroll to the bottom of the page, where you'll see a box titled "Commit changes."
When you make a commit, Git takes a snapshot of the changes you made and permanently stores it in your repository's history.
Every commit records a user name, email, and message along side the exact details of the changed files. 
Your "commit message" is a short description of what the changes do or why you made them--this is your note to the future to help everyone understand the code and history.

To commit the changes you just made to the README, record a brief message indicating what changes you made in the box directly underneath the "Commit changes" title.

[screen shot commit message]

For example: `update project title`

Skip the option to add an extended description to the commit, and keep the box checked next to "Commit directly to the main branch".

Click on the green "Commit changes" button.
This will take you back to the base of your repository.
Scroll down to the bottom of your repository to view the new title you added to the README file.

## Add a New File

## Check Out the Repository's History

## Turn on GitHub Pages

1. On your project repository's home page, click the "Settings" button (appears on the right along the tabs above the code area).
2. On "Settings" page: click "Pages" in the left side menu.
3. On the "Pages" page: in the "Source" section, change the dropdown button from "none" to "main" (leave the folder option as "/root"), then click the "Save" button. 

Once saved, the page will refresh with an alert providing the URL where your site will appear. 
It will take a few minutes for the build to happen and your site to go live--so wait it out! 

Meanwhile, you'll want to copy the URL to display on your home page:

1. Copy the provided URL.
2. Go to repository's home page.
3. On right side of the code area, look for "About" section and click on the cog icon to edit. 
4. In the "About" box, paste in your URL, then click "Save". This will make it easy to access the site in the future!

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