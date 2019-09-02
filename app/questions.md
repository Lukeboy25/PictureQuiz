1. What does the abbreviation ART stands for?
Android Runtime

2. What is Android Jetpack?
It's a suite full of libraries, tools and guidance to help us write high-quality apps. 

3. Describe the difference between the fixed, wrap_content and match_constraint setting of the constraint layout?
- wrap_content:
gives only the included content plus the extra padding of it.
- match_constraint:
with the corresponding left/right or top/bottom constraints being set to "parent".
- fixed:
fixed will give you a established height and width that stays at the same place.

4. What does the abbreviation DP stand for and why do we need them?
Density independent, it's to make resolution and display size compatible to work with.

5. What is the purpose of the string.xml file?
It's for the translations of different kind of languages.

6. Why is the layout in Android specified by .xml files?  Why not just have the layout in the code (Kotlin or Java)?
The xml build up the files easily with an design.
To leep layout and code separated from each other.

7. In the level 1 example the following code was used: btnConfirm   .setOnClickListener What is a listener and what is the underlying design pattern?
The listener is watching for the click that is going to happen, then an action will happen. It's a server pattern.  