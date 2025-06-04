### :keyboard: Activity: Debugging (part 1 - Add Logging)

In this step, you'll use GitHub Copilot's Agent mode to add logging to some preexisting code to enable better debugging in the next step. This logging infrastructure will help identify issues when we fix runtime errors.

1. Open the **Copilot** chat panel, switch to **Agent** mode and **Claude 3.7 Sonnet** model using the dropdown menus.

2. Attach the following files to the GitHub Copilot Chat context window to include for code refactoring
   1. `packages/frontend/src/components/ItemDetails.js`
   2. `packages/frontend/src/utils/ItemService.js`
   3. `packages/backend/src/controllers/ItemDetailsController.js`
   4. `packages/frontend/src/App.js`
   5. `packages/backend/src/app.js`

3. :pencil2: In this step you want to get GitHub Copilot to create logging statements to help with debugging the existing errors. :pencil2:
   <details>

   <summary> :warning: Try creating your own prompt before viewing</summary>

      Use the following prompt to ask Copilot to refactor the code for improved logging:
      > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
      >
      > ```prompt
      > Refactor my code in the attached files by adding basic console logging to help with debugging and code maintainability.
      > ```

   </details>
   
4. Run the application with `npm run start` in the root directory to test the functionality.

### Success Criteria

To complete this exercise successfully, ensure that:
   - Code changes are commited to the `feature/code-refactoring` branch.
   - More console logging is added for the specified files.

If you encounter any issues, you can:
- Double check that the pushed branch is called `feature/code-refactoring`
- Ask Copilot to fix specific problems

### Notes

- :bulb: Frequently, GitHub Copilot will attempt to unify the logging strategy and create an abstraction for logging. If this process is taking too long you can update the prompt above to be more specific like `you want to only add console.log statements...`