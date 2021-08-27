# Recipes I Dig
Collection of recipes I've fallen in love with over the years.

## Common Restrictions
The following information is called out in each recipe:

* dairy
* eggs
* nuts
* seeds
* wheat gluten
* added sugar
* meat
* seafood

In many cases, allergen-free ingredients can be substituted (such as butter vs vegan butter, wheat flour vs. gluten free flour, etc.).

## Searching Recipes
You can use `grep` to search through recipes on the command line (using a Terminal application).

To find recipes that contain `dairy`:

```
grep -l 'dairy' *
```

To find recipes that do not contain `dairy`:

```
grep -l -v 'dairy' *
```

To find recipes that are vegan (no eggs, no dairy):

```
egrep -w -l -v 'dairy|eggs' *
```
