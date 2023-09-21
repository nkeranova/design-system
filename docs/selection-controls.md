> Selection controls allow the user to input text, select options among a list or switch setting on or off.

## Usage
Selection controls allow users to complete tasks that involve making choices such as selecting options or switching settings on/off. Selection controls are found on screens that ask users to make decisions or declare preferences such as settings or dialogs.

There are several types of selection controls: text fields, text area, checkboxes, toggle switches and radio buttons.

## Text field
> Text fields let users enter and edit text.

### Usage
Text fields allow users to enter text into a UI. They typically are used for single-line text i.e. display only one line of text. Usually appear in forms and dialogs.

### Anatomy
<img src="https://user-images.githubusercontent.com/10553294/80093703-a8508480-856d-11ea-93c3-12577d733667.png" width="100%" alt="Text field" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Label text | Label text is used to inform users as to what information is requested for a text field. Every text field should have a label. |
| 2 | Input text | Input text is the text which the user has entered a text field. |
| 3 | Container | Displayed by stroke around a text label. Containers improve the discoverability of text fields by creating a contrast between the text field and the surrounding content. |
| 4 | Icon button | Icon buttons are used to trigger an action such as edit, delete, and settings. The Icons do not use any labels to explain the actions. Reference - [Buttons](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/buttons) |

### Behavior

#### Hover State

<img src="https://user-images.githubusercontent.com/10553294/80093725-b3a3b000-856d-11ea-80d8-0c416aca6540.png" width="100%" alt="Text field" />

> On hover the container color is `#E9EAEA`

#### Focus State

<img src="https://user-images.githubusercontent.com/10553294/80093747-bb635480-856d-11ea-996a-b3e402af985e.png" width="100%" alt="Text field" />

> On focus state the container border is `3px` and the color changes to `#566FE6`

#### Disabled State

<img src="https://user-images.githubusercontent.com/10553294/80093774-c7e7ad00-856d-11ea-8423-385a7117c23c.png" width="100%" alt="Text field" />

> Once the Text field is disabled the container border, text label, text input & icon are color - `#E2E2E2`

### Specification

<img src="https://user-images.githubusercontent.com/10553294/82828265-53c85e00-9eb9-11ea-8929-91d05a4661e9.png" width="100%" alt="Text field" />

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Text field label | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Bottom padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>`#333333`</li><li>Sentence-case</li><li>`0.5em`</li></ul> |
| Text field description | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>`#767676`</li><li>Sentence-case</li></ul> |
| Text field Area | <ul><li>Border Color</li><li>Height</li><li>Width</li></ul> | <ul><li>`#929292`</li><li>`2em`</li><li>`17em`</li></ul> |
| Icon Button (Reference - [Buttons](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/buttons)) | <ul><li>Icon Size (_W/H_)</li><li>Color</li><li>BG color</li><li>Icon Touch Area Size (_W/H_)</li></ul> | <ul><li>`1.25em` x `1.25em`</li><li>`#337AB7`</li><li>Transparent</li><li>`3em` x `3em`</li></ul> |

### Multiple Text fields

<img src="https://user-images.githubusercontent.com/10553294/80093824-db931380-856d-11ea-94db-33e5947283ea.png" width="100%" alt="Text field" />

> Once we have multiple text fields, we should keep `1.5em` between the text field items.

## Text area

> Text area let users enter and edit text.

### Usage 

Text area allow users to enter text into a UI. They typically are used for multi-line text fields grow to accommodate multiple lines of text. Text areas are taller than text fields and wrap overflow text onto a new line. They are a fixed height and scroll vertically when the cursor reaches the bottom of the field.

### Anatomy

<img src="https://user-images.githubusercontent.com/10553294/80097931-bf46a500-8574-11ea-9ae2-436212f17cea.png" width="100%" alt="Text area" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Label text | Label text is used to inform users as to what information is requested for a text field. Every text area should have a label. |
| 2 | Input text | Input text is the text which the user has entered a text field. |
| 3 | Container | Displayed by stroke around a text label. Containers improve the discoverability of the text area by creating a contrast between the text area and surrounding content. |

### Behavior 

#### Hover State

<img src="https://user-images.githubusercontent.com/10553294/80098024-e0a79100-8574-11ea-8b58-0653569b7891.png" width="100%" alt="Text area" />

> On hover the container color is `#E9EAEA`

#### Focus State

<img src="https://user-images.githubusercontent.com/10553294/80098069-f1f09d80-8574-11ea-8bbd-6a37aee7e7f6.png" width="100%" alt="Text area" />

> On focus state the container border is `3px` and the color changes to `#566FE6`

#### Disabled State
<img src="https://user-images.githubusercontent.com/10553294/80098153-12b8f300-8575-11ea-8967-cc57bf7c17cf.png" width="100%" alt="Text area" />

> Once the Text field is disabled the container border, text label, text input is color - `#E2E2E2`

### Specification

