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
1. **Unique Identifier (id)**: Ensure each recipe has a unique numerical identifier in the incremental order it is going to be stored in.

2. **Name (name)**: Provide a clear and concise name for the recipe.

3. **Cuisine (cuisine)**: Specify the cuisine type (e.g., Italian, Indian, Japanese, Chinese).

4. **Ingredients (ingredients)**: List all ingredients as strings in an array.

5. **Instructions (instructions)**: Write step-by-step cooking instructions.

6. **Calories (calories)**: Include the approximate calories for the entire recipe.

7. **Duration (duration)**: Indicate the total time it takes for cooking.

## How to submit
- Fork this repository.

- Add your recipe to the recipes array in data.json.

- Create a pull request with a clear title and description.

*Thank you for contributing!*