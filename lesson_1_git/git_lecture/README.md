# Unit 0 - Lesson 1: Introduction to git and GitHub

## Objectives
* Understand Git as a tool for version control.
* Develop a sound mental model for the Git/GitHub workflow.
* Understand GitHub as a tool for collaboration and as remote host of git repositories.
* Understand GitHub as a social media platform for career development.
* Understand the difference between git and GitHub
* Create your GitHub profile
* Initialize a Git repository from the command line
* Create a remote GitHub repository
* Stage and commit changes from the command line.
* Push commits to a remote repository.
* Create a pull request.

## Vocabulary
* Git
* GitHub
* version control system (VCS)
* repository
* commit
* push
* pull request
* fork
* clone
* remote
* local
* mental model

## The Why
* Git and GitHub may be the most ubiquitous tools in all of software engineering and web development.
* Git is a **version control system** tracking changes in computer files and coordinating work on those files among multiple people.
* Git is primarily used for source code management in software development, but it can be used to keep track of changes in any set of files.
* GitHub is a **remote** hosting service for Git repositories. In addition to the core features of Git, GitHub provides a suite of tools to facilitate collaboration, such as bug tracking, task management, and feature requests.
* GitHub is one of many remote VCS hosting platforms, but with nearly 40 million users, it is the largest in the world.
* GitHub also has many features typical of a social network (username, followers, groups, public profile, etc), thus it has also become an important platform for personal branding and career development.

## Lecture: Developing a Mental Model
*  Mental models are the stories, analogies, and visual representations that we use to explain complex or abstract phenomena in the real world.
* Git/GitHub is hella confusing. Its a complex distributed system written in C. A solid mental model of the system will allow us to use the system effectively, even if we don't understand its intracies or implementation details.

We are all familiar with working in Microsoft Word. Let's use this as the basis for our analogy. Story time...

* Imagine you worked all night on a 15 page paper. You saved it. Then you fell asleep. Your little brother came in and deleted your paper and saved it. You're screwed.
* Imagine you worked all night on a short essay. Just as you were getting ready to submit you thought, "this isn't good enough." You scrapped the entire second half of the essay and took the paper in a different direction. When you finally submitted, your teacher said, "I love the first half but I like the original idea for the ending that you told me about in your outline." You think, "Ugh. I saved over that original copy. I have to write it all over again. I'm screwed."
* What if... hear me out... what if there was a way that you could take a _snapshot_ of your file each time you pressed 'Save'. That way, you could go back to previous _versions_ of your work if something ever happened.
* Well that's exactly why Git was created by Linus Torvald and the Linux development community in 2005!
* So let's assume that you were a baller and used Git for version control. You were going home to revert back to your previous version so that you can turn it back in to you teacher. When you get home, you find out that your brother has set your laptop on fire.
* Don't you wish you had a place where you could _host_, or store your repositories so that they aren't gone forever when your computer combusts into flames? And wouldn't it be great if it lived in the cloud so that you could access them from any device with an internet connection?
* Well, that's excatly why GitHub was created in 2008!

Let's continue with our Microsoft Word analogy.
* In Git, our project folders are called **_repositories_**.
* The essay folder that is saved on your computer is called a **local repository**.
* Any time you make a significant change to your local repository, you **stage** them and **commit** them. This is like saving your document with one key difference: 
  * In Microsoft Word, when you press 'Save', you are writing over the previous copy and saving the new copy in its place. 
  * In Git, when you `commit`, you are taking a "snapshot" of the current state of your repository and saving that snapshot. When you `commit` multiple times, you are saving multiple snapshots, essentially creating a living history of your repository.
* Before long, you want to back your essay up in the cloud. So you create a Google Drive folder with the same name. You can access Google Drive from anywhere so you know your essay will be safe. 
* Likewise, we can log on to GitHub.com and create a repository with the same name as our local repository. We call this a **remote repository**.
* When we **push** to this repository, we are sending our local changes to our remote repository. Now our code lives in two places: on our laptop and on the internet!

To extend the analogy...
* A classmate wants to use your essay for inspiration (don't worry they aren't cheating :wink:)
* Because you decided to leave your GitHub repo public, they can create a **fork** of your project. This fork, shares the same history as your project but your friend is now welcome to give it a new future.
* The **clone** the project to their own local repo so that they can work on it on their laptop.
* When they are done making edits, they commit their changes and push them up to their own fork of your essay repo.
* They feel so good about these changes that they think you might want to incorporate them into your own essay. They do this by opening a **pull request**. This is essentially a message to the owner (or **maintainer**) of the original repository saying, "Hey, boo 💁! I made some changes to your repo that are really cool. I think it makes the project so much better. Take a look and consider adding them in to main version so that the world can see as well!"

Now let's walk through this ourselves!

## Lesson Lab: Pull Request Walk-Thru
The purpose of this lab is to pull together everything that we have learned about git, GitHub, and the Command Line Interface. In your very first lab of the school year, I will ask you to...
  * Fork and clone a repo
  * Navigate your directores using the command line
  * Create your first Markdown file
  * Stage and commit changes
  * Push changes to your remote repo
  * **Make your first pull request**

In order to avoid frustration and confusion, follow this guide step-by-step and reach out to your community when you need help. Do not be afraid of "breaking" anything. You can always delete the directory and start all over again!

Okay, here we go!

1. Fork the [se-unit-0 repo](https://github.com/The-Marcy-Lab-School/se-unit-0/)
2. Clone the repository, creating a copy on your local environment.
3. In your local environment, navigate to your newly added `lesson_1_git/git_lecture/git_lab` directory.
4. Inside of the `git_lab/` directory, create a new Markdown fil. Use the following _naming convention_: `FIRSTNAME_LASTNAME_blog0.md`
5. Open the newly created Markdown file and make a change to the file. If you want, you can try to use Markdown syntax for headings, lists, bold, italics, etc. When you are done, save and close the file.
6. Stage your changes using `git add [filename]`
7. Commit your changes using `git commit -m "[Enter commit message here]"`
8. Push your changes back up to the remote copy of _your fork_. `git push origin master`
9. Log back on to GitHub.com.
10. Navigate back to your fork of the `se-unit-0` repository. 
11. Open a **pull request**. ![pull request photo](./pull_request.png) 
    ...then click ![pull request photo 2](./pull_request2.png)
    ...and lastly ![pull request photo 3](./pull_request3.png)
12. And just like that... you're done! You've made your first pull request!
