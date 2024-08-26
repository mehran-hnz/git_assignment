# Git Assignment - mehran-hnz

### a. What is an issue?

An issue is like a note or a to-do list where people can report bugs, suggest features, or ask questions in a project. It’s a way to keep track of things that need attention.

### b. What is a pull request?

A pull request (PR) is when we're ready to share the changes we’ve made with the rest of the team. basically saying, “Hey, I’ve made these updates, can someone check them out and approve them for merging into the main code?”

### c. Describe the steps to open a pull request?

1.  Push the branch with changes to GitHub.
2.  Go to the repository on GitHub and on the Pull Requests tab click New pull request.
3.  Choose the branch with changes and the branch you want to merge into.
4.  Add a title and description to explain what changed and Create pull request

### d. Describe the steps to add a collaborator to a repository (share write permissions)

1.  on the repository on GitHub , click Settings.
2.  Under Collaborators and teams, add the person’s username or email.
3.  Send them an invite, and they’ll need to accept it.

### e. What is the difference between `git` and `GitHub`?

`Git` is the tool that tracks changes in our code (a distributed version control system).

`GitHub` is a place to store that code online (a web-based platform for hosting Git repositories), collaborate with others, and keep everything organized.

### f. What does `git diff` do?

`git diff` shows you what’s different between our working files and what’s already staged or committed. It’s basically a sneak peek of what’s changed.

### g. What is the main branch?

The main branch is the primary branch in a repo. It’s where the stable, production-ready code should be. (Old days, it was called Master!)

### h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

No. It’s better to work in a separate branch and then use a pull request to merge our changes. This way, others can review our code before it goes into the main branch.
