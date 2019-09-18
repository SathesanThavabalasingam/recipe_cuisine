# recipe_cuisine
Using NLP methods to classify text 

### Problem 

You've just joined the data team at an online publishing company. One of your verticals is a food publication. A product manager on your team wants to build a feature for this vertical that enables users to query by cuisine, not just by ingredients. Most of your recipes are unlabeled, and it's infeasible to label them by hand. Luckily, you have a small training set of about 10,000 recipes with labeled cuisines.

### Goal

Design and execute a method to predict the cuisine of a recipe given only its ingredients. 

### Data 

`recipes.json`: file containing 39774 individual recipes, each with the following information:

```
{
    "id": unique id for recipe,
    "cuisine": str for 1 of 20 cuisines,
    "ingredients": list containing text
}
```
