
# An Introduction to GitHub


## Introduction
[GitHub](https://github.com/) is a website  for uploading, sharing and collaborating on projects. It is primarily used by software developers and data analysts/data scientists to share their code and to collaborate - either within their team or with people from other organizations (such as on Open Source projects).

In addition, at Flatiron School, we use GitHub to store all of our lessons. So this content that you are reading now, is stored on GitHub! In this lesson we'll look at what GitHub is and we'll provide a brief overview of how it can be used for collaboration.

## Objectives
You will be able to:
* Explain how and why people use GitHub to collaborate


### The Importance of Open Source Software 
Open Source Software (OSS) - depending on the specific license - is software that you are free to view the source code to, free to modify, and (often) there is no charge for using the software. 

OSS is the basis of most software developed today. If you're hosting a website on a Linux server (and most websites are hosted on Linux), the operating system, hosting software and most of the other tools to enable that are open source projects. When you write code using Python, you're taking advantage of an open source programming language.

As you start to use packages like Pandas and NumPy for data manipulation, you're using Open Source Software. If you use matplotlib for visualization or pretty much any other Python package, you're using OSS. Most of those Open Source projects live on GitHub and it's the place to go if you want to learn more about a project, report a bug or view the underlying source code.

### GitHub and the History of OSS
Back in 2007, if you wanted to manage an OSS project, people generally had to email you if they had improvements they wanted to make to your project. You then needed to take the code from their email, test it, maybe share it with a couple of other contributors via email, summarize their feedback, and usually there would be a lengthy back and forth as you asked the submitter to improve their proposed changes (often called a "patch"). Because of that, most OSS projects only had a handful of committers (people who had submitted code to make the projects better). It was just too much trouble to engage with more than a few tens of people for most project leads.

In 2008, that all changed. With GitHub, you could upload your project and anyone could "fork" your project (make their own copy that they could change), make some improvements and then easily submit a "Pull Request" to allow them to propose improvements to the project (Requesting that you Pull their changes back into your copy of the project to improve it). 

As a project lead, all you had to do was "check out" the Pull Request (download and look at it on your computer), "at mention" anyone else you wanted to take a look (e.g. "Hey @peterbell, what do you think about this improvement"), add comments if you want any changes from the submitter, and then click a single button to "merge" the work back into your "upstream" project. 

It became possible for volunteer, part time project leads to run OSS projects with hundreds or thousands of committers. It's like the difference between using MailChimp to send an email newsletter to all your friends vs. hand writing a personalized card to everyone you know to keep them up to date with what you've been doing.

In the decade since GitHub launched, one of the reasons for the explosive growth in OSS has been the fact that GitHub is a single, central repository for OSS projects with a consistent interface for downloading, commenting on and contributing to all of the projects. 


### What is a Project?
One question that often comes up - what *is* a project in GitHub? Technically it is a Git repository (if you were wondering, that's another reason we introduced you to Git earlier in the course), along with some additional features like Issues and Pull Requests to facilitate collaboration.

You could think of it like a folder/directory on your desktop. It is a container for a series of files (some of which might be in subdirectories) as well as additional information *about* those files including the history of revisions made to them over time. 

Typically there will be a text file in the root (top) directory called README.md that explains what the project is about and how to install and use it. There may also be the option to submit Issues (if you want to report a problem with the software) and/or to submit Pull Requests if you'd like to improve it. Here's an example, it's the GitHub repo* for Pandas, a popular data manipulation package for Python.

\* *Repo - short for repository. When people talk about content on GitHub they will often interchangeably refer to a project, a repository or a repo.*

![Pandas](http://curriculum-content.s3.amazonaws.com/ent-ds-deloitte/pandas.png)

### Collaborating through GitHub
There are lots of ways to use GitHub for collaboration, but the two most common ones that we're going to introduce briefly are Issues and Pull Requests.

GitHub Issues allows you to add or comment on an issue with a project (perhaps a bug or other unexpected behavior). They're pretty straightforward. Click on the Issues tab in a project (support for Issues is optional - so not all projects have them) and then add a new issue or add a comment to an existing one. The purpose of issues is to allow you to comment on the project without actually submitting changes to the code.

Pull Requests allow you to propose a set of changes to the content of a project. The workflow is that you:
* Fork the repo - making your own copy
* Clone the repo - downloading a copy of the files to your computer
* Make the changes - change the files to improve the project
* Commit your changes - use Git to save the changes you made locally
* Push your changes - upload the changes you saved into Git to your copy of the project on GitHub
* Submit a Pull Request - create a Pull Request requesting that the original project owner/maintainer take your changes and make them part of their project

Don't worry if that sounds like a lot or is confusing right now. At the moment, we're just introducing some terminology so it's not completely new to you when class starts. You'll get plenty of chances to practice your Git and GitHub skills as the course progresses, and your teacher will be available to answer any questions you might have!


## Summary

It's important to have a sense of how to use GitHub for collaboration and to understand what key terms like Repo, Pull Request, Fork and Clone mean. But we're not going to dig too deeply into GitHub. However, in the next lesson, we will build on this introduction to GitHub to run you through how to use it as part of this course!

