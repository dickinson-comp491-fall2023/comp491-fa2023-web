# COMP491 Assignment HW5: Bug Gardening

This assignment is worth 60 points and is expected to take about six
hours: roughly two hours per bug, per student investigating. Most of the
work can be done as a team, in pairs, or individually. Log your
activity on the Slack live log.

## Introduction

**Bug gardening** is a name often given to the task of maintaining the issue tracker in a project. This name reflects the fact that without careful attention, issue trackers tend to become disorganized - like an overgrown garden. They will accumulate tickets that are unlabeled, redundant/duplicates, inaccurate, or describe bugs that no longer exist in the current version of the software. Bug gardening thus includes actions such as assigning tags and/or priorities to tickets, confirming the existence of reported bugs, requesting additional information on submitted tickets, adding useful information to existing tickets, eliminating duplicate tickets, connecting potentially related tickets, closing completed or out of date tickets, etc. While some of these activities are done by the maintainers (e.g. prioritizing, deleting or labeling tickets) many others can be done by the community.

## Assignment

In this assignment you will engage as part of your project's community by doing some bug gardening. More specifically you will:
- Develop an understanding of your project's process for dealing with bugs/issues.
- Help with the maintenance of your project's issue tracker by bug gardening.

### Getting Started

For this activity, there will be a number of deliverables that will be collectively produced by your project team and posted to the team wiki page.

* Create a new wiki page, linked from your team wiki page. The new
  page should be titled "Bug Gardening".

All team members will be adding information to your Bug Gardening wiki
page throughout the activity. It is the responsibility of all team
members to keep your team's wiki pages well organized and nicely
formatted.

### Collecting the Project's Bug Information

Most H/FOSS projects have an *issue tracker*. (If your project does
not have an issue tracker, please discuss with the instructor to make
alternative arrangements for this assignment.)  In addition to the
issue tracker, many projects also have resources (documents,
communication channels, etc.) that describe the processes and
expectations for reporting/triaging/fixing issues.

- Find and read all of the bug/issue related resources that your
  project provides. Be sure to find the issue tracker itself, guides
  on how to report a new issue/bug (e.g. what information to include
  or how to format the ticket), information about how developers claim
  tickets on which they plan to work, and how bug/issue fixes are
  contributed back to the project (e.g. how to make a pull request).
- Create a heading of "Bug Resources" on your team's Bug Gardening
  wiki page.
- As a team, create an annotated list of all of the useful
  bug/issue-related resources that you found.  Each entry should
  contain a link to the resource and a sentence or two describing what
  the resource is.
- Spend a few minutes doing online research about what makes a good
  bug report. Chapters 12 and 14 of our textbook discuss bug reports,
  so we will come back to this later in the semester.

### Gardening for "Suspect Tickets"

In this part of the activity you will try to help your project by
doing some bug gardening. Specifically you will investigate *suspect
tickets* in the issue tracker for your project. A suspect ticket is
one that is still open (i.e. has not been closed) but that may not
actually exist in the current version of the product. Suspect tickets
can arise in a variety of ways. Someone may simply have forgotten to
close the ticket, someone may have re-discovered and fixed the issue
while working on another ticket, or the relevant features may have
been eliminated from the product.

To identify suspect tickets, you might look at old tickets, tickets
with version numbers that do not match the current version of the
product, and older tickets marked as low priority. Any information
that you were able to identify earlier about how the project handles
issues may also help in finding suspect bugs. For example, if the
project uses an in-progress tag for tickets undergoing active work, a
ticket tagged in-progress that hasn't been updated in a long time
might be suspect. The best suspect bugs to investigate will be those
with a detailed list of steps for replicating a bug. If you have
trouble identifying suspect tickets, you might reach out to the
community and explain (briefly) what you are trying to do. They may
then have suggestions for how to identify suspect tickets in the
project or suggestions for other related things you might do to help
maintain the issue tracker. If the community has other suggestions,
please discuss them with the course faculty to possibly arrange
alternative criteria for this assignment.

