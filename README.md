# FoodSter

an app to lookup recipes.

## User stories

1. As a user, I want to search for recipes, so that I can find new ideas for meals

2. As a user, I want to be able to update the number of savings, so that I can cook a meal for different number of people

3. As a user, I want to bookmark recieps, so that I can review them later

4. As a user, I want to be able to create my own recipes, so that I have them all organized in the same app

5. As a user, I want to be able to see my bookmarks and own recieps when I leave the app and come back later, so that I can close the app safely after cooking.

## Features

1. - Search functionality: input fields to send requests to API with searched keywords
   - Display results with pagination
   - Dispaly recipe with cooking time, servings and ingridients

2. Change servings functionality: update all ingredients according to current number of servings

3. Bookmarking functionaly: display list of all bookmarked recipes

4. - User can upload own recipes
   - User recipes will automatically be bookmarked
   - User can only see their own recipes, not recipes from other users

5. - Store bookmark data in the browser using locak storage
   - On page load, read saved bookmarks from local storage and display.
