A guide to gauging features
===========================


0. Purpose of this document
---------------------------

The purpose of this document is to provide a guide on how to gauge features
whether they belong in Minetest or not. Though, by the very definition of
the subject, it is impossible to provide a comprehensive and exact manual,
instead this document tries to outline a common approach on how to evaluate
features and provide a good foundation for further discussion if necessary.


1. Consider the mission statement
---------------------------------

There is a very simple question which can be asked for every feature:

 > Does it help with achieving the goal of Minetest?

And if in doubt asking the opposite question might help:

 > Does it hinder achieving the goal of Minetest?

If the second answer can be answered with "no" there is a good chance that
having the suggested feature is a good idea. Additionally there is a question
which should also weigh heavy:

 > Does somebody want the feature?

If somebody wants a feature and maybe even writes it themselves, there is a good
chance that this feature is also desired by others and will ultimately help
with achieving the goal.


2. Flexibility
--------------

For Minetest to be flexible it requires features and these features must
be flexible. So an additional question that can be asked is:

 > Can it be configured?

Though, this question doesn't necessarily make sense for every feature to be
asked, but raising the question might actually show that it might benefit from
being configurable by either the modder or user.

Additionally one can ask themselves:

 > What else might this feature be used for?

For example, the tree spawner is not limited to trees, even though it might
be designed to spawn trees it can easily be used to spawn completely different
structures.


3. One-size fits all
--------------------

There is no difference between features for modders, users or both. All features
can be judged by the simple questions above. For example shaders, they do not
directly help with achieving the mission statement, but do also not hinder it,
they can be configured by the user and many people want it. So the choice if
the feature is used (and how) is actually not upon the developer, but upon
the user.


4. Having a lot of features is not bad
--------------------------------------

This is a contentious point, but everyone will agree that a software which does
not offer features will not be used. On the other hand, offering many features
can quickly lead to the opinion that the software is bloated, complicated or
both. So it is important that features actually stay out of the way until they
are wanted or required. Providing many features is not a bad thing, providing
many features which are somehow required or interleave with each other is a bad
thing.

Having a feature rich engine means that it offers all the features which might
be required, and also has the cleanliness that all these not needed features
stay out of the way until they are required. The developer should not even need
to know that these features exist if they don't use it.

