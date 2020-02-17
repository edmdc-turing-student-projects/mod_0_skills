## Lasagna
### Attributes
* name = "lasagna"
* ingredients = ["pasta", "tomato sauce", "veggies", "cheese", "herbs"]
* portionSize = 5
* price = 12.50
* isTodaySpecial = true


### Methods
* mixIngredients = "pastatomatosauceveggiescheeseherbs"
* dividePortion = ["pasta", "tomat", "osauc", "evegg", "iesch", "eeseh", "erbs"]
* reducePrice = (12.50 * .85) = 10.625
* increasePortion = (5 + 2) = 7


Notes on revisions: I removed/replaced any curly braces that did not belong here, kept those that did on other examples. An array is a type of object, in a way, because it is still a key/value pair. The key is assumed to be an integer called an index (begins at 0). The correct syntax uses square brackets, and separates each value with commas.
```javascript
//This retrieves "veggie":
ingredients[2];
```
In an object, the key must be defined (like variable assignments, each key within an object should be unique). The value of each key can be a property (variable) or a method (functions), and are given in curly braces.
```javascript
/* From 'class_1_example_object.md'
This retrieves Johnny's Thursday availability, 3, a pm shift */
availability.thursday;
```     

Additionally, I changed everything to camelCase. For some reason, I thought booleans used snake_case.

 
