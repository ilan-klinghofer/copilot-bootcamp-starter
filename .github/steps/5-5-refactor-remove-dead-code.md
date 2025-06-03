### :keyboard: Activity: Refactoring (part 2 - remove dead code)

In this step, you'll use GitHub Copilot's Agent mode to refactor some preexisting code by removing some dead code. This completes the refactoring process by cleaning up unused code after the parameter simplification.

1. Open the **Copilot** chat panel, switch to **Agent** mode and **Claude 3.7 Sonnet** model using the dropdown menus.

2. Attach the following files to the GitHub Copilot Chat context window to include for code refactoring
   1. `packages/frontend/src/components/ItemDetails.js`
   2. `packages/frontend/src/utils/ItemService.js`
   3. `packages/backend/src/controllers/ItemDetailsController.js`

3. Use the following prompt to ask Copilot to refactor the code for removing dead and unused code:
   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > Refactor my code in the attached files by removing dead and unused code.
   > ```
   
4. Run the application with `npm run start` in the root directory to test the functionality.

### Success Criteria

To complete this exercise successfully, ensure that:
   - Code changes are commited to the `feature/code-refactoring` branch.
   - All dead code is removed for the specified files.

If you encounter any issues, you can:
- Double check that the pushed branch is called `feature/code-refactoring`
- Ask Copilot to fix specific problems