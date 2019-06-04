# Github for Artists



1. Here are other ways of sharing files and doing version control
1. Flounder through it
2. What is Github,
  1. History
  2. What is git vs GitHub,
  3. Open Source
  1. Licesnses
  3. Create Github account and install git
  * Pull Repo
  4. basic git commands (i.e. how to work by yourself and just have a more efficient version control system/public portfolio of code/open source bois),
  1. Here is what it’s like to work with multiple versions of the same thing
  2. Everyone add a file with their name and favorite food
5.  how to use branches(basically have a p5 sketch and have two different branches of two different aesthetic styles ) ,
  6. how to merge code with other people ( have a p5 sketch, have one person make changes adding ml5 or something have one person change the style or something, and show them how to combine)

## What’s Git?
  Git is a [version control system](https://www.atlassian.com/git/tutorials/what-is-version-control).
### What’s Version Control?
  Version control software allows multiple developers to manage and track changes to software over time. Git is a distributed version control system, meaning rather than every developer making changes to the same files that are centralized, all the changes made in git and similar version control systems are made on a local instance that is then “pushed” to a central repository when the changes are ready.
  Distributed version control systems are great because they:
  1. Keeps track of all changes made to every file in a repository (this is the fancy word people use for a file or set of files stored in git).
  2. Allows individual developers “push”, “pull”, “merge” and “branch” repositories.
  **Pull**: this allows you to download the code from the original repository, or any branch stored on GitHub.
  **Push**: this allows you to send changes you’ve made locally back to the original or master repository.
  **Branch**: this allows you to create a different version of a repository to work on a specific set of changes.
  **Merge**: this allows you to combine different branches of the same repository

->![Linus Torvalds](img/linus.jpg)<-

->*Linus Torvalds, creator of Git and Linux*<-
  Git was created in 2005 by Linus Torvalds for use by the open-source team working on the Linux kernel. He called it “git” because it’s British slang for a stupid person, and he calls it “the stupid content tracker”. This is what passes for humor in programming.

#### Alternatives to git
  * [Mercurial](https://www.mercurial-scm.org/): distributed VCS. Git’s closest competitor (although it’s losing the battle), allegedly easier to learn than git.
  * [Subversion](https://subversion.apache.org/): centralized VCS. No branching, better for storing binary files, more access control, considered easier to learn than git.


## What’s GitHub?

  GitHub is a git repository hosting service. It provides a web-based UI for git, and allows users to “fork” a repository, which is probably its “killer app”: forking allows users to create their own copies of someone else’s repository, add changes, and then create a “pull request” to the original repository if they so wish so that their changes are added to the original.

  There are a few alternatives to GitHub, although it’s by far the most popular hosting service available right now. I’ll list these, and their pros and cons, here:

| App | Pros | Cons |
| ------| ------| ------ |
| [GitHub](github.com)                | Most popular by far, great featureset, easy UI | Owned by Microsoft if that bothers you, doesn’t automatically come with continuous integration, doesn’t automatically come with a deployment platform, can’t export projects to other systems |
| [Bitbucket](https://bitbucket.org/) | Allows hosting with Mercurial as well as git, many of the same features as GitHub, unlimited private and public repos | Less pricing options, GUI is uglier |
| [GitLab](https://gitlab.com)        | Self-owned, comes with CI and deployment platform, greater control over permissions, allows importing data from other vendors, cheaper enterprise plan | Adoption less widespread, not as big of a dev community |


