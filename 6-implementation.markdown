Implementation
==============


0. Purpose of this document
---------------------------

The purpose of this document is to outline the scheme necessary to implement
the changes outlined in the previous documents.


1. Changes to the repository
----------------------------

The changes in the repository are the easiest to do, the new tags, the teams
and the milestones must be created.


2. Issues
---------

The first, and most likely easiest task is to tackle the issues.

Each and every issue must be looked at, the developers must be added and, where
appropriate, milestones must be set. This can be done by a single developer but
all other developers should work through the generated lists of issues which
they are now assigned to them:

 1. Is this issue still relevant (has it been fixed, is not applicable anymore)?
 2. Is this actually something we want?
 3. Is information missing?
 4. Does somebody else need to be added?
 5. Does it need different tags?
 6. Does it need a milestone?

After that all developers should actually have a good idea of what issues are
in the tracker and what they are up against.


3. Pull requests
----------------

Now the big part are the pull requests.

Again, each and every pull request needs to be looked at, the new tags need to
be added and people need to be assigned. After that the assigned developers must
work through their lists:

 1. Is the pull request still relevant?
 2. Is this something we want?
 3. What's the status, what is missing?
 4. Does somebody else need to be added?
 5. Does it need different tags?
 6. Does it need a milestone?

After that the pull requests need to be handled, plain and simple as that.


4. Doing this regularly
-----------------------

All this previously mentioned actions can only improve the situation if
they are performed on a regular basis. Developers must work themselves through
the list of their issues and pull requests and must check them.

Ideally the workload will drop off after the backlog has been dealed with, which
might or might not take some time. After that the ideal case is that a developer
only has a handful, if at all, pull requests which they must attend to.

The pull requests should be handled in this order:

 1. Active/in progress pull requests should be handled first, as the contributor
    is most motivated in that stage and the momentum should be preserved.
 2. Older pull requests should be looked at again and checked, why are they
    still pending? Is input from the core developers missing? Are changes from
    the contributor missing? Those should be poked at a quite regular basis.
 3. New pull requests should be handled.

Even though new pull requests are quite important, they can be handled last,
as the contributor is already prepared that the initial handling might take some
time. On the other hand a pull request which is dragging on and on has
the potential of losing the contributor, especially if the contributor is
constantly waiting on input from the team.


5. Conclusion
-------------

The current state of the project has accumulated over years and is a result of
many factors. The only way to change that is through, some quite hard, work, and
the most important part is that the issues and pull requests need constant
attention. Once the backlog of pull requests has been dealt with, the required
amount of work will drop off like a cliff, but it will also require constant
work to make sure that such a backlog does never accumulate again.

Theoretically, some of these tasks don't require core developers to do them, for
example the initial tagging and assigning and the merging. These could be done,
additionally to the core developers, by another team which lacks the power to
approve pull requests but is otherwise allowed to merge and change them. This
would allow to split the work required and might actually improve the reaction
time on pull requests.

