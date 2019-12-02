# AngularTest

Create a page depicting a form designer, where a user can create a custom field from the default field types available and dynamically display a form

# Getting Started

Change directory into angular-test and write the command ng-serve --open
The project will run on the localhost:4200

# Prerequisites

Install Node package 

# Installing

The npm start command builds (compiles TypeScript and copies assets) the application into dist/, watches for changes to the source files, and runs lite-server on port 4200.
Shut it down manually with Ctrl-C.

# And coding style tests
- Three components has been created: 
1. Form component: showed empty table with headers, a preview button and add button.
2. Update Component: Right side of the page and will appear click on the add field button 
3. Preview Component: To display the actual form created.

 1. Unique ID: Randomly generated at the time of creation 
 2. Visible: Boolean flag (decides if the field must be shown or not)
 3. Required: Boolean flag (decides if the field must have value or not)
 4. Order: Number (decides which position the field will be shown) 
 5. Name / Label: text (Label for the field)
 6. Type: Drop Down with all the input field types provided (except radio button). 
 - Text field 
 - Text Area
 - Dropdown 
 - Multiselect 
 - checkboxes 
 



