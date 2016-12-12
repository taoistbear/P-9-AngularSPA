# Treehouse Full-Stack Techdegree Projectc 8
## Build a single page application using Angular.js

### Project Instructions
- [ ] Create an app AngularJS module that declares ngRoute as a dependency and update the provided index.html file so that AngularJS bootstraps your application.
- [ ] Create a dataService AngularJS service that calls into the provided Node.js REST API. __See Treehouse Documentation__
- [ ] Set up routes for the "Recipes" and "Recipe Detail" screens by opening the route-config.js file (located in the scripts folder) and uncommenting the commented out code.
- [ ] Create a RecipesController AngularJS Controller that provides the business logic for the recipes.html template.
- [ ] Update the RecipesController controller to satisfy the following user requirements:
    - [ ] As a user, I should be able to select a category on the "Recipes" list screen to filter the list of recipes by that selected category.
    - [ ] As a user, I should be able to click on a recipe row or on the row's "Edit" link to view the details for that recipe using the "Recipe Detail" screen.
    - [ ] As a user, I should be able to click on a recipe row's "Delete" link to delete that recipe.
    - [ ] As a user, I should be able to click the "Add Recipe" button to add a new recipe using the "Recipe Detail" screen.
- [ ] Update the provided recipes.html template with AngularJS ng directives. __See Treehouse Documentation__
- [ ] Create a RecipeDetailController AngularJS Controller that provides the business logic for the recipe-detail.html template.
- [ ] Update the RecipeDetailController controller to satisfy the following user requirements:
    - [ ] As a user, when adding or updating a recipe, I can provide the following values:
        - [ ] Name (text box)
        - [ ] Description (multi-line text box)
        - [ ] Category (select list)
        - [ ] Prep Time (text box)
        - [ ] Cook Time (text box)
    - [ ] As a user, I should be able to add one or more ingredients and steps to a recipe.
    - [ ] As a user, when adding an ingredient to a recipe, I can provide the following values:
        - [ ] Item (select list)
        - [ ] Condition (text box)
        - [ ] Quantity (text box)
    - [ ] As a user, when adding a step to a recipe, I can provide the following values:
        - [ ] Description (text box)
    - [ ] As a user, I should be able to see any errors that the REST API returns when I save a recipe.
- [ ] Update the provided recipe-detail.html template with AngularJS ng directives. __See Treehouse Documentation__
- [ ] Wrap all of your JavaScript application, controller, and services code in immediately invoked functions in order to prevent from polluting the global namespace.

### Extra Credit
- [ ] Instead of defining properties and functions directly on the AngularJS $scope object, use the "controller as" syntax. The provided AngularJS routes are already configured to expose controller properties and functions via the vm scope property.
- [ ] As a user, I should be asked to confirm a recipe deletion before it is deleted.
- [ ] Provide a global error handler that displays error messages in a popup window when unhandled errors occur.
- [ ] Write unit tests for either the RecipesController or RecipeDetailController AngularJS controllers.
- [ ] Add code comments using JSDoc syntax.

## **For any additional info... Review TD Project Page!
