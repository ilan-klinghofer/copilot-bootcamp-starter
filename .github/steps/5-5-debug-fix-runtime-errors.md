### :keyboard: Activity: Fix runtime errors

In this step, you'll use GitHub Copilot's Agent mode to fix some runtime errors.

1. Open the **Copilot** chat panel, switch to **Agent** mode and **Claude 3.7 Sonnet** model using the dropdown menus.

2. Attach the following files to the GitHub Copilot Chat context window to include for debugging
   1. `file1.js`
   2. `file2.js`
   3. `file3.js`

3. Use the following prompt to ask Copilot to analyze and update the code to fix tje runtime errors:
   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > Fix my code for the following runtime error observed in my browser's console log.
   > ---
   > (paste error here)
   > ---
   > ```
   
4. Run the application with `npm run start` in the root directory to test the functionality.

### Success Criteria

To complete this exercise successfully, ensure that:
   - Code changes are commited to the `feature/code-refactoring` branch.
   - All runtime errors are resolved.

If you encounter any issues, you can:
- Double check that the pushed branch is called `feature/code-refactoring`
- Ask Copilot to fix specific problems