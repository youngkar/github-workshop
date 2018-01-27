# GitHub Workshop

This repository contains all of the resources for my Intro to GitHub workshop


## Part 1: Why Git and GitHub?
- Powerpoint: [Why do we use Git?](WhyGit.pptx)

## Part 2: Set up Git and GitHub
*Talk to the people around you and do the next few parts together in teams of 3-4:*

- Download and install Git [here](https://git-scm.com/)
- Create a GitHub account


## Part 3: Fork and clone this repository
*Even though you can view this repository, you don't have permission to add content to it. In this part, one member of your team will create a copy of this repository that you can add content to. If you get stuck, check out [this article](https://help.github.com/articles/fork-a-repo/) or feel free to ask for help.*

- One member in your team: Fork this repository by clicking on the “Fork” button in the top right.

 *This step will create a copy of the repository under your account, which only you have permission to edit for now. Part 4 will show how to grant edit permission to your teammates.*
- Everyone in your team: Clone into the new repository by running the command:

  `git clone https://github.com/<teammate’s username>/github-workshop`

  *This step creates a local copy of the repository on your computer, which has the same content as the online, called "remote", version does.*


## Part 4: Add collaborators to a repository
*This part walks you through adding the other members of your team as collaborators on your repository.*

- Whoever who forked the repository: Click on the Settings tab of your repository, then the Collaborators sub-tab, and then add your teammates by username. New collaborators will need to accept your invitation by clicking a link sent to their email.


## Part 5: Make some changes!
*Everyone on your team now has a local repository set up. This folder on your computer mirrors the content of the remote repository. By adding some content to your local repository, you will be able to send it to the remote repository.*

- Everyone in your team: Add however much content you want to the four directories: *motivational_quotes*, *wallpaper*, *code*, and *batman*. There are some examples in each of them to get you started but feel free to add anything.


## Part 6: Push your content to the remote repository
*So you just added some pictures to your local repository but they aren't showing up in your remote yet. This is because Git is very careful about how it deals with content and it hasn't done anything with your pictures yet. You will need to tell it specifically what to do with your pictures.*

- Everyone in your team: Run the following commands in the following order to send your changes to the remote repository. When you run these commands, read what Git tells you in response because you will probably be able to understand it! If you want to get a clearer idea of what these commands do, check out [Git: The Simple Guide](http://rogerdudler.github.io/git-guide/) and scroll down a bit.

  1. `git pull` Checks whether your local repo is up-to-date with your remote repo, and makes it up-to-date if it is not.

  2. `git add <filename>` or `git add *` Tells Git that you would like to stage a particular modified file to be uploaded, or that you would like to stage all modified files to be uploaded.

  3. `git status` Asks Git to show you the status of your modified files (how many of them are staged vs. unstaged). This is an optional step.

  4. `git commit -m “<commit messsage>”` Takes all currently-staged files and creates a new snapshot in time of your repository that includes those files, called a commit.

  5. `git push` Tells git to upload all of your commits to your remote repository.

- Now refresh your browser and you should be able to see your new files!


## Part 7: Open a pull request
*Now that everyone has pushed their changes to the forked version of this repo, it’s time to merge all of your changes back into the original repository that you didn't have access to before.*

- One person in your team: On your forked repository page, click the “New pull request” button in the middle-left of the screen. Then click the green “Create pull request” button.
- Let me know that your team opened a pull request and I'll approve it.
- Refresh the original repository and see your changes there!


## That’s it!
In this workshop, you learned how to fork a repository, clone a local copy of your fork, add new content, push new content to a remote, and finally merge your changes back into the master repository. You know the basics of Git!

If you'd like, feel free to repeat parts 5-7 and open more pull requests. Otherwise check out some of the resources below to learn more about Git and GitHub:

- [GitHub's list of its favorite learning resources](https://help.github.com/articles/git-and-github-learning-resources/)
- [GitHub Guides](https://guides.github.com/) (Official articles with lots of pictures)
- [Git: The Simple Guide](http://rogerdudler.github.io/git-guide/)
- [Try Git Simulator](https://try.github.io/)
- [Pro Git E-Book](https://git-scm.com/book/en/v2)
- [Git Documentation](https://git-scm.com/docs)
- [Commit Logs From Last Night](http://www.commitlogsfromlastnight.com/)

Thanks for coming!
