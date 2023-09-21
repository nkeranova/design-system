> Selection options allow the user to input text, and choose from different options, date and time.

## Usage

Selection Options are found where users must make decisions and declare preferences. There are several types of selection options: duel pick list, input, picklist, date & time picker.

## Duel Pick List
The dueling-picklist allows the user to perform a single or multiple-select and move options from one list to another.

### Usage

A dueling-picklist is used to move one or multiple options between two lists.

### Anatomy

<img src="https://user-images.githubusercontent.com/10553294/80406720-31005500-88cd-11ea-96ad-59d2f0cf5454.png" width="100%" alt="Duel Pick List" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | List label | Text label is used to inform users for what stands for the following list I.e. list title, group title. Every duel list should have a label. |
| 2 | Selection | Selection is used to inform users as what selection perform once choose the item. Every list should have at least one or more selections. |
| 3 | Selections list | List of possible selections |
| 4 | Container | Displayed by stroke around a selection list. Containers improve the discoverability of list items by creating a contrast between the duel pick list and surrounding content. |
| 5 | Icon Buttons | Icon buttons are used to add the selected item to the newly list. The Icons do not use any labels to explain the actions. Reference - [Buttons](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/buttons) |
| 6 | List label | Text label is used to inform users for what stands for the newly generated list I.e. list title, group title. Every duel list should have a label. |
| 7 | Container | Displayed by stroke around a selection list. |

#### Duel Pick list with Scrollbar

<img src="https://user-images.githubusercontent.com/10553294/80406763-3cec1700-88cd-11ea-8946-c1b4d45f0f84.png" width="100%" alt="Duel Pick List" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Scrollbar | The scrollbar allows the user to easily find item of huge selection list. |
| 2 | Selection list | Selection is used to inform users as what selection perform once choose the item. Every list should have at least one or more selections. |

### Behavior

#### Hover State

<img src="https://user-images.githubusercontent.com/10553294/80406788-470e1580-88cd-11ea-9cc2-ccbd45a589bc.png" width="100%" alt="Duel Pick List" />

> On hover the Selection background color is `#E9EAEA`

#### Focus State

<img src="https://user-images.githubusercontent.com/10553294/80406801-4c6b6000-88cd-11ea-9298-2b327916346f.png" width="100%" alt="Duel Pick List" />

> On focus state the Selection border is `3px` and the color changes to `#566FE6`

#### Disabled State

> If the user is not able to interact with the dueling picklist, then it should be marked as disabled.

<img src="https://user-images.githubusercontent.com/10553294/80406828-57be8b80-88cd-11ea-95da-43f90f6ab9fa.png" width="100%" alt="Duel Pick List" />

> Once the Selection is disabled the color is `#E2E2E2`

#### Selected State

<img src="https://user-images.githubusercontent.com/10553294/80406849-5ee59980-88cd-11ea-8e0d-691a390cd2cd.png" width="100%" alt="Duel Pick List" />

> Once the item is selected the selection color is `#FFFFFF` and the outlined container is `#407CA0` 

#### Dueling Pick Interaction
Please find a visual demonstration of the Dueling Pick Interaction. On selected item how the icons button behaves I.e. hovered icon button, focused icon button, selected icon button & the selected item already added to the newly group list.

<img src="https://user-images.githubusercontent.com/10553294/80406867-66a53e00-88cd-11ea-9925-8765e410ad5c.png" width="100%" alt="Duel Pick List" />

### Specification

<img src="https://user-images.githubusercontent.com/10553294/80406898-74f35a00-88cd-11ea-930f-6a9a79346fa1.png" width="100%" alt="Duel Pick List" />

| Item | Attribute | Value |
| ---- | --------- | ----- |
| List label | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Bottom padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>`#333333`</li><li>Sentence-case</li><li>`0.5em`</li></ul> |
| Selection | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Top/Left/Bottom Padding</li><li>Right Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>`#333333`</li><li>Sentence-case</li><li>`1em`</li><li>`2em`</li></ul> |
| Selection item | <ul><li>Height</li></ul> | <ul><li>`3em`</li></ul> |
| Icon Button (Reference - [Buttons](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/buttons))  | <ul><li>Icon Size (_W/H_)</li><li>Color</li><li>BG color</li><li>Icon Touch Area Size (_W/H_) </li></ul> | <ul><li>`1.25em` x `1.25em`</li><li>`#337AB7`</li><li>Transparent</li><li>`3em` x `3em`</li></ul> |