<img src="https://user-images.githubusercontent.com/10553294/80098195-2401ff80-8575-11ea-864d-67289e6ef121.png" width="100%" alt="Text area" />

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Text area label | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Bottom padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>`#333333`</li><li>Sentence-case</li><li>`0.5em`</li></ul> |
| Text area description | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>`#767676`</li><li>Sentence-case</li></ul> |
| Text Area | <ul><li>Border Color</li><li>Height</li><li>Width</li></ul> | <ul><li>`#929292`</li><li>`TBD`</li><li>`TBD`</li></ul> |

## Checkbox 

> Checkboxes allow the user to select one or more items from a set. Checkboxes can be used to turn an option on/off.

### Usage

Checkboxes can be used in two different ways: 
1. The stand-alone checkbox is used to turn a setting option on or off. 
2. With a group of checkboxes, users can select any number (zero, one or more) of independent options from a predefined list. 
3. The checkbox is used if a user can select more than one option.  If the user can just have one option, please, use radio buttons instead. 

### Anatomy

<img src="https://user-images.githubusercontent.com/10553294/80100911-544b9d00-8579-11ea-95fa-659527e76ef3.png" width="100%" alt="Checkbox" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Checkbox | Clickable checkbox item. |
| 2 | Label text | Label text is used to inform users as what selection perform once tick the checkbox. Every checkbox should have a label. |
| 3 | Checkbox item | The item is a combination of the checkbox and text label. |
| 4 | Multiple checkbox items | A list of checkbox items typically used for multiple selection lists. |

### Behavior 

> Checkboxes can be selected, unselected, or indeterminate. Checkboxes have active, hover, focused and disables states.

#### Hover State

<img src="https://user-images.githubusercontent.com/10553294/80100945-60375f00-8579-11ea-8a04-b357ab6352cb.png" width="100%" alt="Checkbox" />

> On hover the outlined color of checkbox item is `#E9EAEA`

#### Focus State

<img src="https://user-images.githubusercontent.com/10553294/80100971-6af1f400-8579-11ea-8b50-d7359e55aaf3.png" width="100%" alt="Checkbox" />

> On focus state the outlined border is 3px and the color changes to #566FE6 

#### Disabled State

<img src="https://user-images.githubusercontent.com/10553294/80100980-6f1e1180-8579-11ea-8de6-f7e3af2e0440.png" width="100%" alt="Checkbox" />

> Once the checkbox item is disabled the checkbox and the text label are color - `#E2E2E2`

#### Active State

<img src="https://user-images.githubusercontent.com/10553294/80100998-72b19880-8579-11ea-8051-83028badba16.png" width="100%" alt="Checkbox" />

> Once the checkbox item is active the checkbox and the text label are color - `#FFFFFF` and the outlined container is `#407CA0` 

### Specification

<img src="https://user-images.githubusercontent.com/10553294/80101013-75ac8900-8579-11ea-999d-04a1b8e9e9b5.png" width="100%" alt="Checkbox" />

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Selection | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Left padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>`#333333`</li><li>Sentence-case</li><li>`1em`</li></ul> |
| Checkbox | <ul><li>Size</li><li>Color</li><li>Padding</li></ul> | <ul><li>`1.5em` x `1.5em `</li><li>`#FFFFFF`</li><li>`1em`<li></ul> |
| Checkbox list | <ul><li>Padding btw checkbox items</li></ul> | <ul><li>`3em` x `3em`</li></ul> |

#### Multi-column checkbox list

<img src="https://user-images.githubusercontent.com/10553294/80101852-a640f280-857a-11ea-8c36-4d7ede7ab916.png" width="100%" alt="Checkbox" />

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Checkbox list | Item Size | `3em` x `3em` |
| Checkbox column | Column Padding | `2em` |

> Once we have multiple checkbox items in a list, we should keep 3em between checkbox items. Once we have multiple checkbox items columns, we should keep padding 2em between each column. 

## Radio

> Radio buttons are used to choose one option for a set of mutually exclusive choices. It means once one option is selected, the previously selected option automatically deselects. Users can choose one and only one option at a time.

### Usage 

Radio buttons allow the user to select one option from a set. Use radio buttons when the user needs to see all available options. If available options can be collapsed, consider using a dropdown menu because it uses less space. 

Radio button list is preferable when there is more label text and may have additional descriptions. Drop downs can just be used for short label texts.

### Anatomy

<img src="https://user-images.githubusercontent.com/10553294/80102121-06379900-857b-11ea-8853-f93a52393dc8.png" width="100%" alt="Radio" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Radio | Clickable radio button. |
| 2 | Label text | Label text is used to inform users as what selection perform once chose the radio item. Every radio button should have a label. |
| 3 | Radio item | The item is a combination of the radio button and text label. |
| 4 | Multiple radio items | A list of radio items typically used for single-choice selection lists. |

### Behavior 
> Radio buttons can be selected or unselected. Radio buttons have active, hover, focused and disabled states. 

