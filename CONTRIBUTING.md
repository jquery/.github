# Contributing to jQuery projects

1. [Getting Involved](#getting-involved)
2. [Questions and Discussion](#questions-and-discussion)
3. [How To Report Bugs](#how-to-report-bugs)
4. [Specific Projects](#specific-projects)

## Getting Involved

[API design principles](https://github.com/jquery/jquery/wiki/API-design-guidelines)

We're always looking for help [identifying bugs](#how-to-report-bugs), writing and reducing test cases, and improving documentation. And although new features are rare, anything passing our [guidelines](https://github.com/jquery/jquery/wiki/Adding-new-features) will be considered.

More information on how to contribute to this and other jQuery organization projects is at [contribute.jquery.org](https://contribute.jquery.org), including a short guide with tips, tricks, and ideas on [getting started with open source](https://contribute.jquery.org/open-source/). Please review our [commit & pull request guide](https://contribute.jquery.org/commits-and-pull-requests/) and [style guides](https://contribute.jquery.org/style-guide/) for instructions on how to maintain a fork and submit patches.

When opening a pull request, you'll be asked to sign our Contributor License Agreement. Both the Corporate and Individual agreements can be [previewed on GitHub](https://github.com/openjs-foundation/easycla).

If you're looking for some good issues to start with, [here are some issues labeled "help wanted" or "patch welcome"](https://github.com/jquery/jquery/issues?q=is%3Aissue+label%3A%22help+wanted%22%2C%22Patch+Welcome%22).

## Questions and Discussion

### Forum and IRC

jQuery is so popular that many developers have knowledge of its capabilities and limitations. Most questions about using jQuery can be answered on popular forums such as [Stack Overflow](https://stackoverflow.com). Please start there when you have questions, even if you think you've found a bug.

The jQuery Core team watches the [jQuery Development Forum](https://forum.jquery.com/developing-jquery-core). If you have longer posts or questions that can't be answered in places such as Stack Overflow, please feel free to post them there. If you think you've found a bug, please [file it in the bug tracker](#how-to-report-bugs). The Core team can be found in the [#jquery-dev](https://webchat.freenode.net/?channels=jquery-dev) IRC channel on irc.freenode.net.

### Weekly Status Meetings

The jQuery Core team has a weekly meeting to discuss the progress of current work. The meeting is held on the [matrix.org platform]([matrix.org platform](https://matrix.to/#/#jquery_meeting:gitter.im)) at [Noon EST](https://www.timeanddate.com/worldclock/fixedtime.html?month=1&day=17&year=2011&hour=12&min=0&sec=0&p1=43) on Mondays.

[jQuery Core Meeting Notes](https://meetings.jquery.org/category/core/)

## How to Report Bugs

### Make sure it is a bug in the project

Most bugs reported to our bug tracker are actually bugs in user code, not in jQuery code. Keep in mind that just because your code throws an error inside of jQuery, this does *not* mean the bug is a jQuery bug.

Ask for help first in a discussion forum like [Stack Overflow](https://stackoverflow.com/). You will get much quicker support, and you will help avoid tying up the jQuery team with invalid bug reports.

### Disable browser extensions

Make sure you have reproduced any bugs that occur in a browser with all browser extensions and add-ons disabled, as these can sometimes cause things to break in interesting and unpredictable ways. Try using incognito, stealth or anonymous browsing modes.

### Try the latest version

Bugs in old versions of jQuery may have already been fixed. In order to avoid reporting known issues, make sure you are always testing against the [latest build](https://releases.jquery.com/git/jquery-git.js). jQuery and jQuery UI are very stable libraries, and we try to avoid making breaking changes. If you find a bug in the latest version, it is likely to be a real bug.

### Simplify the test case

When experiencing a problem, [reduce your code](https://webkit.org/quality/reduction.html) to the bare minimum required to reproduce the issue. This makes it *much* easier to isolate and fix the offending code. Bugs reported without reduced test cases take on average 9001% longer to fix than bugs that are submitted with them, so you really should try to do this if at all possible.

### Search for related or duplicate issues

Go to the GitHub issue tracker for the project and make sure the problem hasn't already been reported. If not, create a new issue there and include your test case.

## Specific Projects

Refer to the appropriate GitHub repository's CONTRIBUTING.md for specific details on how to contribute to that project.

- [jQuery](https://github.com/jquery/jquery/blob/main/CONTRIBUTING.md)
- [jQuery UI](https://github.com/jquery/jquery-ui/blob/main/CONTRIBUTING.md)

Contributions to jQuery Mobile are no longer accepted.

Contributions should usually be made in the form of a pull request. Find more information on how to contribute to jQuery projects at [contribute.jquery.org](https://contribute.jquery.org).