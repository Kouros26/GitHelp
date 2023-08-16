# GitHelp-En

[French here](#githelp-fr)

Very basic tutorial on how to set up and work in a team with a clean GitHub workflow, intended for game designers, artists, or anyone with little GitHub experience. This tutorial assumes you know the basics of `pushing` and `pulling`.

1. [Setting up a safe repository](#setting-up-a-safe-repository)
2. [Pull requests](#pull-requests)
   - [What is a pull request](#what-is-a-pull-request)
   - [Open a pull request](#open-a-pull-request)
   - [Review a pull request](#review-a-pull-request)
  
## Setting up a safe repository

Setting up a safe repository is very important when collaborating for multiple reasons :

- Less error-prone
- Follow-ups on collaborators advancements
- Main branch will look like a **milestone achievement archive** instead of a mess of commits and merge one on top of the other

This tutorial will help you achieve that goal by **protecting the main branch** (i.e. preventing direct pushes to the main branch)
To protect your main branch, go into your repository's `Settings`, then go to `Branches`, if you don't see the "Branches" tab, it may be because you don't have anything pushed on your repository, so push a small file for the time being and try this step again.

![Branch tab in repository settings](img/settingsbranch.PNG)

After that click on the	`Add branch protection rule`, you will be greeted with a "form" that once completed should look like this :

![Branch protection](img/branchprotection.PNG)

Here we are telling GitHub that the protection rule should apply to the branch named `main`, that we ***NEED*** to make a [pull request](#pull-requests) in order to have anything go on the main branch (There's no other way now !), at least `1` person needs to approve our Pull request's changes in order to send them on the main branch, all the pull request's [conversations](#conversations) must be resolved, and finally the last checked parameter is `Do not allow bypassing the above settings`

This one tells GitHub that these rules also apply to the owner of the repository (you) and is very much recommended, just like all the other checked parameters on the image, but feel free to read about the other parameters and add them to your liking.

## Pull requests
### What is a pull request
### Open a pull request
### Review a pull request














# GitHelp-Fr

[English here](#githelp-en)

Tutoriel basique expliquant comment setup un environnement de travail GitHub, pensé pour les game designers, les artistes, ou toute personne avec peu d'expérience sur GitHub. Ce tutoriel part du principe que vous connaissez les bases des commandes `push` et `pull`
