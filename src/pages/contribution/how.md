---
templateKey: docs-template
path: /contribution/how
title:
---
<div class="HowToContirbute">

# How to contribute
There are multiple ways you can contribute to the project. And help is always welcome! All details can be found on the contributing page. Keep reading for a quick overview!

## Becoming a Committer
If you are interested in the project and looking for ways to help, consult the list of tasks in JIRA, or ask the mailing list.

## Contributing by Helping Other Users
A great way to contribute to AGE is to help answer user questions on the mailing list or on StackOverflow. There are always many new AGE users; taking a few minutes to help answer a question is a very valuable community service.

Contributors should subscribe to this list and follow it to keep up to date on what's happening in AGE. Answering questions is an excellent and visible way to help the community, which also demonstrates your expertise.

## Contributing by Reviewing Changes
Changes to AGE source code are proposed, reviewed, and committed via Github pull requests (described in Developer Guidelines). Anyone can view and comment on active changes here. Reviewing others' changes is a good way to learn how the change process works and gain exposure to activity in various parts of the code. You can help by reviewing the changes and asking questions or pointing out issues as simple as typos or small issues of style.

## Contributing Documentation Changes
To propose a change to release documentation (that is, docs that appear here), edit the Markdown source files in the right branch on the Age website repository. The documentation will be build automatically after the changes have been merged.

## Contributing Bug Reports
Ideally, bug reports are accompanied by a proposed code change to fix the bug. This isn't always possible, as those who discover a bug may not have the experience to fix it. A bug may be reported by creating a JIRA issue but without creating a pull request.

Bug reports are only useful, however, if they include enough information to understand, isolate and ideally reproduce the bug. Simply encountering an error does not mean a bug should be reported; search JIRA and inquire on the AGE user / dev mailing lists first. Unreproducible bugs, or simple error reports, may be closed.

The more context the reporter can give about a bug, the better, such as: how the bug was introduced, by which commit, etc. It assists the committers in the decision process on how far the bug fix should be backported, when the pull request is merged. The pull request to fix the bug should narrow down the problem to the root cause. Data correctness/data loss bugs are very serious. Make sure the corresponding bug report JIRA issue is labeled as correctness or data-loss. Please send an email to dev@age.apache.org after submitting the bug report, to quickly draw attention to the issue. Performance issues are classified as bugs. The pull request to fix a performance bug must provide a benchmark to prove the problem is indeed fixed.


## Contributing to JIRA Maintenance
Most contributors can directly resolve <a href='https://issues.apache.org/jira/projects/AGE2/issues/' target="_blank">JIRA issues.</a> Use judgment in determining whether you are confident the issue should be resolved (although changes can be easily undone). When resolving JIRA tickets, please observe the following conventions:

When resolving JIRA tickets, please observe the following conventions:

* Resolve as Fixed if there's a release or code commit that resolved the issue.
  * Set Fix Version(s), if and only if the resolution is Fixed
  * Set Assignee to the person who contributed the most to its resolution, usually the person who opened the PR that resolved the issue.
* For issues that can't be reproduced against master as reported, resolve as Cannot Reproduce.
* If the issue is the same as or a subset of another issue, resolved as Duplicate
  * Mark the issue that has less activity or discussion as the duplicate.
  * Link it to the JIRA ticket it duplicates.
* If the issue seems clearly obsolete and applies to issues or components that have changed radically since it was opened, resolve as Not a Problem
* If the issue doesn't make sense or is not actionable resolve as Invalid.
* If it's a coherent issue, but there is a clear indication that there is no support or interest in acting on it, then resolve as Won't Fix.

<b>Searching JIRA</b> How to search JIRA for existing issues:

1. Basic:
    1. Visit <a href='https://issues.apache.org/jira/projects/AGE2/issues/' target="_blank"><b>AGE JIRA</b></a>
    2. Type query into search box in top right (beware this will return results from all projects)
<br />

2. Advanced:
    1. Visit <a href='https://issues.apache.org/jira/issues/?jql=project%20%3D%20%22Apache%20AGE%22' target="_blank">AGE JIRA Advanced Search</a>
    2. Replace the empty quotes with quoted text (such as "cypher")
<br />

</div>
