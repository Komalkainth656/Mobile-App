# Changes made in the project

# MainActivity.java
1. Removed the clear button, edit text and add button
2. Added Menu and menu click to open the dialog box on click
3. Implemented the interface to get the item name entered

# AddItemFragment
1. This extends DialogFragment
2. AddItemFragment has edittext and button
3. When the button is clicked the text in the edittext is checked and if it is not empty then the value is passed to the MainActivity

# AddItemInterface
1. This has method addItem which has string as parameter

# Drawable
1. ic_baseline_add_24 is added to show the add button

# Menu
Menu Resource created to add the menu in the app