---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - shell
  - ruby
  - python
  - javascript

includes:
  - errors

search: true
---

# More-recipes API Documentation

Welcome to the More Recipes API! You can use our API to access more-recipes API endpoints, which can get information on various recipes in our database.

# Recipes

## Get All recipes

```javascript
https://more-recipes-application.herokuapp.com/api/v1/recipes
```

> The above command returns JSON structured like this:

```json
{
    "recipes": [
        {
            "id": 1,
            "recipeImage": null,
            "recipeQuantity": 1,
            "recipeIngredient": "tomatoes",
            "recipeDirection": "Pour the chicken stock and the tomato stew into a sizeable pot and leave to boil."
        }
    ],
    "error": false
}
```

This endpoint retrieves all recipes.

### HTTP Request

`GET https://more-recipes-application.herokuapp.com/api/v1/recipes`