## Input

### Usage
Input allow users to upload a file into a UI. They typically appear in forms and dialogs.

### Anatomy

<img src="https://user-images.githubusercontent.com/10553294/80408921-a9b4e080-88d0-11ea-9efe-c097797fca74.png" width="100%" alt="Input" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Label | Upload file label is used to inform users that will perform uploading of the file. |
| 2 | Icon | Action Icon helps user to easily understand what kind of action could perform. Reference [Iconography](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography) |
| 3 | Action Text | Action text additionally informs the users for the available action could be triggered. |
| 4 | Input Label | Input label informs the user could load a file from URL. |
| 5 | Input field | Input field where the user will input the URL. |
| 6 | Refresh icon button | Icon button perform refresh action. Reference [Buttons](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/buttons) |

#### Input with Error Message

<img src="https://user-images.githubusercontent.com/10553294/80409209-221ba180-88d1-11ea-9c6e-f90b6b7b39a6.png" width="100%" alt="Input" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Input Text | Once the input is invalid URL an error occurs, and the input text become red. |
| 2 | Error label | Once an Error occurs, there is a red Error label. |

#### Input with Drag & Drop Error

<img src="https://user-images.githubusercontent.com/10553294/80409257-33fd4480-88d1-11ea-81b6-4cfc47f4f6cd.png" width="100%" alt="Input" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Error Message | Once an Error occurs on a Drag & Drop file action a red Error Message is shown for better user information. |
| 2 | Try Again (_Tertiary Button_) | Once an Error occurs, there is a Try Again button reloading the initial input screen. Check Buttons |

### Behavior 

#### Hover State

<img src="https://user-images.githubusercontent.com/10553294/80409275-3e1f4300-88d1-11ea-872e-9d5fa6bb113d.png" width="100%" alt="Input" />

> On hover the container/input color is `#E9EAEA` 

#### Focus State

<img src="https://user-images.githubusercontent.com/10553294/80409306-4f684f80-88d1-11ea-9f2c-4e307f1d3297.png" width="100%" alt="Input" />

> On focus state the container border is `3px` and the color changes to `#566FE6`

### Specification

<img src="https://user-images.githubusercontent.com/10553294/80409326-5b541180-88d1-11ea-89b6-e48dc3fdd553.png" width="100%" alt="Input" />

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Label | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Bottom padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>`#333333`</li><li>Sentence-case</li><li>`0.5em`</li></ul> |
| Icon | <ul><li>Size</li><li>Color</li><li>Case</li><li>Top Padding</li><li>Bottom Padding</li></ul> | <ul><li>Check Iconography</li><li>`#FFFFFF`</li><li>`2em`</li><li>`1em`</li></ul> |
| Action Text | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Bottom padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1.5em`</li><li>`#767676`</li><li>Sentence-case</li><li>`1.25em`</li></ul> |
| Input Label | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Bottom padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>`#333333`</li><li>Sentence-case</li><li>`0.5em`</li></ul> |
| Input field | <ul><li>Size</li><li>Border Color</li><li>Bottom padding</li></ul> |  <ul><li>Check Selection Controls – Text field</li><li>`#FFFFFF`</li><li>`2em`</li></ul> |
| Refresh icon button | <ul><li>Size</li><li>Color</li></ul> | <ul><li>Check Buttons</li><li>`#FFFFFF`</li></ul> |

#### Input Error Specs

<img src="https://user-images.githubusercontent.com/10553294/80409375-6dce4b00-88d1-11ea-939f-dddbd029366d.png" width="100%" alt="Input" />

> If you add an invalid URL to the input field the input text will change to color to #B20000 and add text label below “This is not a valid entry” in #B20000 as well.

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Input Text | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>`#B20000`</li><li>Sentence-case</li></ul> |
| Error Label | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Top Padding</li><li>Bottom Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>`#B20000`</li><li>Sentence-case</li><li>`0.5em`</li><li>`2em`</li></ul> |