The total number of suspect tickets investigated must be three per team member. You can work individually, in pairs, or in larger groups.

#### Reporting "Suspect Tickets"

All of the suspect bugs investigated by the team should collected
together and documented under the heading "Suspect Tickets" on your
team's Bug Gardening wiki page.

This section of the wiki page should include a table with one row for each suspect ticket. The information in this table should be brief. The sample table below shows the required columns, gives a short explanation of each column and a few sample rows:

| __Bug ID__	| __Members__ | __Description__ | __Why Suspect__ | __Exists__	| __Actions__ |
|-------------|-------------|-----------------|---------------------|-------------|-------------|
| _The identifier for the bug as a live link into the project's issue tracker_ | _Initials of the team members investigating this issue_ | _A short description of the issue in your own words_ | _A short explanation of why you found the issue suspect_ | _Yes if you were able to confirm existence of the issue in the latest version. No, if you were were able to confirm it does not exist. Uncertain, if neither yes or no. Also include brief explanation for your answer._ | _Description of any action taken on the bug. If you comment on the ticket or elsewhere, include live links that document your actions._ |
| [1234](http://example.com/link1234.html) | GB/XY| Deposit field allows negative amounts. |	Ticket dated 2008, latest version released 2016. |	No. Followed steps in ticket to reproduce and negative amount was rejected. |	Commented on the ticket [here](ttp://example.com/sample.html) suggesting that it be closed. |
| [X5432b](http://example.com/linkX5432b.html) | 	GB/XY	| UI is unresponsive when sorting data.	| Ticket posted for version 1.3, latest product version is 2.7.	| Yes. Confirmed unresponsiveness when sorting the very large test data set.	| Commented on the ticket [here](ttp://example.com/sample.html) indicating problem was seen in Version 2.7 using the large test data set, but was not noticeable with the small test data set. |
[AB392c](http://example.com/linkAB392c.html) | JM/PQ | Program crashes on dates before 1970.	| Ticket dated 2010, had lots of comments and but no resolution.	| Uncertain. | We were unable to replicate bug because steps for replication were incomplete/unclear with regard to the latest version. Conversed with community [here](ttp://example.com/sample.html) about the issue. Commented on the ticket [here](ttp://example.com/sample.html) with clarified steps. |
| [9876](http://example.com/link9876.html) | JM/FS | About dialog gives incorrect copyright year. |	Ticket dated 2020, but good first issue tag suggests it should be easy to fix. |	Yes. Followed steps in ticket to reproduce and copyright is still incorrect. |	No action taken. |

Example code of an nWiki table with the above structure is provided in the "fake team 1" bug gardening page on our course wiki.

If members of your team happen to identify a new issue that does not
already appear in the issue tracker, you may open a new ticket for that
issue in lieu of one of the suspect issues. The corresponding row in
the table above should link to the new ticket and describe the issue.
If you go this way, be sure to do a thorough search of the issue
tracker before reporting a new issue.

## Submission

All outputs of this assignment are recorded on your team wiki pages as described above.

## Rubric

A good grade can be achieved by: following all instructions
accurately; producing material that reflects about six hours of effort
per student for this assignment (with evidence of time spent on the
Slack live log); employing correct grammar, effective design, and
clear presentation of concepts on the relevant wiki pages. For an
excellent grade, some evidence of additional research, insight, or
thoughtfulness may be required.


## Acknowledgements

This assignment was authored by Professor Braught with minor changes
by John MacCormick.  It builds from and adapts ideas and content from
the following activities created by others:
- http://foss2serve.org/index.php/Bug_Gardening
- http://foss2serve.org/index.php/Bug_Selection
- http://foss2serve.org/index.php/Research_Bug_Activity
- http://foss2serve.org/index.php/Solving_A_Bug
- http://foss2serve.org/index.php/Writing_a_bug_report
