# My Budget Tracker

## Project Description

My Budget Tracker is a simple website designed to help users record, organize, and understand their daily expenses.

I created the first version of this project during Week 1. For Week 2, I continued building on the same project by adding an expense table, improving the expense form, adding multimedia elements, creating an interactive instructions section, and applying advanced CSS selectors.

The project is currently built using HTML5 and CSS3.

## Features

### 1. Expense Table

I replaced the "No expenses yet" placeholder with a structured expense table.

The table contains four columns:

* Name
* Amount
* Category
* Date

I added five sample expenses to demonstrate how the table works.

The table uses the following HTML elements:

* `<table>` to create the table
* `<thead>` for the table header
* `<tbody>` for the expense data
* `<tr>` for table rows
* `<th>` for column headings
* `<td>` for expense information

I also used CSS to add borders, padding, a colored header, alternating row colors, and a hover effect.

### 2. Upgraded Add Expense Form

I improved the Add Expense form from Week 1.

The form contains fields for:

* Expense Name
* Amount
* Category
* Date

The category field was changed from a text input to a dropdown menu.

The dropdown contains five options:

1. Food
2. Transport
3. Rent
4. Entertainment
5. Other

The form is wrapped inside a `<form>` element.

The Add Expense button uses:

`type="button"`

Each input also has a clear and unique ID. These IDs will be useful when JavaScript is introduced in future weeks.

The Add Expense button is currently only part of the webpage interface. It will be connected to JavaScript later.

### 3. Multimedia Elements

I added an image near the main heading using the `<img>` element.

The image includes the required:

* `src` attribute
* `alt` attribute
* `width` attribute

I also embedded a YouTube budgeting video using the `<iframe>` element.

The iframe includes:

* Width
* Height
* Title
* Frameborder

These multimedia elements make the webpage more informative and engaging.

### 4. Interactive Element

I added a collapsible section called "How to use this tracker."

This section uses:

* `<details>`
* `<summary>`

The user can click the summary to open and view instructions about how to use the Budget Tracker.

I also added a hover effect to the expense table rows. When the user moves the mouse over a row, its background changes.

The Add Expense button also uses `cursor: pointer` so the cursor changes to a hand when the user moves over the button.

### 5. Advanced CSS Selectors

I used several advanced CSS selectors that I learned in Week 2.

These include:

* Descendant selector
* Direct child selector
* `:nth-child()` pseudo-class
* `:first-child` pseudo-class
* `:not()` pseudo-class
* `:focus` pseudo-class
* `:hover` pseudo-class

For example, `tr:nth-child(even)` is used to create alternating background colors for the table rows.

The `:hover` selector is used to change the appearance of table rows when the mouse moves over them.

The `:focus` selector is used to change the appearance of form fields when the user selects them.

## Project Files

### index.html

The `index.html` file contains the structure and content of the Budget Tracker website.

It contains:

* Main heading
* Project description
* Add Expense form
* Expense name input
* Amount input
* Category dropdown
* Date input
* Add Expense button
* Expense table
* Five sample expenses
* Instructions section
* Logo/image
* YouTube video

### style.css

The `style.css` file controls the appearance and design of the Budget Tracker.

It contains styles for:

* Page background
* Headings
* Form section
* Input fields
* Category dropdown
* Button
* Expense table
* Table header
* Table rows
* Hover effects
* Focus effects
* Instructions section
* Multimedia section

It also contains the advanced CSS selectors required for the Week 2 assignment.

### README.md

The `README.md` file explains the Budget Tracker project.

It describes what I built, the features I added, the technologies I used, and the purpose of each project file.

## Technologies Used

* HTML5
* CSS3

## What I Learned

Through this Week 2 project, I practiced:

* Creating HTML tables
* Using `<thead>` and `<tbody>`
* Creating table rows and cells
* Building HTML forms
* Using `<select>` and `<option>`
* Using input IDs
* Adding images to a webpage
* Embedding YouTube videos
* Using `<details>` and `<summary>`
* Styling tables with CSS
* Using advanced CSS selectors
* Using `:hover` and `:focus`
* Creating a more organized and user-friendly webpage

## Future Improvements

In future weeks, I plan to add JavaScript functionality to make the Budget Tracker interactive.

Some planned improvements include:

* Adding new expenses automatically
* Calculating total expenses
* Editing expenses
* Deleting expenses
* Filtering expenses by category
* Saving expense information
* Adding income tracking
* Displaying the total amount spent

## Conclusion

The Week 2 version of My Budget Tracker builds on the project I created in Week 1.

The project demonstrates my understanding of HTML tables, HTML forms, multimedia elements, interactive HTML elements, CSS styling, and advanced CSS selectors.

The project will provide a foundation for adding JavaScript functionality in future weeks.