#### Input Drag & Drop Specs

<img src="https://user-images.githubusercontent.com/10553294/80409383-7161d200-88d1-11ea-8396-18e107c0f74a.png" width="100%" alt="Input" />

> Once Error occurs on Drag and Drop fail, Error Message is shown “Error Message. Upload Your File Again.” in color #B20000 and “Try Again” Tertiary button is added, allows user to retry the operation.

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Error Message | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Top Padding</li><li>Bottom Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>`#B20000`</li><li>Sentence-case</li><li>`1.25em`</li><li>`1.75em`</li></ul> |
| Try Again (_Tertiary button_)  | <ul><li>Size</li><li>Color</li><li>Top Padding</li></ul> | <ul><li>Check Buttons</li><li>`#337AB7`</li><li>`2em`</li></ul> |

## Picklist

A Picklist provides a user with a read-only input field that is accompanied with a list box of pre-defined options. A picklist has both single and multi-selection patterns.

### Usage

A picklist is a widget that displays a list of selectable options. When an option is selected, it is shown as selected and the value of the read-only input is updated to match it.

A multi-select picklist is a widget that displays a list of selectable options, where more than one option can be chosen.

### Anatomy

#### Single Picklist

<img src="https://user-images.githubusercontent.com/10553294/80413433-23040180-88d8-11ea-916b-d2814a18e3e1.png" width="100%" alt="Picklist" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Picklist Label (_label + Icon_) | Picklist Label contains text label & Action Icon. In general, is a read-only input field, informs the user regarding the Selections list purpose. |
| 2 | Active Picklist Label | A Selected Picklist Label which expand the Selections list. |
| 3 | Selections list | The Selection list is a list box of pre-defined options. |
| 4 | Container | List box container displayed by stroke border. |

#### Multiple Picklist

<img src="https://user-images.githubusercontent.com/10553294/80413452-2a2b0f80-88d8-11ea-8f75-2db0d5411aeb.png" width="100%" alt="Picklist" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Active Picklist Label | Picklist Label contains text label & Action Icon. In general, is a read-only input field, informs the user regarding the Selections list purpose. Selected Picklist Label which expand the Selections list. |
| 2 | Checkbox | Checkbox of each Selection of the predefined options. |
| 3 | Tertiary Button | Check Buttons. The Tertiary button will perform an action over the selected items from the predefined list. |
| 4 | Multiple Selections List Columns | Multiple Selections List displayed by separate columns. |

### Behavior

#### Hover State

<img src="https://user-images.githubusercontent.com/10553294/80413477-32834a80-88d8-11ea-80d0-30ea0bd7eec5.png" width="100%" alt="Picklist" />

> On hover the container color is `#E9EAEA`, the Label text become `#407CA0` 

#### Focus State

<img src="https://user-images.githubusercontent.com/10553294/80413500-3911c200-88d8-11ea-9b46-3cfb8187af82.png" width="100%" alt="Picklist" />

> On focus state the container border is `3px` and the color changes to `#566FE6` 

#### Active/Selected State

<img src="https://user-images.githubusercontent.com/10553294/80413535-475fde00-88d8-11ea-8bc1-9403e79133db.png" width="100%" alt="Picklist" />

> On Active state the Selection item background color become `#407CA0` and the Selection item text become `#000000` 

#### Disabled State
<img src="https://user-images.githubusercontent.com/10553294/80413569-4fb81900-88d8-11ea-8d37-c32ece1b01c6.png" width="100%" alt="Picklist" />

> Once the Selection item is disabled the text label & checkbox are color - `#E2E2E2` 

### Specification

#### Single Picklist

