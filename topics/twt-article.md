---
title: Managing Web Content Using Git, GitHub, and Markdown
layout: template_file
---


# {{ page.title }}

If you are a writer working on a project that needs you to collaborate with multiple writers who are working and making changes to the same document, you may have faced multiple issues such as merging the changes, maintaining different versions of the same document, storing files in a location easily accessible to everyone in the team. You may have noticed that Software developers work in a similar setup and face similar challenges but the problem of maintaining their code was not as daunting task as it seemed to be for documents. You would hate to agree if I told that you can use the same solution that developers use to ease your life in managing your content by using utilities such as Git/GitHub for collaboration and Markdown as your authoring language.
In this article, let us try to understand what these utilities have to offer!

## Version Control Is Not Only for Code

Before getting into the specifics of Git, GitHub and Markdown, let us understand that, in a project, everything needs to be tracked irrespective of whether it is software code, a document or any other type of content. Therefore, you will be happy to know that writers can harness the benefits of a version control system just like the developers do. And, utilities such a Git, GitHub, and authoring language such as Markdown enable you to do so.

## What is a Version Control System?

A version control system helps in maintaining a record of all documents and changes made to those documents, in a single location. Users can extract a specific version of the document, if need be.  A version control system can use a local model (users using same file system), client-server model (users using same shared repository), or distributed model (separate repository created for each user).

## Git – The Distributed Version Control System

Git is a collaboration tool designed and developed by Linus Torvalds who led the Linux kernel project. Ever since its inception in 2005, Git has been the most popular version control system, and has dominated the version control space.

Git is version control system that follows the distributed version control model in which your documents are stored under a repository (repo) that is equivalent to a folder on your Windows/Mac system. Unlike certain word processors, Git does not periodically save updated versions of your documents. Instead, Git will save changes only if you specifically instruct Git to do so.

Git helps in tracking and managing documentation changes such that reverting to any previous change is simple and easy. This way changes are not lost and a document is not overwritten with any changes.

> Note that, Git is not only targeted at developers who want to store/track their code, but non-technical users can also reap the same benefits.

Though Git is a version control system, it can also be considered as a source code management system and a revision control system. It is like a one stop solution to manage/maintain your content.

### Work Offline as Seamlessly as Working Online

As writers, inspiration strikes us anywhere and we would want to pen them down irrespective of whether we are hooked to the Internet or not. This means that we do not want our work to be disrupted whether we are online or offline. Git provides the facility to work on your local system while you are on the move by allowing you to commit, browse, merge, or create branches. The next instance you are connected to the Internet, you can instruct Git to push these changes to the main branch.

### Why Use Something Like Git?

Using Git to manage your next writing project gives you the ability to view multiple drafts at the same time, see differences between those drafts, and even roll back to a previous version. And if you’re comfortable doing so, you can then share your work with others on GitHub or other central Git repositories.

For instance, consider two writers in the same project are updating the same page for a document. If the first writer makes changes to the document and uploads the changed document while the second writer has also uploaded a changed document. In an ideal situation, one of the writers will loose their changes but with Git that does not happen. Though both writers upload the same document with their changes, Git maintains separate copies of each document. Anyone can later decide to merge changes in both the documents or later, even decide to revert to the previous version of the document as Git has anyways stored a snapshot of each change made to a document.  

## Using GitHub to Enhance Your Git Experience

GitHub is a cloud-based version control service that incorporates Git’s version control features. While Git is a distributed version control software that you can install locally on your system, GitHub is a web-based utility where files are stored on a GitHub Web server. Unlike Git which is a command-line utility, GitHub provides a graphical user interface to view and manage files placed under a repository. If you are a writer authoring content in text-based authoring formats, such as Markdown and HTML, you can avail the additional benefit that GitHub offers, that is of a Web publishing engine. GitHub has an integrated publishing engine that renders your content on the Web, and provides a unique URL to access it too. This way, GitHub is not just a revision control repository but also a Web publishing engine.  

With GitHub, you can either configure a repository to be private to you or to the team, or you can also configure the repository as public that allowing anyone to download the repository and make changes. However, these changes will need to be sent as change requests and you can decide whether to accept and merge these changes to your file.

### Git and GitHub – Are They Same or Different?

The answer is no. As discussed previously, Git and GitHub are similar to the extent that both provide version control services but GitHub is much more than that. In addition to the version control feature, GitHub provides several security and collaboration features like, Wikis, and task management tools for each project. If your intention is only to work locally, then Git is your best option, but if you want to collaborate with multiple writers, then GitHub is the solution for you.


## Markdown – The Popular Text-Based Authoring Format

In 2004, John Gruber and Aaron Swartz created the Markdown language with an intention to provide a language that was easy to write and read. Markdown was developed in such a way that it did not appear as if the Markdown file was marked up with tags to depict formatting styles like in an HTML file.

Markdown is a plain text formatting language and also a tool to convert this plain text to a valid HTML file. Markdown provides several simple tags that you can use to define formatting such as bold, underline, italics, lists, and so on. However, the presence of these tags does not interfere with the readability of the document and you can read a Markdown document with the same ease as you would read the same document when it is converted to HTML.

If you want to author a document in Markdown, text editors compatible with Markdown authoring are freely available on the Web for the Windows and Mac Operating systems. If you do not want to install a Markdown editor on your system, you can work on an online editor, such as Dillinger that provides a HTML preview of your Markdown document in the left pane of the editor.

Due to the widespread popularity of Markdown, several implementations were developed such as the GitHub Flavoured Markdown (GFM) developed by GitHub in 2017. GFM is the default markdown format used for documents stored in a GitHub repository unless you override the formatting by defining your own template and stylesheet.

One of the advantages of using Markdown formatted files in GitHub is that it is easy to compare files for changes because Markdown is a plain text file, like a developer’s code. This makes merging documentation changes also easy, a feature that is prevalent in the coding world!


### Is Markdown Good for Writers?

Markdown is a great format for Web content. Off late many writers wish to maintain a blog of their own and Markdown is the best format to use. To create a blog of your own, create a document and save it with .md or .Markdown, the Markdown extension. Further, create a repository on a cloud-based version control system, such as GitHub, and copy your .md file in that repository. GitHub provides a personalized URL when the .md file is hosted in HTML format. This way you can focus your energy in writing quality content and leave the HTML rendering nuances to GitHub.

Markdown is platform agnostic in the sense that you need not be associated to the format of your editor. For instance, to create a .md file, you can use any editor installed on your system or use a version control system like GitHub as it provides an inbuilt Markdown editor.

As Markdown is a lightweight plain text format, the learning curve is not much, and anybody can start using it quickly.

While advantages of Markdown are manifold, a probable disadvantage may be that you need to remember different Markdown tags as there is no button that you can click to get the required formatting.
