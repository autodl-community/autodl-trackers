## Requesting a new tracker

[Submit an issue](#submitting-an-issue) to the [Issue Tracker](https://github.com/autodl-community/autodl-trackers/issues) or come to the IRC channel below with the following information:

* Tracker name
* Tracker abbreviation (if applicable)
* Tracker IRC server address
* Tracker IRC announce channel
* Tracker IRC announcer name
* A decent size sampling of announces from the announce channel (at least 5-10)

Preferably, this information should be provided using a pastebin site. More information may be requested if necessary.

## Submitting an issue

Bug reports and feature requests can be submitted to our [Issue Tracker](https://github.com/autodl-community/autodl-trackers/issues).

Some general guidelines to follow:

* Use an appropriate, descriptive title.
* Provide as many details as possible.
* Don't piggy-back. Keep separate topics in separate issues.

If you need to keep some information private, you can e-mail autodl.community@gmail.com with the subject ``Issue #`` replacing \# with the number of your issue.

## Submitting code

Patches are welcome. Keep your code consistent with the rest of the project (use tabs for indentation, etc). If you have any questions or concerns, contact us through the methods listed below.

For simple, single file changes/additions, sending or linking your modified file is acceptable. For complex, multiple file changes, creating a diff file or using GitHub's [Pull Request](https://help.github.com/articles/using-pull-requests/) feature is preferable.

### Pull Requests

You should create a separate [feature branch][fb] in your [fork][fork] to commit your changes to. [Pull Requests](https://help.github.com/articles/creating-a-pull-request) will only be accepted if made from a [feature branch][fb] and against the [devel](https://github.com/autodl-community/autodl-trackers/tree/devel) branch of this repository.

Commit messages should be written in a [well-formed, consistent](https://sethrobertson.github.io/GitBestPractices/#usemsg) manner. See the [commit log](https://github.com/autodl-community/autodl-trackers/commits/devel) for acceptable examples.

Each commit should encompass the smallest logical changeset (e.g. changing two unrelated things in the same file would be two commits rather than one commit of "Change filename".) If you made a mistake in a commit in your Pull Request, you should [amend](https://www.atlassian.com/git/tutorials/rewriting-history/git-commit--amend) or [rebase](https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase-i) to change your previous commit(s) then [force push](http://stackoverflow.com/a/12610763) to the [feature branch][fb] in your [fork][fork].

[fb]: https://help.github.com/articles/creating-and-deleting-branches-within-your-repository/#creating-a-branch
[fork]: https://help.github.com/articles/fork-a-repo
