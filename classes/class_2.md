## Class="recipe"
### Attributes
* name: (a string data type with the recipe's name)
* ingredients: (a string array with all the ingredients needed for that recipe)
* portionSize: (an integer data type, I will use characters as my unit)
* price: (Float data type with the items cost)
* is_today_special: (boolean value determining if the recipe is "Today's special")


### Methods
* mixIngredients: (makes use of the ingredients array to combine all ingredients)
* dividePortion: (Divides the result of the previous method according to the portionSize)
* reducePrice: (if is_today_special=true, reduces the price attribute of the recipe on menu by 15%)
* increasePortion: (adds 2 to portionSize, for the dinner sized portion)
