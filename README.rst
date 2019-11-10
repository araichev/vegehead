Vegehead
**********
Introduction
=============
This is an open-source cookbook and a work in progress.
In compiling it, i set the following requirements.

**Yummy**.
The food should taste great.

**Fast.**
The food should take at most 30 minutes to make, excluding trivial preparation, such as soaking legumes overnight to remove their phytic acid.
I enjoy cooking but don’t want to spend a lot of time doing it.
To fulfill this requirement, many of the recipes below use a pressure cooker.
OK, i cheat here.
Some recipes below, such as the almond rolls, are slightly over time but too good to omit.

**Vegetarian**.
The food should not require the killing of animals.
I like to minimize the animal suffering involved in my meals and going vegetarian is a step in the right direction.
Going vegan is a bigger step that i'm not willing to take at present.

**Pre-industrial**.
The ingredients should be as close as possible to the ones eaten by our pre-industrial ancestors.
That rules out 20th-century edible food-like substances (synthetic flavorings, high-fructose corn syrup, skim milk powder, etc.), food grown with synthetic pesticides, and even canned food because of the shadey chemical linings used in the cans.
I don’t trust that stuff, but i get lazy and use canned tomatoes.

**Grain-free**.
The food should not contain grains: wheat, rice, corn, oats, etc.
I’m eating less carbohydrate these days, and cutting out grains is one simple way to do that.
I’m cutting back on sugars too, which is probably more important health-wise, but i still include some sweet recipes here, such as ice cream.
Mmm, ice cream.


Building the book yourself
============================
- Create a Python 3.7 virtual environment and run ``poetry install``
- Change directory to ``docs`` directory and run ``make singlehtml`` and the Python library Sphinx will work its magic to build the book
- You can then use the `resulting HTML <http://raichev.net/vegehead>`_ as is or print a PDF from it, for example


Contributing
=============
- Learn the basics of `reStructuredText <https://en.wikipedia.org/wiki/ReStructuredText>`_
- Fork this repository
- Add your recipes
- Issue a merge request and wait while i test out your recipes.


Notes
=====
- To deploy, change to the ``docs`` directory, build the docs via ``make singlehtml``, then push with ``ghp-import _build/singlehtml -pnf``.
- Unicode fractions: ⅛, ¼, ⅓, ½, ⅔, ¾.


Changes
========

3.2.0, 2019-11-10
-----------------
- Added the minestrone recipe.


3.1.2, 2019-09-02
-----------------
- Fixed typos in nut butter muffins recipe.


3.1.1, 2019-08-26
-----------------
- Added a testimonial.


3.1.0, 2019-08-21
-----------------
- Added a testimonial.
- Added almond rolls and frylet recipes.
- Removed the lemon curd recipe, because it's not fantastic.


3.0.3, 2019-08-10
-----------------
- Updated pumpkin curry.


3.0.2, 2019-08-05
-----------------
- Updated testimonials.


3.0.1, 2019-08-02
-----------------
- Updated dependencies.


3.0.0, 2019-08-02
-----------------
- Switched to Python 3.7.
- Switched to Poetry.
- Corrected some typos.
- Added some recipes.


2.1.3, 2018-03-30
------------------
- Updated the cook time on the black bean brownies to 40 minutes, which is more accurate and, alas, breaks the Vegehead rules. Still keeping the recipe, though.


2.1.0, 2016-12-27
------------------
- Added Moroccan chili and rhubarb sauce recipes
- Updated license
- Tweaked wording and style


2.0.2, 2015-10-04
-----------------
- Added lemon curd recipe


2.0.1, 2015-04-18
-------------------
- Updated the chocolate recipe
- Updated the license


2.0
------
- Restricted the recipe requirements


1.0
-----
Initial version of a vegetarian cookbook
