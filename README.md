# Bank Branch Singleton

This code implements a singleton pattern for managing bank branch instances in JavaScript.

# File Structure:

* index.html: This is the main HTML file where the content of the webpage is structured.
* index.css: This is the CSS file containing the scripts for the webpage.
* index.js: This is the JavaScript file containing the scripts for the webpage.

# How to use 

* Create a Singleton Instance:
- The variable `bankBranchInstance` is used to store the singleton instance of the bank branch.

* BankBranch Class:
- `BankBranch` class is defined for managing branch information.
- It containes a constructor that takes `branchInfo` as a parameter.

# Constructor:
* Checks if `bankBranchInstance` variable is null.
* If `bankBRanchInstance` is null, it creates a new instance with the provided `branchInfo`.
* Assigns the new instance to the `bankBranchInstance` variable.
* Returns `bankBranchInstance`, whether it's newly created or existing.