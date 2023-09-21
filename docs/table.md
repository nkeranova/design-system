## Data Table
> Data tables display sets of data across rows and columns. They are used to display large amounts of data that can be sorted based on specific data-points.  More advanced data tables provide the flexibility to apply a function to a specific row, or multiple rows.
> Data tables are the main purpose to show granular data. Example: displaying performance metrics, ISBN numbers or teams.  A data table should not be used to show categories or listings.  Example: Showing applications, contracts or teams.

## Usage
Data tables display information in a grid-like format of rows and columns. They organize information in a way that’s easy to scan so that users can look for patterns and insights.

Data tables can contain:
* Interactive components (buttons and dropdowns)
* Non-interactive elements (copy and datapoints)
* Tools to query data (adding additional components such as filters, search and type ahead)

## Types
The previous types of actions, clickable, expandable, multi-selectable, non-stripped, paginated and sortable in the React UI (Storybook) have been retired and collapsed to simplify the designs.

**Single Select Table** is the updated default table with the following core requirements:

* Sortable column header if applicable
* Rows with optional action and expandable panel
* Table record display
* Pagination

**Multi-Select Table** ii's the updated default table with the following core requirements:

* Sortable column header
* Rows with optional action panel if applicable
* Table record display
* Pagination
* Row Multi-selection
* Table Action Panel

> Filters, Search and Type Ahead can be applied to both table formats.

## Anatomy

### Single Select Table Options

<img src="https://user-images.githubusercontent.com/10553294/78367511-e3911080-75ca-11ea-914a-239a51c5090b.png" width="100%" alt="Single Select Table Options"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 1 | Record Display | Displays how which records are currently displayed in the table out of the total # of records. |
| 2 | Column Header |	Displays the Column Category |
| 3 | Column Header Sort Function | Button that displays the order of the current records which is either ascending or descending.  On click or tap, the record order reverses as well as the icon. Default: Descending or A-Z. |
| 4 | Action Panel | See Action Panel |
| 5 | Instruction Copy | Displays informative copy for #9. |
| 6 | Table Display Option | Selects the display options for the table.  The default is 1-20.  If there are less than 20 records, omit this function with #8. |
| 7 | Pagination | See Pagination |

### Multi-Select Table Options

<img src="https://user-images.githubusercontent.com/10553294/78367631-0f13fb00-75cb-11ea-8779-fe70533148b2.png" width="100%" alt="Multi-Select Table Options"/>

