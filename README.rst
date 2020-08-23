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
To fulfill this requirement, many of the recipes use a pressure cooker.
If you don't have one, then just use a pot and cook for roughly twice as long.
I also cheated: some of the recipes, such as the almond rolls, take slightly longer than 30 minutes to make, but those that do are too good to omit.

**Vegetarian**.
The food should not require the killing of animals.
I like to minimize the suffering involved in my meals, and going vegetarian is a step in that direction.
Going vegan is a bigger step, one that i'm not willing to take at present.

**Pre-industrial**.
The ingredients should be as close as possible to the ones eaten by our pre-industrial ancestors.
That rules out 20th-century edible food-like substances (synthetic flavorings, high-fructose corn syrup, skim milk powder, etc.), food grown with synthetic pesticides, and even canned food because of the shady chemical linings used in the cans.
I don't trust that stuff.
That said, i do get lazy and use canned tomatoes.

**Grain-free**.
The food should not contain grains: wheat, rice, corn, oats, etc.
I’m eating less carbohydrate these days, and cutting out grains is one simple way to do that.
I’m cutting back on sugars too, which is the greater devil, but i still include some sweet recipes here, such as ice cream.
Mmm, ice cream.


Building the book yourself
============================
- Create a Python 3.7+ virtual environment and run ``poetry install``
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
- To deploy, change to the ``docs`` directory, build the docs via ``make clean singlehtml``, then push with ``ghp-import _build/singlehtml -pnf``.
- Unicode fractions: ⅛, ¼, ⅓, ½, ⅔, ¾.
- Good list of food and drink unicode characters `here <https://emojipedia.org/food-drink/>`__.


Changes
========

3.6.0, 2020-08-23
-----------------
- Added aioli recipe.
- Removed mayonnaise recipe.
- Tweaked hummus recipe.
- Tweaked kulfi recipe.
- Reduced water in chana dal recipe.


3.5.1, 2020-07-30
-----------------
- Fixed padding on small screens.
- Tweaked emojis.


3.5.0, 2020-07-29
-----------------
- Rephrased Chickpea Curry.
- Added Banana Kulfi.
- Added sections to separate savory and sweet recipes.


3.4.1, 2020-07-15
-----------------
- Tweaked African Peanut Stew.
- Added a note about pressure cookers in the intro.
- Replaced baking soda with baking powder in Nut Butter Muffins.


3.4.0, 2020-06-30
-----------------
- Added African Peanut Stew.
- Added testimonial from Lewis.


3.3.3, 2020-05-27
-----------------
- Increased the amount of peanut butter in the black bean brownies and edited the text.


3.3.2, 2020-05-21
-----------------
- Fixed missing curry leaf instruction in masoor dal.
- Added more baking soda to the nut butter muffins.


3.3.1, 2020-05-20
-----------------
- Added more water to masoor dal.


3.3.0, 2020-05-15
-----------------
- Added masoor dal recipe.
- Corrected salt instruction in mung dal.
- Added Evania's testimonial.


3.2.2, 2019-12-10
-----------------
- Updated Matt's testimonial.
- Simplified nut butter muffin instructions.


3.2.1, 2019-11-13
-----------------
- Added kombu dicing to the minestrone recipe.


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
