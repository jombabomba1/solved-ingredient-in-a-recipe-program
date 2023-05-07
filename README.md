Download Link: https://assignmentchef.com/product/solved-ingredient-in-a-recipe-program
<br>
Many recipes tend to be rather small, producing the fewest number of servings that are really possible with the included ingredients. Sometimes one will want to be able to scale those recipes upwards for serving larger groups.

This program’s task is to determine how much of each ingredient in a recipe will be required for a target party size.

The first inputs to the program will be the recipe itself.

Here is an example recipe that comes from the story “Chitty Chitty Bang Bang”, written by Ian Fleming, who is much better known for introducing the world to James Bond:

This is a recipe scaler for serving large crowds!

Enter one ingredient per line, With a numeric value first.

Indicate the end of input with an empty line.

4 tbsp cocoa

1/4-pound butter

2 tsp corn syrup

can evaporated milk

1 tsp Water

Here is the recipe that has been recorded

4 tbsp

pound

tsp

can

tsp

cocoa

butter

corn syrup

evaporated milk

water




Attractive user-friendly output is rather straightforward, with the help of Python’s string formatting features.

User-friendly input is a little trickier, so here is a peek at a little of the instructor’s code:

First trick:

The name of an ingredient might be more than one word. This will place all of the extra words into a single string

variable ‘item’:

quant, unit, item

Second trick:

= line. split(‘

* pull off at most 2 words fron the front

Sometimes the measure will be fractional. We can tell that if there is a slash in there. Not having a slash can be  treated the same way as a fraction with a denominator of 1.

if ‘/’ in quant:

nuner, slash, dene quant.partition( • i’)

set the parts of the fraction

The rest is left up to the student since this is a string operation and this fraction represents a number.

Extra Credit Option

No doubt the output seems to be a little strange to ask for 2/4 pounds of butter.

better to ask for 1/2.

Modify the program so that all fractions are reduced to their lowest terms.

Also, express all improper fractions (where the numerator exceeds the denominator) as mixed fractions.

Scaling