<img src="https://user-images.githubusercontent.com/10553294/80413589-56469080-88d8-11ea-8303-f294de06682f.png" width="100%" alt="Picklist" />

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Label | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Top/Bottom Padding</li><li>Left/Right Padding</li></ul> | <ul><li>System Default</li><li>Bold</li><li>`1em`</li><li>`#337AB7`</li><li>Sentence-case</li><li>`1em`</li><li>`2em`</li></ul> |
| Label Icon | <ul><li>Size</li><li>Color</li><li>Top/Bottom Padding</li><li>Left/Right Padding</li></ul> | <ul><li>Check Iconography</li><li>`#337AB7`</li><li>`1em`</li><li>`2em`</li></ul> |
| Active Label + Icon | <ul><li>Color</li><li>BG Color</li><li>Border Radius</li></ul> | <ul><li>`#FFFFFF`</li><li>`#337AB7`</li><li>`0.625em`</li></ul> |
| Selection item | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Height</li><li>Top/Left/Bottom Padding </li><li>Right Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>`#333333`</li><li>Sentence-case</li><li>`3em`</li><li>`1em`</li><li>`2em`</li></ul> |

#### Multiple Picklist

<img src="https://user-images.githubusercontent.com/10553294/80413601-5ba3db00-88d8-11ea-897b-590240162fb2.png" width="100%" alt="Picklist" />

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Checkbox | <ul><li>Size</li><li>Left/Right Padding</li></ul> | <ul><li>`1.5em` x `1.5 em`</li><li>`1em`</li></ul> |
| Selection List Column | <ul><li>Left/Right Padding</li></ul> | <ul><li>`2em`</li></ul> |
| Tertiary Button | <ul><li>Color</li><li>BG Color</li><li>Top/Bottom Padding</li><li>Right Padding</li></ul> | <ul><li>`#337AB7`</li><li>`#337AB7`</li><li>`1em`</li><li>`2em`</li></ul> |

## Date Picker

> Date pickers let users select a date, or a range of dates.

### Usage 

Date pickers let users select a date or range of dates. They should be suitable for the context in which they appear. 

Date pickers can be embedded into: 
* Dialogs on mobile 
* Text field dropdowns on desktop 

#### Best Principles

1. **Relevant** - could display past, present, or future dates 
2. **Clear** - indicate important dates, such as current and selected days 
3. **Intuitive** - ensure picking a day or time is intuitive, use common picker patterns, such as a calendar. 

Desktop date pickers allow the selection of a specific date and year. The desktop date picker displays a date input field by default, and a dropdown calendar appears when the user taps on the input field. The user can interact with either form of date entry. 

Desktop date pickers are ideal for navigating dates in both the near future (or past) and the distant future (or past), as they provide multiple ways to select dates. 

### Anatomy

The date picker is a form element, containing a label and text input, and a dropdown menu, containing a grid-based calendar and filters. The form element acts as a trigger for the dropdown.

<img src="https://user-images.githubusercontent.com/10553294/80415635-7af03780-88db-11ea-9b25-92abb6b54a65.png" width="100%" alt="Date Picker" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Date Label | Text label is used to inform users for what stands for the following date picker. |
| 2 | Container | Displayed by stroke around a date read-only date format label. Containers improve the discoverability of date picker by creating a contrast between the text field and surrounding content. |
| 3 | Icon Button | Icon buttons are used to trigger an action such as expand calendar & select date. Reference Buttons |
| 4 | Icon Button | Icon buttons are used to trigger an action such as render the previous/next month to the expanded calendar. Reference Buttons |
| 5 | Calendar container | Displayed by stroke around a Calendar. Containers improve the discoverability of date picker by creating a contrast between the text field and surrounding content. |
| 6 | Calendar view | Calendar view render the days & dates of a specific month by columns & rows. Allows the user to select a date. |

#### Date Picker Range

Desktop date range pickers allow a range of days to be selected. They display both calendar and date input fields.

