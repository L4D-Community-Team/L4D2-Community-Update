# Introduction

Hey there!

We are thrilled that you would like to help. If you ever have a question it is probably addressed below; if not, please [contact](/CODE_OF_CONDUCT.md#Contact) us.

As a community pursuit, everything we do is motivated by passion. Unlike [The Last Stand](https://www.l4d.com/laststand/), we are not officially greenlit for an update. However, we are not going to wait for life to happen to us. With the right amount of persistence and [a lot](https://developer.valvesoftware.com/wiki/Valve_Time) of patience, we aim to get out what we put in.

By participating, you agree to our [Code of Conduct](/CODE_OF_CONDUCT.md).

# Issues

## Create a new issue
If you are here to report a bug, first [search if an issue already exists](https://github.com/Tsuey/L4D2-Community-Update/issues?q=is%3Aopen) [^1]. If a related issue doesn't exist, you can [open a new issue using a relevant issue form](https://github.com/Tsuey/L4D2-Community-Update/issues/new).

## Help to solve an issue
Scan through our [existing issues](https://github.com/Tsuey/L4D2-Community-Update/issues?q=is%3Aopen) to find one that interests you. You can narrow down the search using labels as filters. If you find an issue to work on thats not assigned to anyone, you are welcome to open a PR with a fix.

# Submissions

If you are here to submit files, please first consider opening an [issue](https://github.com/Tsuey/L4D2-Community-Update/issues) to ask questions or discuss potentially [subjective](https://en.wikipedia.org/wiki/Subjective) changes or improvements first.

## Contributor Guidelines
In the interest of avoiding [bikeshedding](https://docs.freebsd.org/en/books/faq/#bikeshed-painting), please keep the following in mind for every submission:

- If the repository does not already have the text file, please submit the unchanged files as the earliest commits, then your changes.
- When it comes to model, texture, or other files not included in game distribution, please contact **Lt. Rocky** (Discord: `Lt. Rocky#7341`) directly. We store these files separately and cannot accept them here.
- Valve needs to verify every byte we edit, so every submission must serve some functional utility. Maintenance tasks such as optimization and changelogs are the responsibility of maintainers.
- Usage of leading tabs are preferred over spaces for non-generated text files.
- For [VDF/KeyValues](https://developer.valvesoftware.com/wiki/KeyValues) files, enclosing tokens in double quotes is preferred.
- [ByteOrderMark](https://en.wikipedia.org/wiki/Byte_order_mark#UTF-8) is not allowed for text files encoded with UTF-8.
- Keep changes as focused as possible. If there are multiple changes that are not dependent on each other, consider a separate PR.
- Please [mark PR's as drafts](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/changing-the-stage-of-a-pull-request) if they are not yet ready for review.
- Finally, write [good commit messages](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html).

## Make Changes
### Make changes locally
1. Fork the repository.
   - Using GitHub Desktop:
     - [Getting started with GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/getting-started-with-github-desktop) will guide you through setting up Desktop.
     - Once Desktop is set up, you can use it to [fork the repo](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/cloning-and-forking-repositories-from-github-desktop)!
   - Using the command line:
     - [Fork the repo](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo#fork-an-example-repository) so that you can make your changes without affecting the original project until you're ready to merge them.
2. Create a working branch and start with your changes!
### Commit your update
Commit the changes once you are happy with them.

## Pull Request
When you're finished with the changes, create a pull request, also known as a PR.

- Don't forget to [link PR to issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue) if you are solving one.
- Enable the checkbox to [allow maintainer edits](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/allowing-changes-to-a-pull-request-branch-created-from-a-fork) so the branch can be updated for a merge. Once you submit your PR, a Docs team member will review your proposal. We may ask questions or request for additional information.
- We may ask for changes to be made before a PR can be merged, either using [suggested changes](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/incorporating-feedback-in-your-pull-request) or pull request comments. You can apply suggested changes in your fork, then commit them to your branch.
- As you update your PR and apply changes, [mark each conversation as resolved](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request#resolving-conversations).
- If you run into any merge issues, checkout this [git tutorial](https://lab.github.com/githubtraining/managing-merge-conflicts) to help you resolve merge conflicts and other issues.

[^1]: Help: [Searching issues and pull requests](https://docs.github.com/en/github/searching-for-information-on-github/searching-on-github/searching-issues-and-pull-requests#search-by-the-title-body-or-comments).
