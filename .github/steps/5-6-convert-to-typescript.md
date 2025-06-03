### :keyboard: Activity: Large Refactoring - Convert to TypeScript

In this step, you'll use GitHub Copilot's Agent mode to convert part of the codebase to utilizing typescript which will be built into the app.

1. Open the **Copilot** chat panel, switch to **Agent** mode and **Claude 3.7 Sonnet** model using the dropdown menus.

2. Attach the following files to the GitHub Copilot Chat context window to include for code refactoring
   1. `packages/frontend/src/components/ItemDetails.js`
   2. `packages/frontend/src/utils/ItemService.js`
   3. `packages/backend/src/controllers/ItemDetailsController.js`

3. Use the following prompt to ask Copilot to refactor the code to use TypeScript:
   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > I want to introduce TypeScript into my codebase. 
   > 
   > I want my `npm run start` for both my frontend and backend to still function once some or all of my codebase is converted to TypeScript.
   >  
   > Refactor my code in the attached files to use TypeScript and ensure TypeScript compiler allows for JavaScript for all the other untouched JavaScript source files in my backend and frontend codebases.
   > ```
   
4. Run the application with `npm run start` in the root directory to test the functionality.

### Success Criteria

To complete this exercise successfully, ensure that:
   - Code changes are commited to the `feature/code-refactoring` branch.
   - The specified files are convert to TypeScript files now.

If you encounter any issues, you can:
- Double check that the pushed branch is called `feature/code-refactoring`
- Ask Copilot to fix specific problems