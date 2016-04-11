Python Training
===============

This is an exercise to practice what we've learned so far about Python.

Problem
-------

Please write code to model a product hierarchy.

Your model should address these needs:

* Products are grouped into families
* Products may either be a video or an ebook (other types are optional)
* Each product has an ID which is formed from its ISBN and a product type
  abbreviation, for example, "1234567890123.VIDEO"
* Each family has an additional ID which is formed from its ISBN and a
  sentinel product type abbreviation "1234567890123.IP"
* Each product family has a title, but individual products within it may
  override that title
* Ebooks have some number of pages
* Videos last for some number of minutes and seconds

Demo
----

Please create a demonstration of your code by:

* Constructing a product hierarchy with your model for the family below.
* Implement a method on your object that prints a textual representation of
  a product hierarchy for debugging purposes, and call it.

The textual representation should give the name and ID of each product and
family and its title.  A product's title should only be printed if it
differs from the family's title.

Sample Products
---------------

The "Lean Microservices on Rails" family has ISBN 1234567890123.  It has a
video version with ISBN 1234567654321.  It was so popular that its
transcript was developed into its own ebook publication called, "Lean
Microservices on Rails, One Page at a Time."  They are 119:58 and 206 pages
long, respectively.

Suggestions for Learning
------------------------

* Frequently run your code to make sure you're on the right track
* Be prepared to demo what you have.  A partial implementation that runs
  makes more a more convincing demo than a complete implementation that
  doesn't work at all.
* Pair with someone you don't normally work with
* Take turns driving and navigating
* Clone this repo as a starting point and checkin your work as you go
