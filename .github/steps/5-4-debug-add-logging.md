### :keyboard: Activity: Debugging - Add Logging

In this step, you'll use GitHub Copilot's Agent mode to add logging to some preexisting code to enable better debugging in future steps.

1. Open the **Copilot** chat panel, switch to **Agent** mode and **Claude 3.7 Sonnet** model using the dropdown menus.

2. Attach the following files to the GitHub Copilot Chat context window to include for code refactoring
   1. `file1.js`
   2. `file2.js`
   3. `file3.js`

3. Use the following prompt to ask Copilot to refactor the code for improved logging:
   > ![Static Badge](https://img.shields.io/badge/-Prompt-text?style=social&logo=github%20copilot)
   >
   > ```prompt
   > Refactor my code in the attached files by adding logging to help with debugging and code maintainability.
   > ```
   
4. Run the application with `npm run start` in the root directory to test the functionality.

### Success Criteria

To complete this exercise successfully, ensure that:
   - Code changes are commited to the `feature/code-refactoring` branch.
   - More console logging is added for the specified files.

If you encounter any issues, you can:
- Double check that the pushed branch is called `feature/code-refactoring`
- Ask Copilot to fix specific problems