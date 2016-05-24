# gurtle
Automatically exported from code.google.com/p/gurtle

Google Code project issue tracker integration for TortoiseSVN & TortoiseGit

Gurtle is a TortoiseSVN/TortoiseGit issue tracker plug-in (an IBugTraqProvider implementation) for projects hosted at Google Code.

With release 1.5, TortoiseSVN (and TortoiseGit later) introduced the possibility for anyone to author a COM-based plug-in that enables a user to query a project's issue tracking system during a commit. Gurtle is such a plug-in and enables the user to consult issues of a project hosted by Google Code from within the TortoiseSVN Commit dialog box. The screenshot below shows how the issue dialog box looks like in Gurtle for the project hosting support project.

http://gurtle.googlecode.com/svn/wiki/SupportIssues.png

When you select one or more issues, Gurtle appends the number and summary of each issue to the commit log message.

Feature Overview

Gurtle's issue browsing dialog box sports the following notable features:

Download of issues in the background
Sort issues by clicking on column headers
Conduct free-text and interactive search along one or across all dispalyed columns
Search issues as download happens in the background
See closed in addition to open issues
Unowned/Unassigned issues appear visually distinct (dimmed)
Closed issues appear visually distinct (struck-out)
Open detail page of an issue in the default Web browser
Notification of version updates
Requirements

TortoiseSVN or TortoiseGit
Microsoft .NET Framework 2.0
Any Windows version where TortoiseSVN and Microsoft .NET Framework 2.0 are supported though most testing has been conducted on Windows XP and Vista.
Internet connection for reaching Google Code
More details