| # | Component Name | Guidelines |
| - | ------------- | ---------- |
| 8 | Checkbox | Selects an individual row. Multi-row selection available via `Ctrl+Shift+L`, or `Command+Shift+L` on OS X. |
| 9 | Select All | Checking selects all rows on the current page.  It does not extend to all records.  Unchecking deselects all the rows on this page |
| 10 | Table Action Panel | The actions apply to all the records currently selected.  A row must be selected to make the buttons active. Otherwise, the buttons are visible but inactive.  The Add Button is always active since this adds a row to the current table. (see Table Action Panel for more information on how to add a row. |

## Behavior

### Focus State

<img src="https://user-images.githubusercontent.com/10553294/78368097-c90b6700-75cb-11ea-8a7f-5d095fca2e7f.png" width="100%" alt="Focus State" />

> On focus, an item is outlined with a `3px` border. The border color is `#566FE6`.

### Hover State

<img src="https://user-images.githubusercontent.com/10553294/78368477-5fd82380-75cc-11ea-8510-c901de5cf314.png" width="100%" alt="Hover State" />

> On hover state, the list item changes color (the final color is still TBD). For testing the bg color is `#E9EAEA`.

### Selected (Active State)

<img src="https://user-images.githubusercontent.com/10553294/78368719-b9d8e900-75cc-11ea-91e1-c0d2c6b548b8.png" width="100%" alt="Selected State" />

> If an item is currently selected, the list item changes colors (final colors are still TBD). For testing, the icons and text are `#FFFFFF` and the bg color is `#407CA0`.

### Expandable Row Panel

<img src="https://user-images.githubusercontent.com/10553294/78368801-de34c580-75cc-11ea-94f6-af0888649848.png" width="100%" alt="Expandable Row Panel" />

> The arrow icon changes to point upward when the expanded view is open. On mouse-click, tap, or (keyboard action?) the row collapses and the arrow return to point downward.

### Adding Row to Data Table

<img src="https://user-images.githubusercontent.com/10553294/78368878-002e4800-75cd-11ea-8395-fee3fffa28dd.png" width="100%" alt="Adding Row to Data Table" />

> A new row is automatically added to the table underneath the column header. The row has if applicable a new checkmark (multi-select table), empty text fields to enter data under each available column and a Save and Close icon in the Action Panel. If the user closes hits cancel before saving is triggered the data is lost.

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 1 | Save Row | Saves the text fields and creates a new row in the data table. When the row is saved, the screen refreshes and a data table is updated with a new data row.  The new data row appears at the top row (as confirmation) just under the column header. The user has to sort to move the columns into alphabetical order. |
| 2 | Close | Closes the row without saving the data. |

### Message (Confirmation)

<img src="https://user-images.githubusercontent.com/10553294/78368975-2b189c00-75cd-11ea-9ad5-d1f72897a6ed.png" width="100%" alt="Message" />

> The confirmation message of a deleted row is displayed in the location of the successfully deleted row. The screen auto-refreshes to display that message. The user can close that message by triggering the cancel/close icon.

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 1 | Message | Displays the appropriate message |
| 2 | Close | Closes the row |

## Accessibility

> Ask the development team to add the correct HTML+CSS semantics for accessibility compliance.

## Specs

### Single Select Table Options

<img src="https://user-images.githubusercontent.com/10553294/78370948-01ad3f80-75d0-11ea-8ad3-ce061715ef81.png" width="100%" alt="Single Select Table Options"/>

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Table Border | Width <br>Color | `0.0625em` <br>`#929292` |
| Table Header | Typeface <br>Font <br>Size <br>Case <br>Color | System <br>Default <br>Bold <br>`1 em` <br>Sentence case <br>`#000000` |
| Table Item | Typeface <br>Font <br>Size <br>Case <br>Color | System <br>Default <br>Regular <br>`1 em` <br>Sentence case <br>`#000000` |
| Item Count | Typeface <br>Font <br>Size <br>Case <br>Color | System <br>Default <br>Regular <br>`0.875 em` <br>Sentence case <br>`#575757` |
| Body Copy | Typeface <br>Font <br>Size <br>Case <br>Color | System <br>Default <br>Regular <br>`0.875 em` <br>Sentence case <br>`#575757` |

### Multi-Select Table Options

<img src="https://user-images.githubusercontent.com/10553294/78369288-9c584f00-75cd-11ea-8af3-2ffcb2f0cdab.png" width="100%" alt="Multi-Select Table Options"/>

### Expandable Row Panel

<img src="https://user-images.githubusercontent.com/10553294/78369418-d590bf00-75cd-11ea-91d5-5abe81d20a40.png" width="100%" alt="Expandable Row Panel"/>

## Responsive Grid

### 840+

<img src="https://user-images.githubusercontent.com/10553294/78369758-623b7d00-75ce-11ea-868a-fd9216f66d8f.png" width="100%" alt="840+"/>

### 720 – 839

#### 4 Columns

<img src="https://user-images.githubusercontent.com/10553294/78369855-88611d00-75ce-11ea-93e3-a6d69f20b0ab.png" width="100%" alt="720–839 4"/>

#### 5 Columns

<img src="https://user-images.githubusercontent.com/10553294/78369993-b21a4400-75ce-11ea-9206-e6f7e2254ef1.png" width="100%" alt="720–839 5"/>

#### 6+ Columns (Tablet)

<img src="https://user-images.githubusercontent.com/10553294/78370168-f86fa300-75ce-11ea-8a2a-463355b6fff3.png" width="100%" alt="720–839 6+"/>

#### On Swipe Right

<img src="https://user-images.githubusercontent.com/10553294/78370224-0ae9dc80-75cf-11ea-9ec2-046b6037e345.png" width="100%" alt="On Swipe Right"/>

The columns scroll to the right/left with the swipe of the screen. For more detailed interaction examples, check: [https://medium.com/appnroll-publication/5-practical-solutions-to-make-responsive-data-tables-ff031c48b122](https://medium.com/appnroll-publication/5-practical-solutions-to-make-responsive-data-tables-ff031c48b122)

> __Note:__ Sort by has still to be designed to work on mobile. The function would change from drop-down to a button that opens a modal window with sorting options. 