# Course website for Open Source Software Development at NYU


This repository contains code and content for a website for one of the courses
that I teach. Tt is setup as an open source project so that the students taking the course can exercise the process of the open source contributions without the pressure of dealing with a _real world_ project. 



## Contributions

Contributions are generally accepted only from students taking the course.

The general workflow is: 
- someone posts an issue, 
- other people comment on that issue (may or may not happen)
- someone claims that issue, fixes it and makes a pull request, 
- the original poster and people who commented should verify that the issue is an actual fix. 

Again, because this is really a course exercise, the person reporting an issue, should be different from the person fixing that issue. 

### Reporting Issues

- As you are exploring the course website, take a note of any problems, inconsistencies, broken links, misformatting, etc.
- Once you discover a problem, go the the course
website repository and look through the existing issues.
- If the issue that you found has not been reported yet, report it.
Provide a detailed description of the problem (when it occurs, why you think it
is a problem), state which browser and operating system (name and version)
you are using.
- If the issue has been reported, you can comment on it. If nobody verified it
before, you can add a comment stating that you have also encountered the issue (if such a comment adds some value to the issue report).
If other people already verified it, but you have additional details to add, you
can do that as well. You can also suggest a solution, if you think
that you know how to solve it.
- If you find reported issues that are not really issues, you can contribute that to the discussion.



__You should pay close attention to the issues that you reported and commented on.__
Other people may ask follow-up questions and suggest modifications to the issue.
Eventually, someone may provide a fix to an issue and you should be able
to verify quickly that their fix actually works and that it fixes the issue.
You should respond to all such comments and requests in a timely manner (i.e.,
a couple of days, not weeks).


### Claiming Issues

If you want to fix an issue, you should first claim it. Add a comment to
one of the issues that you would like to fix. The comment should basically state 
"I would like to claim this issue." or "I'd like to work on this.", or ...

Make sure that you wait for the response before you start working on the issue!


__Restrictions__<br> You will not be assigned to fix an issue that you reported yourself.
For that reason, there is no point in claiming an issue that you reported.

It may be a good idea to claim issues that have not been claimed before since we will use "first come first serve" rule in assigning the issues (with minor exceptions at our discretion).


### Fixing Issues

You should not work on an issue that you were not assigned. Pull request from contributors who did not successfully claim the issue will be rejected.


Attempt to fix the issue and submit a pull request.
You should make a fork of the existing code and make and test all the changes
that you are proposing in that fork repository. If you enable github pages
for that repository, then you can verify that the issue that was reported is actually
fixed and that your fix did not break any other parts of the website. Make sure that
you carefully read the report of the issue and all/any follow-up discussion. Your fix
should implement exactly what was agreed on (do not include fixes to other issues,
or fixes to other unreported problems).


Issue a pull request. In the pull request you should ask the original poster of the issue
and (optionally) the people who commented on the issue to verify that the fix
is acceptable to them. Provide a link to your fork that stores a functional website with
your changes. <br>
If there are merge conflicts when you issue a pull request (or if any merge conflicts arise after you
issued the pull request, but before it was merged), you HAVE to resolve
them before the pull request can be accepted.

- use @USERNAME to mention particular users (people who reported an issue)
- use "Resolves #NUM" where the NUM is the issue number, so that when the pull
request is merged, the issue is automatically marked as resolved


Make sure that you pay close attention to the pull request until it is rejected or merged.
The maintainers and/or original posters may ask you to make changes and you should
respond to such comments and requests in a timely manner.


As people submit pull requests in order to fix the issues,
the original posters (and anybody else) should be verifying that the fix is really
relevant to the original issue and that it fixes it according to the discussion
for the issue. The author of the pull request should provide the location
of a fork for the website so that people can easily verify it.

As changes are incorporated into the website, there may be new issues coming up.
If you spot a new problem or previously unreported problem, feel free to report it
as a new issue or comment on the previously reported issue.

If an issue is closed and you discover that the problem still exists,
you should  suggest that it is reopened.

If an accepted fix introduces a new problem, report it as a new issue but mention all
other issues and pull request that might be related to this new problem.





