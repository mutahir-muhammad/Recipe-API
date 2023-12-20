# Recipe-API
my Recipe API
An API to share recipes from different cuisines all around the globe.

## Contributing Recipes
We welcome contributions to our recipe collection! 
If you'd like to add a new recipe, please follow these guidelines:
### Recipe Format
Each recipe should be formatted as a JSON object with the following structure:
```JSON
{
    "id": [Unique numerical identifier],
    "name": "[Recipe Name]",
    "cuisine": "[Cuisine Type]",
    "ingredients": [
        "[Ingredient 1]",
        "[Ingredient 2]",
        ...
    ],
    "instructions": "[Cooking Instructions]",
    "calories": [Calories],
    "duration": "[Cooking Duration]"
}
```

### Guidelines
**Unique Identifier (id)**: Ensure each recipe has a unique numerical identifier.

**Name (name)**: Provide a clear and concise name for the recipe.

**Cuisine (cuisine)**: Specify the cuisine type (e.g., Italian, Indian, Japanese).

**Ingredients (ingredients)**: List all ingredients as strings in an array.

**Instructions (instructions)**: Write step-by-step cooking instructions.

**Calories (calories)**: Include the approximate calories for the entire recipe.

**Duration (duration)**: Indicate the total cooking duration.