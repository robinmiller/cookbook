Recipes
========================================
App made from the lesson at: http://www.learnhowtoprogram.com/lessons/recipes

To run the app:

============================
1. Clone the repo
2. bundle
3. Make sure you have postgres installed and running
4. rake db:create db:migrate db:test:prepare
5. Start a rails server
6. Navigate to localhost:3000

User Stories

=========================================

DONE - As a contributor, I want to post new recipes, so that I can share them with others.

DONE - As a contributor, I want to tag my recipes, so that they are easier to find. (Hint: a recipe has many tags, and a tag has many recipes. Another hint: don't be afraid to create several actions for this: one page for creating tags, one page for creating recipes, one page for adding tags to a recipe.)

DONE - As a cook, I want to choose a tag and see what recipes have that tag.

DONE - As a cook, I want to give a recipe 1 through 5 stars, so that can share with others what I think of a recipe.

DONE - As a cook, I want to see recipes ordered by the number of stars they have, so that I can focus on the best ones.

As a cook, I want to see some new recipes mixed in with the highest-rated ones, so that I can give new recipes with no or few ratings a try. (Hint: make a method that creates an arbitrary weighting between the average number of stars a recipe has, and how old it is.)

As a cook, I want to search through recipes, so that I can find something with a particular ingredient or word. (Hint: use the Textacular gem.)
