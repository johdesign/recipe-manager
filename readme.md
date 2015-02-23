Recipe Manager
==============

Ideally this should be able to take a json library/config file and output the contents to a consolidated web view and/or output the individual recipes to pdf's.


Schema Description
------------------

+ **id**:
    Unique identifier of recipe
+ **name**:
    The common name of the recipe
+ **prepTime**:
    How long will the recipe take to prepare?
+ **cookTime**:
    How long will the recipe take to cook?
+ **yield**:
    How much will this recipe yield?
+ **storageContainer**:
    What storage container is preferred for the prepared recipe?
+ **ingredients**:
    What are the ingredients, they need to be listed with the name of the ingredient, the quantity and the unit of measure as separate properties.
+ **preparation**:
    This is an array of the steps require to reproduce the recipe.
+ **attributes**:
    These are like tags, e.g. the dish is
    + spicy
    + vegetarian
    + gluten-free
    + allergen-alert

