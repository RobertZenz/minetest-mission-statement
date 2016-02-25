How to handle issues
====================


0. Purpose of this document
---------------------------

The purpose of this document is to provide an overview of how to handle issues
on GitHub, how it is currently done and what may be improved upon that.


1. Current state
----------------

The current state is that incoming tickets are tagged with appropriate tags,
they are comment upon as necessary. There are no people assigned to the issues,
and sparcely are milestones are assigned.


2. Assign people
----------------

Ideally the people into whose area of expertise the issue falls are assigned to
the issue. Not to show that somebody is working on it, but to make sure that
the correct people are notified about changes on the issue, and also that
the developers have an easy way of querying what issues need attention.


3. Assign milestones
--------------------

This is quite a big step, though. Ask the simple questions:

 > Would I like to see this in the next release?
 > 
 > Does it make sense to have this in the next release?

From these answers can be derived if a milestone should be assigned or not.
Ideally this would expand over the current release and one or two releaes into
the future. This should be done rigorously even for issues which get immediately
fixed (as in, a commit was made to fix it).

This will create a clear plan to follow for the release and a complete changelog
of issues which where fixed or implemented in the release.


4. Work through the lists
-------------------------

All these suggestions obviously only work if the developers are working from
time to time through these lists which can be generated from this. But together
with the tags and milestones, the developers have an easy time to see what needs
their attention and what doesn't.

Ideally the developers would check their assigned issues on a regular basis to
make sure that all of these are still relevant.

