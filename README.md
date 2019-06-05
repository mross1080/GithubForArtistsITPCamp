# Github for Artists

Welcome to GitHub for artists! This repository is an introduction to the history and basics of git, by [Matt Ross]() and [Brent Bailey](http://brentlbailey.com). Git and GitHub are extremely powerful tools for collaborative and iterative work, and an essential part of anyone working in creative technology or digital media’s toolkit. It’s our hope that these tutorials and resources will help people new to these technologies begin to adopt them. To that end, we’re happy to accept pull requests, suggestions, and more to make these resources as useful as they can be.

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
<p style=”text-align: center;” align=”center”>
<img src=img/linus.jpg>
<br />
Linus Torvalds, creator of Git and Linux
</p>
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

## Other Things To Know

### Other Stuff You Can Do On GitHub

[Github Pages](https://pages.github.com/) : a quick and easy hosting solution for static websites. Unlimited repositories. Can’t host any servers or anything particularly complex.

[Wikis](https://help.github.com/en/articles/about-wikis): a great way to document more complex open-source projects (or use as a blog, syllabus, or any other purpose you might think of).

[Pro and Enterprise](https://help.github.com/en/articles/githubs-products) : starting a business? Working with a big group? Want to keep your code closed-source (boooooo)? Github has a range of options for professional and enterprise use.


### Licensing

Most publicly available code on GitHub is considered open-source (which means anyone can use or contribute to it). If you want to keep your code closed-source and private, you’ll have to register for the paid GitHub tier. If you’re comfortable with keeping your code open, it’s wise to pick a license. Licenses are basically some legalese that determines how your code can be used. The most common ones on GitHub are the MIT License, which basically allows any use of your code including creating closed-source versions, and the GNU License, which allows any use *except* closed-source. If you need help choosing your license, [ChooseALicense](https://choosealicense.com/) is a helpful resource. To add licensing to your repository, you can follow the instructions [here](https://help.github.com/en/articles/licensing-a-repository).

### Resources

If we’ve successfully convinced you that git and GitHub are the way to go, you’re in luck: there are tons of resources out there for both. We’ll list a few here:

*[Git Cheat Sheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)* : a list of commonly used git commands.

*[GitHub Guides](https://guides.github.com/): a series of tutorials produced by GitHub for learning its tools. Great way to get started with GitHub Pages, creating wikis, and more.

*[Version Control with Git](http://shop.oreilly.com/product/0636920022862.do) : getting reallllly into git? Check out O’Reilly’s version control with git, a great resource for getting super in-depth.