#### Hover State

<img src="https://user-images.githubusercontent.com/10553294/80102166-118ac480-857b-11ea-935a-b26d5ccaa15e.png" width="100%" alt="Radio" />

> On hover the outlined color of the radio item is `#E9EAEA`

#### Focus State

<img src="https://user-images.githubusercontent.com/10553294/80102191-1b142c80-857b-11ea-9b72-a9244d0fdf0f.png" width="100%" alt="Radio" />

> On focus state the outlined border is `3px` and the color changes to `#566FE6`

#### Disabled State

<img src="https://user-images.githubusercontent.com/10553294/80102217-20717700-857b-11ea-9f73-56f43b239539.png" width="100%" alt="Radio" />

> Once the radio item is disabled the radio button and the text label are color - `#E2E2E2`

#### Active State

<img src="https://user-images.githubusercontent.com/10553294/80102234-249d9480-857b-11ea-9a92-2915eed85d37.png" width="100%" alt="Radio" />

> Once the radio item is active the radio button and the text label are color - `#FFFFFF` and the outlined background color is `#407CA0`

### Specification
<img src="https://user-images.githubusercontent.com/10553294/80102246-27988500-857b-11ea-9b48-78febff300fb.png" width="100%" alt="Radio" />

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Selection | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Left padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>`#333333`</li><li>Sentence-case</li><li>`1em`</li></ul> |
| Radio | <ul><li>Size</li><li>Color</li><li>Padding</li></ul> | <ul><li>`1.5em` x `1.5em `</li><li>`#FFFFFF`</li><li>`1em`</li></ul> |
| Radio list | <ul><li>Padding btw Radio items</li></ul> | <ul><li>`3em` x `3em`</li></ul> |

#### Multi-column radio list

<img src="https://user-images.githubusercontent.com/10553294/80102282-34b57400-857b-11ea-8cd3-68d204de147c.png" width="100%" alt="Radio" />

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Radio list | Item Size | `3em` x `3em` |
| Radio column | Column Padding | `2em` |

> Once we have multiple radio items in a list, we should keep 3em between the radio items. Once we have multiple radio items columns, we should keep padding 2em between each column.

## Toggle
> With a toggle switch, users can change the state of a setting between two opposing states, like yes/no, true/false, on/off, etc.

### Usage

Switches toggle the state of a single setting on/off. They are the preferred way to adjust settings on mobile. Toggle are not very commonly used on desktop and are often confusing for users.  It is often not clear what the off/on indicated.   It is required to add label text to the toggle on both sides (ex. On/Off) to make sure the user is clear about the selection.  

### Anatomy

<img src="https://user-images.githubusercontent.com/10553294/80103491-fcaf3080-857c-11ea-9a9d-1b97e4465d2c.png" width="100%" alt="Toggle" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Label text | Label text is used to inform users what selection perform once toggle the button. Every toggle should have a label. |
| 2 | Toggle button | Toggle button. A switch is successfully toggled when the user slides a switch thumb to the other side of the track, and the state of the switch changes. |
| 3 | Opposite Label text | Label text is used to inform users what opposite selection perform once toggle the button. Every toggle should have a label and opposite label I.e. true/false. |

### Behavior

When a user toggles a switch, its corresponding action takes effect immediately. If a switch cannot be turned on, the switch will automatically turn back off.

#### Hover State

<img src="https://user-images.githubusercontent.com/10553294/80103516-03d63e80-857d-11ea-94e1-2564da751e5c.png" width="100%" alt="Toggle" />

> On hover the outlined color of the toggle button is `#E9EAEA`

#### Focus State

<img src="https://user-images.githubusercontent.com/10553294/80103542-0e90d380-857d-11ea-891e-a731eb14d3cd.png" width="100%" alt="Toggle" />

> On focus state the outlined border is `3px` and the color changes to `#566FE6`

#### Disabled State

<img src="https://user-images.githubusercontent.com/10553294/80103587-1c465900-857d-11ea-9acf-055128ffb82e.png" width="100%" alt="Toggle" />

> Once the radio item is disabled the toggle button and the text labels are color - `#E2E2E2`

#### Selected State
<img src="https://user-images.githubusercontent.com/10553294/80103622-27998480-857d-11ea-904b-88ea094fcfd6.png" width="100%" alt="Toggle" />

> Once the radio item is active the toggle button is a color `#407CA0`

### Specification
<img src="https://user-images.githubusercontent.com/10553294/80104543-fa9aa100-857f-11ea-8aed-305449e9bba4.png" width="100%" alt="Toggle" />

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Selections | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>`#333333`</li><li>Sentence-case</li><li>`1em`</li></ul> |
| Toggle button | <ul><li>Size (_W/H_)</li><li>Color</li><li>Padding</li></ul> | <ul><li>`2em` x `1em `</li><li>`#407CA0`</li><li>`1em`</li></ul> |