<img src="https://user-images.githubusercontent.com/10553294/80415660-84799f80-88db-11ea-9edd-0cdd585f4631.png" width="100%" alt="Date Picker" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | From Label | Text label is used to inform users they could select the from date. |
| 2 | Container | Displayed by stroke around a date read-only date format label. Containers improve the discoverability of date picker by creating a contrast between the text field and surrounding content. |
| 3 | Icon Button | Icon buttons are used to trigger an action such as expand calendar & select date. Reference Buttons |
| 4 | To Label | Text label is used to inform users they could select the to - date. |
| 5 | Container | Displayed by stroke around a date read-only date format label. |
| 6 | Icon Button | Icon buttons are used to trigger an action such as expand calendar & select date. Reference Buttons |
| 7 | Previous Icon Button | Icon buttons are used to trigger an action such as render the previous month to the expanded calendar. Reference Buttons | 
| 8 | Next Icon Button | Icon buttons are used to trigger an action such as render next month to the expanded calendar. Reference Buttons |
| 9 | Calendar views | Calendar views render the days & dates of 2 specific months by columns & rows. Allows the user to select a (from-to) dates. |
| 10 | Calendar container | Displayed by stroke around Calendar views. Containers improve the discoverability of date picker by creating a contrast between the text field and surrounding content. |

### Behavior

Users can input dates either using a keyboard or by navigating the calendar UI; both options are immediately available when the desktop date picker is accessed. 

#### Hover State

<img src="https://user-images.githubusercontent.com/10553294/80415688-8cd1da80-88db-11ea-9eb6-9789507a0132.png" width="100%" alt="Date Picker" />

> On hover the container color is `#E9EAEA` 

#### Focus State

<img src="https://user-images.githubusercontent.com/10553294/80415724-96f3d900-88db-11ea-823f-3efddc84c79d.png" width="100%" alt="Date Picker" />

> On focus state the container border is `3px` and the color changes to `#566FE6` 

#### Active State

<img src="https://user-images.githubusercontent.com/10553294/80415750-9f4c1400-88db-11ea-976a-5ab5cf7a0102.png" width="100%" alt="Date Picker" />

#### Deselected State

<img src="https://user-images.githubusercontent.com/10553294/80415766-a7a44f00-88db-11ea-8039-3dc158b14fed.png" width="100%" alt="Date Picker" />

> Once the Text field is disabled the container border, text label, text input & icon are color - `#E2E2E2`.  Dates might be disabled because dates are not available etc.  It requires certain parameters and rules for dates to be applied. 

### Specification

<img src="https://user-images.githubusercontent.com/10553294/80415793-b12db700-88db-11ea-9fdc-ade4aa93813f.png" width="100%" alt="Date Picker" />

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Date label | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Bottom Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>`#333333`</li><li>Sentence-case</li><li>`0.5em`</li></ul> |
| Text field Area | <ul><li>Border Color</li><li>Height</li><li>Width</li></ul> | <ul><li>`#929292`</li><li>`2em`</li><li>`17em`</li></ul> |
| Text Data | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Date Format</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>`#707070`</li><li>Sentence-case</li><li>`mm/dd/yy`</li></ul> |
| Icon Button (_Reference - Buttons_) | <ul><li>Icon Size (_W/H_)</li><li>Color</li><li>BG color</li><li>Icon Touch Area Size (_W/H_)</li></ul> | <ul><li>`1.25em` x `1.25em`</li><li>`#337AB7`</li><li>Transparent</li><li>`3em` x `3em`</li></ul> |
| Month & year label | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Padding</li></ul> | <ul><li>System Default</li><li>Bold</li><li>`0.875em`</li><li>`#333333`</li><li>Sentence-case</li><li>`1em`</li></ul> |
| Previous/Next Buttons (_Reference - Buttons_) | <ul><li>Icon Size (_W/H_)</li><li>Color</li><li>BG color</li><li>Icon Touch Area Size (_W/H_)</li></ul> | <ul><li>`1.25em` x `1.25em`</li><li>`#337AB7`</li><li>Transparent</li><li>`3em` x `3em`</li></ul> |
| Calendar view | <ul><li>Day Column Size</li><li>Date Row Size</li></ul> | <ul><li>`1.5em`</li><li>`1.5em`</li></ul> |

#### Date Picker Range Specs

