---
title: Managing Content with Git and GitLab
---


# {{ page.title }}

If you are a writer working on a project that needs you to collaborate with multiple writers who are working and making changes to the same document, you may have faced multiple issues such as merging the changes, maintaining different versions of the same document, storing files in a location easily accessible to everyone in the team. You may have noticed that Software developers work in a similar setup and face similar challenges but the problem of maintaining their code was not as daunting task as it seemed to be for documents. You would hate to disagree if I told that you can use the same solution that developers use to ease your life in managing your content by using utilities such as Git/GitLab for collaboration and Markdown as your authoring language.
In this article, let us try to understand what these utilities have to offer!

## Version Control Is Not Only for Code

Before getting into the specifics of Git and GitLab, let us understand that, in a project, everything needs to be tracked irrespective of whether it is software code, a document or any other type of content. Therefore, you will be happy to know that writers can harness the benefits of a version control system just like the developers do. And, utilities such a Git, GitLab, and authoring language such as Markdown enable you to do so.

# What is Version Control System?

A version control system helps in maintaining a record of all documents and changes made to those documents, in a single location. Users can extract a specific version of the document, if need be.  A version control system can use a local model (users using same file system), client-server model (users using same shared repository), or distributed model (separate repository created for each user).

# Git

Git is a collaboration tool designed and developed by Linus Torvalds who led the Linux kernel project. Ever since its inception in 2005, Git has been the most popular version control system, and has dominated the version control space.

Git is version control system that follows the distributed version control model. Git is not only targeted at developers who want to store/track their code but non-technical users can also reap the same benefits.

which means it manages changes to a project without overwriting any part of that project.

Git helps in tracking and managing documentation changes such that reverting to any previous change is simple and easy. This way changes are not lost and a document is not overwritten with any changes.

In Git, your documents are stored under a repository (repo) that is equivalent to a folder on your Windows/Mac system. Unlike certain word processors, Git does not periodically save different versions of your documents. Instead, Git will save changes only if you specifically instruct Git to do so.

Though Git is a version control system, it can also be considered as a source code management system and a revision control system. It is like a one stop solution to manage/maintain your content.

## Work Offline as Seamlessly as Working Online

As writers, inspiration strikes us anywhere and we would want to pen them down irrespective of whether we are hooked to the Internet or not. This means that we do not want our work to be disrupted whether we are online or offline. Git provides the facility to work on your local system while you are on the move by allowing you to commit, browse, merge, or create branches. The next instance you are connected to the Internet, you can instruct Git to push these changes to the main branch.
