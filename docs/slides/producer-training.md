<!-- .slide: data-state="title" -->

# Exercise Files with Github

By raybo ([@planetoftheweb](https://github.com/planetoftheweb))

---

<!-- .slide: data-state="title" class="bg-dark text-warning" -->

# Goal

Be comfortable delivering exercise files on Github<br>
(within the next year)<!-- .element:  class="text-white" -->

> > Author Notes:

So the goal of the training today is to get you comfortable delivering exercise files through Github.

This has been a long process that we've been testing and developing for several years.

The ultimate goal is to deliver all technology courses in this manner inside of the next year.

---

# Project Log

- Prototyping, Legal, Docs
- Producer Training
- Select Producers/Authors
- All Tech Library
- Ongoing Process

> > Author Notes:

It's taken years to get the project to where it's currently at. It's been a grass roots effort that started with a handful of authors finding different ways to work with Github, then moved on to creating a consistent prototype

Today, we're starting to train producers and get them involved in how the process works so that they're comfortable using the process and implementing it into their workflow.

Next, we'll identify a handful of producer who can be leaders and Instructors that would be great testers for the process. So far, this process has been designed by authors, legal and management, so we need to test our assumptions and make changes to the process.

Once we validate our process, then we can expand the process to additional Producers and authors.

The ultimate goal is that within a year, all technology content will use the process.

Because this project relies on software and methodologies that are constantly change, consider this process more of a living process. Github is improving their product rapidly with CI/CD features like Actions and tighter deployment integration. So instead of being set in stone.

---

# Why Github

- [Industry Standard](https://github.com/about)
- [Part of the Family](https://blogs.microsoft.com/blog/2018/06/04/microsoft-github-empowering-developers/)
- [Rich Interactive Features](https://github.com/features)
- Future Capabilities

> > Author Notes:

Github is the biggest social hub for source code on the internet.

GitHub is part of the Microsoft family, just like LinkedIn.

Github also gives both the teacher and the student additional capabilities and features. We'll talk about those in a moment.

Publishing course files on Gihub also gives us the ability to have a modern, interactive and social platform to publish content in and it will open up what we can do to deliver practice based technology learning content.

---

# Basic Features

- [Start](https://github.com/planetoftheweb/bootstrap4/blob/03_07b/builds/bootstrap/index.html)/[End](https://github.com/planetoftheweb/bootstrap4/blob/03_07b/builds/bootstrap/index.html) Snapshots
- Distributed Environment
- Works with any filetypes
- Stores only changes in files

> > Author Notes:

Git lets you create snapshots of your code at different times in the development process. We use this feature to store the state of the beginning of each video we record as well as the end of each video. This allows authors to freeze each state of the project as they record.

Git is also a distributed environment, that means that when someone downloads the repository, they have a copy of the environment the teacher uses, duplicating the same build tools and modules they use to run the softare.

Git handles any file type; text, code, scripts, config, data (json, xml). It works with binary files too; images, database, media etc. Maximum file size per file is 100MB.

It handles file and folder renames and relocations. In essense, Git creates an invisible .git folder that stores the changes between the files, so it's super efficient and creates tiny folders without making us create different folders for different start and end states like we do in exercise files. You can also hide certain folders like the node_modules folders or build folders, making the files even smaller.

---

# Bonus Features

- [Versioning/Updating](https://github.com/LinkedInLearning/svelte-firstlook-2824055/blob/master/package.json)
- [Diffing](https://github.com/linkedInLearning/svelte-firstlook-2824055/compare/01_06b..01_06e)
- [Wiki](https://github.com/LinkedInLearning/svelte-firstlook-2824055/wiki/01_04-Looping-through-data)
- [Zip Files](https://github.com/LinkedInLearning/svelte-firstlook-2824055/archive/master.zip)
- [Starring](https://github.com/planetoftheweb/sassEssentials/stargazers), [Forking](https://github.com/planetoftheweb/sassEssentials/network/members), [Deployments](https://pages.github.com/)

> > Author Notes:

Let's briefly talk about some of the features that are available to us as a result of using Github.

Instead of telling users to go to a site and install a copy of a framework, we can include a package.json file and package-lock.json file which lock-in the version of the modules a project uses. The project is also easier to update because we can push changes to the repository's branches quickly.

One of my favorite features of this process is that Github provides a visual diffing of branches, which lets you look at the differences between the beginning and ending version of code. That makes it easier to record a course, but also gives users the ability to compare their own code with a branch.

Github also provides a Wiki, which can have color coded snippets of code that you can point to. This can also be a quick way to publish simple blog type content to the project. Everything is kept safe by giving us control over the repositories in a central LinkedIn account.

Repositories are search engine indexed, so this allows pointing back to our courses from within Github as well as being able to track the usage of repositories using stats like Stars, Forks and a full analytics package.

Github even lets you create deployments of your projects and you can even combine things like Now or Netlify that give you multiple deployments per commit so you can not only show someone the code for a project, but deploy a sample site of how the code looks.

---

# What do you need?

- [Github Account](https://github.com/join)
- [Two-factor Authentication](https://github.com/settings/security)
- [Node.js](https://nodejs.org/en/)
- [Git/Gitbash](https://git-scm.com/downloads)
- [Terminal](https://hyper.is)

> > Author Notes:

To get started, you need a Github account of course.

It's company policy as a LinkedIn employee that Github users must have two-factor authentication turned on when using Github, so make sure you've set that up.

If you're doing any type of web work, you'll probably want to make sure you have Node.js installed (most repos require running build tool installations.)

Github is nothing without Git, which is the version control system it is based on, so make sure you have git installed on your machine.

You'll also need a terminal in order to run Github commands, so make sure it's set up.

---

<!-- .slide: data-state="title" class="bg-dark text-warning" -->

# Github Process

---

# Github Roles

1. [Github Admin](https://github.com/linkedInLearning) (Samara)
1. Producer
1. Instructor
1. QA Tester

> > Author Notes:

There are four distinct roles in the process. One Github Admin is the manager for the how the other roles interact with the repos within our Github Organization. We gave an Enterprise account where all repos are published. This allows us to have control over the repositories.

Producers create the original repositories by sending a request to the Admin. They also instructs the QA team to request access to the LiL Private repo. Producers may also create the repositories for other authors. This is probably the least defined role currently.

Instructors use the repositories to create the courses and then push the content into the brances. Staff Instructors can handle some of the producer responsibilities as well.

---

# Producers

1. Make sure Instructors<br>have a Github Account
1. Send an email to:<br>[ldc-prod-assets@linkedin.com](mailto://ldc-prod-assets@linkedin.com).

```text
Course Name:
Course ID:
Repo Name:
Producer GitHub Account Name:
Author GitHub Account Name:
```

<!-- .element: class="fragment" -->

---

<!-- .slide: data-state="title" class="bg-dark text-warning" -->

# Repo Names

The repo names should have an identifier, a short name (i.e. bootstrap4), a short identifier (i.e. “esst” for “Essential Training”) and the course ID at the end. For example, a course for Bootstrap Essential Training with a course id of 123456 would have a name<!-- .element:  class="text-white" -->

`bootstrap4-esst-123456`

> > Author Notes:

Once the request is processed, a new private repo will be created under the LinkedIn Learning GitHub organization. You and the author will receive an email invitation to the repository. The repository will include a number of files that will need to be in the final repository.

---

# What's In the Repo

- [CONTRIBUTING](https://github.com/LinkedInLearning/github-producer-training-01/blob/master/CONTRIBUTING.md), [LICENSE](https://github.com/LinkedInLearning/github-producer-training-01/blob/master/LICENSE), [NOTICE](https://github.com/LinkedInLearning/github-producer-training-01/blob/master/NOTICE)

- [README.md](https://github.com/LinkedInLearning/github-producer-training-01/blob/master/README.md)
- [.gitignore](https://github.com/LinkedInLearning/github-producer-training-01/blob/master/.gitignore) sample
- [.github](https://github.com/LinkedInLearning/github-producer-training-01/tree/master/.github) folder

> > Author Notes:

The default template has a number of boilerplate files, including a file detailing how to make contributions (we don't accept those), a license (default is a standard LinkedIn License, if you need a non-standard license, you'll need to request one from the Admin) and a Notice.

There is also a template for a README.md file. Feel free to change that, but do include installation instructions. This file might be something that we update right before the course launches.

`.gitignore` is a special git file that prevents certain files from being copied to the github. This should at minimum contain the node_modules folder, but you can add other folders here as the project dictates.

`.github` file contains special files that are used by github to provide special information. You might see something like an issue template, so that if a user starts an issue, they are guided as to what information to provide before an issue is submitted.

---

# Using the Repo

1. Fork the repo
1. Clone Repo
1. Record the course
1. Pull Request changes

> > Author Notes:

To get started with recording, the Instructor may fork the repository into their own account or their local machine.

Now, the instructor clones the repo to their recording computer.

The instructor records the course creating branches along the way at the beginning and end of each video.

Once recording is complete, the Instructor issues a pull request to the original repository and merges all of the changes.

---

# Course recording

```bash
1. git add --all
2. git commit -m "MY FIRST COMMIT"
3. git checkout -b 02_01b
4. git checkout -b 02_01e
# Record movie as normal.
5. git add –all && git commit -m "RECORDED 02_01 SUCCESSFULLY"
6. git checkout master
7. git merge 02_01b && git merge 02_01e
# Return to step 3 for the next movie.
8. git push --all
```

> > Author Notes:

This procedure creates a branch structure where the master branch holds the final state of the exercise files and each movie has its own branch off master with each branch holding a sub-branch with the end state of the current movie.

`git add --all` In the master branch, add files and libraries as required for the starting point of the first movie with exercise files for the movie you are currently recording.

`git commit -m "MY FIRST COMMIT"` Commit starting point to master branch.

`git checkout -b 02_01b` Create and checkout a branch for the current movie. Branch name will be in the format XX_YY format where XX is chapter number with leading 0's and YY is movie number, so chapter 2 movie 1 has the branch name 02_01

`git checkout -b 02_01e` Create and checkout a new branch for the finished version of the movie with the format XX_YYe (e means this is the end state for the current video)

Record movie as normal.

git add –all && git commit -m "RECORDED 02_01 SUCCESSFULLY" If recording is successful and exercise files are complete, add all of the changes and commit them to the finished branch. Otherwise, you may use git checkout .to revert the files to their starting state and record again.

`git checkout master` Checkout master branch.

`git merge 02_01e` with master branch.

Return to step 3 for the next movie.

`git push --all` Push the finished branches to repo

---

# Record Complete

- Clean up branches
- `$ git remote add upstream GITHUBURL`
- `git push –-mirror upstream`

---

# Producer

- Verify integrity, LICENSE
- Notify Admin: make repo public
- Update README.md

---

# Additional Information

- [Training Teams Channel](https://teams.microsoft.com/l/team/19%3a767edc0a4b544a549d6b61cc7599a0a8%40thread.skype/conversations?groupId=a5162fcd-0eb9-41e6-a103-c4035631df33&tenantId=72f988bf-86f1-41af-91ab-2d7cd011db47)
- [Roles Documentation](https://microsoft.sharepoint.com/:w:/t/GithubProducerTraining/EVmS63aUXqFLqTdlTvi6RrUBMIUSo6bJrVpBYVqYNQxQdw?e=gtDQav)
- [Why Use Github](https://microsoft.sharepoint.com/:w:/t/GithubProducerTraining/EbNBOcGHDYxMoRtnzd-ZDrkB12H1OAi7qxqKwW4MTGToBg?e=KDDSKG)
- [Instructor Docs](https://microsoft.sharepoint.com/:w:/t/GithubProducerTraining/EcMdVQgz5DFCmKm9H6bdrcsBPVwZ1diA4rjecVAiylkmNg?e=Tbqo1K)
- [Producer Docs](https://microsoft.sharepoint.com/:w:/t/GithubProducerTraining/EdJSLo5wV0hEo03uIgyqedQBSx2vBqvSSQGkcQc2w7wItg?e=wEo8dZ)

---

# Courses

- [Learning Git and Github](https://www.linkedin.com/learning/learning-git-and-github/welcome?u=104)
- [Github Essential Training](https://www.linkedin.com/learning/github-essential-training/)
- [Git Essential Training](https://www.linkedin.com/learning/git-essential-training-the-basics/)

---

# Let's do this

- [Use Template](https://github.com/planetoftheweb/producer-template)
- [Download Sample Content](https://github.com/planetoftheweb/producer-training/archive/master.zip)
- Add contents of producer-training

---

# Process

```bash
1. git add --all
2. git commit -m "MY FIRST COMMIT"
3. npm install
4. npm start
5. git checkout -b 01_01b
6. git checkout -b 01_01e
# Add newslide.md file to docs/slides folder
7. git add –all && git commit -m "Added Slide"
8. git checkout master
9. git merge 01_01e
# Record two more branches 01_02b 01_02e
10. git push --all
# Publish the link to repo on Teams
# Bonus: If you want to see your slideshow
# turn on Github Pages using master/docs
# in project/settings
```
