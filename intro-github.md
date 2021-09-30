# Introduction to GitHub

Before we get started, let’s clarify some terms:

[Git](https://git-scm.com/) is a popular free, distributed version control system–i.e. a piece of software used to track the history of changes in a folder of files. Git can be used on your personal computer, or by online services to track the development of a project, such as…

[GitHub](https://github.com/), a popular web platform for hosting Git repositories–i.e. a place to store and sync your project files online. Think of it as Google Drive for code with super robust “track changes” baked in. Built around the powerful version control of Git, it provides a handy web interface for managing, editing, and collaborating on repositories.

## Create a GitHub account

1. Go to <https://github.com>
2. Click the "Sign up" button
3. Enter your email and create a username and password to complete the sign up process

## Copy a GitHub Repository

1. Make sure you're logged in to your account on [GitHub](https://github.com)
2. Scroll to the top of the [foundations-0-github](https://github.com/learn-static/foundations-0-github) repository and click the green "Use This Template" button (appears on the right side above the code area)
4. This brings you to a "Create a new repository" form. Follow these steps:
    1. In the **Repository name** text box, give your repository the name `github-foundations`. If you'd like to create your own name for the repository, be sure to use a lowercase name without spaces or odd characters. Dashes (`-`) or underscores (`_`) are okay.
    2. In the **Description** text box, add `A place to learn GitHub basics`.
    3. Select the option for "**Public**" repository.
    4. Leave the "Include all branches" option **Unchecked**!
    5. Click on the green button "**Create repository from template**". This will take you to your new repository.

!["Create a new repository"](https://github.com/learn-static/foundations-github/blob/main/images/new-repo.png)

## Edit README file

Explore your new repository.
It contains: 
- a folder of images
- a README file
- a "intro-github" file with instructions for this lesson

![GitHub repository files](https://github.com/learn-static/foundations-github/blob/main/images/repo.png)

1. Click on the README.md file:

![Open the README file](https://github.com/learn-static/foundations-github/blob/main/images/open-file.png)

The README file is a place to describe your repository.
By default, GitHub displays the README on the repository home page, so it is often the first place visitors will look for information about your project.

2. Click on the pencil button in the top right corner of the README file. 

![Click the pencil button to edit a file](https://github.com/learn-static/foundations-github/blob/main/images/readme-pencil.png)

You are now in GitHub's editing mode.

The first line at the top of the template file will look like this:

```
# foundations-0-github

```

2. Delete this line of text and instead type `# My Project`.
3. Proceed to the following section to learn how to save or "commit" your changes.

## Make a Commit

When you make a commit, Git takes a snapshot of the changes you made and permanently stores it in your repository's history.
Your "commit message" is a short description of what the changes do or why you made them--this is your note to the future to help everyone understand the code and history.

You can view recent commits from your repository's homepage: commit messages and their timestamps are located to the right of the repository files:

![GitHub file history](https://github.com/learn-static/foundations-github/blob/main/images/commit1.png)

1. To commit the changes you just made to your README file, scroll to the bottom of the page where you made your README edits. You'll see a box titled "Commit changes."
2. In the text box directly underneath the "Commit changes" title, type `update project title`, or a brief message of your choosing that indicates what changes you made to this file.

![Commit Changes button](https://github.com/learn-static/foundations-github/blob/main/images/commit2.png)

3. Skip the option to add an extended description to the commit, and keep the box checked next to "Commit directly to the main branch".
4. Click on the green "Commit changes" button. This will take you back to the base of your repository.
5. Scroll down to the bottom of your repository to view the new title you added to the README file.

## View the Changes

Let's take a closer look at the changes you've made to the README file:

1. On your repository's homepage, locate the README.md file. To the right of the file, you should see the commit message you just made:

![Click on your commit message](https://github.com/learn-static/foundations-github/blob/main/images/commit-message.png)

2. Click on the commit message.

You should now see two versions of your README file, displayed side by side.
You are viewing the difference between the original version of your repository's README file, and the new version that you just created by editing it. 

![View your changes](https://github.com/learn-static/foundations-github/blob/main/images/diff.png)

3. Navigate back to your repository's homepage.

## Add a New File to the Repository

1. On your repository's homepage, locate and click the "Add file" button, situated to the right above your repository's files. When this button is clicked, a drop down menu will appear with the options "Create new file" and "Upload files."
2. Select "Create new file."

![Add a file to the repository](https://github.com/learn-static/foundations-github/blob/main/images/add-file.png)

3. An option to name your file will appear toward the top of your screen. Give your file the name: `new-file.txt`

![Name the new file](https://github.com/learn-static/foundations-github/blob/main/images/name-file.png)

4. Add the following sentence to your text file:
```
This is a new file in my GitHub repository.

```

5. Commit your new file to your repository by adding a commit message (just as you did in the "Make a Commit" section above) and pressing the green "Commit new file" button.

## Check Out the Repository's History

1. On your repository's homepage, locate the commit count for your repository, situated underneath the green "Code" button and to the right of a clock icon: 

![Click on the commit count](https://github.com/learn-static/foundations-github/blob/main/images/commit-count.png)

2. Click on the commit count.

You are now viewing your repository's history: in other words, all the commits that have ever been made to it.

![View your repository's history](https://github.com/learn-static/foundations-github/blob/main/images/history.png)

3. Click on any of the commit messages to view the changes that were made as part of that commit.

## Make an Issue

1. In the navigation menu below your repository's name, locate and click on the "Issues" button.

![Click on "Issues"](https://github.com/learn-static/foundations-github/blob/main/images/issues.png)

2. Click the green "New issue" button, located on the right side of the screen.

3. 

## Optional: Add a GitHub Collaborator

Most digital projects are collaborative, so you will probably want to add your collaborators to your GitHub project repository.

1. On the repository home page, click "Settings" tab
2. On left side nav, click "Manage access"
3. Click the green "invite teams or people" button
4. Type in a GitHub user name to add. The search bar will show suggestions based on what you type, select the correct account to add.
5. Select their level of access to the repository. Generally if you want people to be able to edit code in the repository, give them "Write" access. Then click the green "Add" button.

Once added your collaborator will receive an email with the invitation to join your repository.
They will have to confirm the invitation before being added!