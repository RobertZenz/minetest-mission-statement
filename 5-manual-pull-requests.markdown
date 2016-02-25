How to handle pull requests
===========================


0. Purpose of this document
---------------------------

The purpose of this document is to provide a manual on how to handle
pull requests in an efficient manner which:

 * simplifies handling of pull requests
 * improves and eases management for the core developers
 * improves feedback to the contributor
 * shortens the amount of time necessary to review and merge it


1. Current process
------------------

The current process is as described below:

 1. an initial categorizing is done by adding appropriate tags
 2. core developers are reviewing the pull request as their time permits
 3. after accumulating two approvals from core developers, the pull request is
    merged as time permits

This process lacks in several areas:

 * the timespan in which the pull request is handled is undefined
 * there is no one assigned to the pull request, making it hard for
   the contributor to see who is the responsible contact
 * there is no clear indication if the pull request is approved
 * there is no process to make sure that pull requests are handled at all

These shortcomings require quite a lot of interaction from the contributor and
have the potential to confuse and frustrate the contributor in the worst case.


2. A team consisting of core developers
---------------------------------------

A team on GitHub should be created which contains only these developers which
the right to review and approve pull requests. This removes any ambiguity who
is allowed to approve pull requests.


3. A new set of tags
--------------------

Introducing a new set of tags can improve the process signigicantly:

 * `reviewed`, which indicates that the pull request has been reviewed by
   one core developer
 * `approved`, which indicates that the pull request has been reviewed and
   approved by two core developers
 * `merging`, when a core developer is working on merging the approved pull
   request

This improves the feedback provided to the contributor as it is always visible
in what state the pull request currently is. Additionally this allows the core
developers to quickly and easily query for pull requests which need their
attention.


4. Assign people
----------------

Together with the intial categorization the core developers whose area of
expertise the pull request falls into should be assigned to the pull request.
This allows the contributor to see who is the contact if there are any questions
or if any confusion arises. The core developers can easily query their pull
requests and see their status.

Additionally, the person doing the merge should assign themselves to
the pull request when they are about to merge it, to provide additional
feedback.


5. Assign milestones
--------------------

As with features, pull requests should be assigned milestones. This does make
sure that pull requests are handled and also improves the feedback to
the contributor.


6. Getting work done
--------------------

Currently the process of which pull requests receives attention is undefined,
the previous suggestions will make it easy for core developers to discover
pull requests which need their attention. However, this must be done by
the developers on a regular basis.

Ideally, pull requests which are in progress would receive the highest
attention, as these carry the most momentum from both, the developers and
the contributors.

