# Editing the Guide

GitHub is a platform that is designed to support community collaboration on a single project. While it was designed for coders, it works great for lots of kinds of text-heavy content. 

This guide is largely written using [Markdown](https://www.markdownguide.org/getting-started/), which is a simple language used for formatting text. This page is written in markdown, for example. Thare are many markdown editors that are easy to use, and don't require you to write any code at all. 

Here are a few Markdown editors we recommend:

* [Typora](https://typora.io/) is a great desktop app with a very clean design for Mac, Windows, and Linux.
* [Stack Edit](https://stackedit.io/app#) is an online markdown editor designed for word processing for the web.

You can also use a simple text editor if you are willing to learn the markdown syntax—just please don't use a Word document or Google Doc. They sometimes format text in strange ways that doesn't translate well to this format.

## Appropriate content

Edits should either provide information about a new resource, provide more information about a resource, or else fix something that is incorrect in the guide. Keep in mind that some of our users may be young, elderly, differently abled, or in need of another cup of coffee. Generally speaking, try to write short, simple sentences that are easy to read. 

## Style guide

Submissions should adhere to our [style guide](#) to make sure the language and formatting is consistent with the rest of the guide. If you are having trouble with formatting, see [Troubleshooting](#troubleshooting) below.

## Making an edit

1. Make a GitHub account

   * Check out the excellent guide [GitHub for Non-Programmers](https://github.com/tvanantwerp/github-for-non-programmers) for some instructions.

2. Clone the project

   * This sounds technical, but it's really pretty easy. You can do it via the GitHub for Desktop app, or on the command line. This tutorial will assume you are using the GitHub for Desktop app.
   * From [the main page of the project](https://github.com/alpual/farming-the-rio-grande-valley), click the `Set up in Desktop` button at the top of the page.
   * Follow the instructions it gives you. When finished, you should have the project open and the files in a folder on your comuter. 

3. Make a branch

   * Again, this sounds technical, but it's not that hard. In the GitHub for Desktop app, click `Branch` >  `New Branch`. 
   * Choose a name for your branch. We recommend using `kebab-case`, (lower case letters separated by dashes).
   * Now all of your changes are tracked separately from the original text of the guide.

4. Edit the files

   * You can edit the files using any text editor (but don't use a word processor like Microsoft Word or Google Docs). A few Markdown editors we recommend are [Typora](typora.io) for editing on your computer, or [StackEdit](https://stackedit.io/app#) for editing online. Note that if you are using StackEdit, you will need to copy your Markdown to a local file to be able to commit your changes.

5. Commit your changes.

   * This is another technical step that isn't really that hard to do. A "commit" is a term we use to say that the changes you have made will be "saved" to the branch you are on. 

   * Once you are satisfied with your edits, make sure everything is saved. Then, in the bottom left corner of the GitHub for Desktop app, add a summary of your commit. You can also add a longer description. 
   * Hit the `Commit to <branch name>` button in the bottom corner.

6. Create a pull request

   * Currently, all of your changes are only tracked on your local computer. To let your collaborators know that you have changes to make to the project, click the Pull Request button.
   * For more on pull requests, check out [this tutorial](https://github.com/tvanantwerp/github-for-non-programmers/blob/master/05-branches/05-02-pull-requests.md).
   * If you have edited the same file as somebody else (and they got their pull request approved before you did), you will have conflicts. You will need to resolve those conflicts to continue. [This tutorial](https://dzone.com/articles/how-to-resolve-github-merge-conflicts) is aimed at coders, but it has some good information. If you get stuck, don't panic! Just reach out in your pull request and we can try to help.

7. Review

   * Once your Pull Request is posted, moderators will review it and make suggestions and comments. You will need to answer/address these to get your Pull Request approved.

8. Party!
   * You did it! Thanks for contributing!

## Troubleshooting

### Having trouble with formatting?

Check out the [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/) for a quick reference.

If you are still having trouble getting the formatting right, search the web for a while (it's what programmers do, too), or check out https://www.markdownguide.org/getting-started/. If that doesn't cut it, no worries! We're friendly, and we are happy to help. You can submit a pull request without formatting, and ask for help with the formatting.

### Having trouble with GitHub?

Go ahead and [submit an issue](#) and we'll try to help you out there.

### Having trouble with Git?

We feel you. It's a super powerful tool, but it can be confusing. GitHub provides a desktop app that makes life easier. Search engines are also your friend here. If you are still stuck, submit an issue and we'll try to help you out.

### Did you find these instructions confusing?

If so, please submit an issue or a PR so that we can improve this guide. Thanks!