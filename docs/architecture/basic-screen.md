# Basic Screens

In Power Apps development, we will usually work with this list of screens

1. Home Screen
2. List/Gallery Screen
3. Form Screen
4. Settings Screen
5. Loading Screen (Optional)

## Variables

Create variables based on their usage and location. For example, if a variable is only used in a single screen, use context variable `UpdateContext({})` to create the variable. When user exits the screen, ensure that the variable is cleared in the `OnHidden` property of the screen.