<img src="https://user-images.githubusercontent.com/10553294/80415821-c0146980-88db-11ea-8cb7-3a0f59a2b925.png" width="100%" alt="Date Picker" />

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Previous Buttons (_Reference - Buttons_) | <ul><li>Icon Size (_W/H_)</li><li>Color</li><li>BG color</li><li>Icon Touch Area Size (_W/H_)</li><li>Left Padding</li></ul> | <ul><li>`1.25em` x `1.25em`</li><li>`#337AB7`</li><li>Transparent</li><li>`3em` x `3em`</li><li>`1em`</li></ul> |
| Next Buttons (_Reference - Buttons_) | <ul><li>Icon Size (_W/H_)</li><li>Color</li><li>BG color</li><li>Icon Touch Area Size (_W/H_)</li><li>Right Padding</li></ul> | <ul><li>`1.25em` x `1.25em`</li><li>`#337AB7`</li><li>Transparent</li><li>`3em` x `3em`</li><li>`1em`</li></ul> |
| Calendar view | <ul><li>Day Column Size</li><li>Date Row Size</li><li>Left/Right Padding (_Container padding_)</li><li>Calendar view Padding (_btw both Calendars_)</li></ul> | <ul><li>`1.5em`</li><li>`1.5em`</li><li>`1em`</li><li>`1.25em`</li></ul> |

> Calendar view Padding should be 1.25em or 2.5em between each Calendar

## Time Picker

A time picker is an autocomplete text input to capture a time.

### Usage 

A time picker is used to select a single time.

### Anatomy

<img src="https://user-images.githubusercontent.com/10553294/80418288-da504680-88df-11ea-851f-ba18e09e6db3.png" width="100%" alt="Time Picker" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Time Label | Text label is used to inform users for what stands for the following time picker i.e time label. |
| 2 | Container | Displayed by stroke around a date read-only time format label. Containers improve the discoverability of date picker by creating a contrast between the text field and surrounding content. |
| 3 | Icon Button | Icon buttons are used to trigger an action such as an expand times list. Reference Buttons |
| 4 | Available times list | A list with possible options displayed in am/pm format. |
| 5 | Scrollbar | The scrollbar allows the user to easily find an item of a huge selection list. |
| 6 | Container | Displayed by stroke around a date read-only time format label. Containers improve the discoverability of date picker by creating a contrast between the text field and surrounding content. |

### Behavior 

#### Hover State

<img src="https://user-images.githubusercontent.com/10553294/80418310-e3d9ae80-88df-11ea-8f22-b24127d882c5.png" width="100%" alt="Time Picker" />

> On hover the item background color is `#E9EAEA` 

#### Focus State

<img src="https://user-images.githubusercontent.com/10553294/80418328-eb995300-88df-11ea-8979-d6079373a633.png" width="100%" alt="Time Picker" />

> On focus state the container border is `3px` and the color changes to `#566FE6` 

#### Active State

<img src="https://user-images.githubusercontent.com/10553294/80418346-f0f69d80-88df-11ea-8563-9502f892826f.png" width="100%" alt="Time Picker" />

> If an item is currently selected, the bg changes colors (final colors are still TBD).  For testing the icons and text are #FFFFFF and the bg color is #407CA0. 

#### Disabled State

<img src="https://user-images.githubusercontent.com/10553294/80418355-f522bb00-88df-11ea-8d1e-60d77b1a2483.png" width="100%" alt="Time Picker" />

> Once the time field is disabled the text label to color - `#E2E2E2`

### Specification

<img src="https://user-images.githubusercontent.com/10553294/80418370-fb189c00-88df-11ea-9a22-adb4a887ad3f.png" width="100%" alt="Time Picker" />

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Time list Container | <ul><li>Top Padding</li><li>Height (_depends on the list item N_)</li></ul> | <ul><li>`0.375em`</li><li>`3em x N`</li></ul> | 
| Scrollbar | <ul><li>Icon Size (_W/H_)</li><li>Color</li><li>BG color</li><li>Icon Touch Area Size (_W/H_)</li><li>Right Padding</li></ul> | <ul><li>`1.25em` x `1.25em`</li><li>`#337AB7`</li><li>Transparent</li><li>`3em` x `3em`</li><li>`1em`</li></ul> |
| Time list item | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Top/Left/Bottom Padding</li><li>Right Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>`#333333`</li><li>Sentence-case</li><li>`1em`</li><li>`2em`</li></ul> |