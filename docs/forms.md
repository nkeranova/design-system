> A form is a group of related selection controls that allows users to provide data or configure options. Forms can be simple or complex, and may be presented as dedicated pages, side panels, or dialogs depending on the use case and the situation.

## Usage

Use forms to allow people to enter data for use by the application, or to configure options. Forms are used to get information and guide people with minimal fuss.

### When to use 

Forms are incredibly common in user interfaces and their design and usage continues to evolve as input methods. You might design a form for a user to:

* Sign up for / log into an account
* Register for a service 
* Reconfigure settings, (e.g. enabling notifications) 
* Take a survey 
* Purchase a product 
* Provide feedback

& Etc. 

## Anatomy

A form is simply built ad a group of related selection controls elements. A form could contain a text field, text area, checkbox/radio list, buttons and more. To learn in detail about every possible option, please review the Selection controls section. 

If the form is more complex could be built from different Selection options and more elements from the DS. 

Forms are comprised of some or all of the following elements: title, description, labels, inputs, text filed/area, radio, checkbox, buttons, etc. Or whatever selection option/control element. Reference - check the Selection options & Selection controls sections 

## 1Column Form

A one-column form is basically form build in one column structure. The elements are organized in vertical hierarchy each element is below the previous sibling.

### Simple 1Column Form

Simple one column form is built by the simplest possible elements: inputs (text fields/data inputs), text area & buttons.

<img src="https://user-images.githubusercontent.com/10553294/83426636-23903a80-a438-11ea-9281-5c625b391785.png" width="100%" alt="Forms" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Form Title | Displays the Form Title. Should be brief and descriptive. |
| 2 | Text field | Text field is element described in [Selection controls](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/selection-controls) section. |
| 3 | Form Container | Displayed by stroke around a form content. Containers improve the discoverability of the forms by creating a contrast with the surrounding content. Access to the rest of the UI is disabled until the form is filled. |
| 4 | Required | An asterisk `*` sign is used to mark the required elements of the form content. |
| 5 | Button | Reference – [Buttons](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/buttons) section. |

#### Form with subtitle

<img src="https://user-images.githubusercontent.com/10553294/83426652-28ed8500-a438-11ea-8fc7-3e6d6b8468a1.png" width="100%" alt="Forms" />

| # | Element | Description |
| - | ------- | ----------- |
| 6 | Subtitle | Displays the Form Subtitle. Should provide additional important details, again be brief and descriptive. Could be an additional brief description of the form purpose/goal. |
| 7 | Text Area | Text Area is element described in detail under [Selection controls](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/selection-controls) section. |
| 8 | Button pair | Button pair, check Buttons. |

#### Form with Error 

> Once an Error occurs, there is a red Error label & the description (entered text by the user) becomes red as well. 

<img src="https://user-images.githubusercontent.com/10553294/83426667-2d19a280-a438-11ea-9f5b-92010c7ed3cf.png" width="100%" alt="Forms" />

| # | Element | Description |
| - | ------- | ----------- |
| 9 | Description | Input text which the user has entered a text field. In case of Error becomes red. |
| 10 | Error Label | Once an Error occurs, there is a red Error label. |

#### Behavior

##### Focus state

<img src="https://user-images.githubusercontent.com/10553294/83426678-3145c000-a438-11ea-9a83-84a746b668a3.png" width="100%" alt="Forms" />

> On focus, a form is outlined with a `3px` border. The border color is `#566FE6`

##### Hover state

<img src="https://user-images.githubusercontent.com/10553294/83426695-37d43780-a438-11ea-8786-f6d14c823fa4.png" width="100%" alt="Forms" />

> On hover state, the form item changes the background color to `#C8C9C7` by `60%`

##### Disabled state

<img src="https://user-images.githubusercontent.com/10553294/83426709-3c98eb80-a438-11ea-9019-fb77898bc501.png" width="100%" alt="Forms" />

> On Disabled state the form is inactive and all elements becomes `#C8C9C7`

#### Specification

<img src="https://user-images.githubusercontent.com/10553294/83426724-43276300-a438-11ea-842e-77af52f3b1d4.png" width="100%" alt="Forms" />

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Form Title | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top Padding</li><li>Bottom Padding</li><li>Left Padding</li></ul> |  <ul><li>System Default</li><li>Regular</li><li>`1.5em`</li><li>Sentence case</li><li>`#000000`</li><li>`1.75em`</li><li>`1.25em`</li><li>`1.5em`</li></ul> |
| Form Subtitle (_Optional_) | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top/Bottom Padding </li><li>Left Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>Sentence case</li><li>`#000000`</li><li>`1.25em`</li><li>`1.5em`</li></ul> |
| Form Element – _check the Element’s section_ | <ul><li>Top/Bottom Padding</li><li>Left/Right Padding</li></ul> | <ul><li>`1.5em`</li><li>`1.5em`</li></ul> |
| Error Label | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top/Bottom Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>Sentence case</li><li>`#B20000`</li><li>`0.5em`</li></ul> |
| Button – _check Buttons_ | <ul><li>Top/Left/Right Padding</li><li>Bottom Padding</li></ul> | <ul><li>`1.5em`</li><li>`1.75em`</li></ul> |
| Button pairs - _check Buttons_ | <ul><li>Top/Left/Right Padding</li><li>Bottom Padding </li><li>Padding btw the Buttons</li></ul> | <ul><li>`1.5em`</li><li>`1.75em`</li><li>`1.5em`</li></ul> |

> The main rule is you should always keep `1.5em` space between each 2 Form Elements.

### Complex 1Column Form

> Complex one column form is built by the combination of more complex elements such as: radio, checkbox, date picker, dropdowns & button pairs.

<img src="https://user-images.githubusercontent.com/10553294/83520751-ddde7b00-a4e6-11ea-81f9-ca8557339624.png" width="100%" alt="Forms" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Form Title | Displays the Form Title. Should be brief and descriptive. |
| 2 | Subtitle | Displays the Form Subtitle. Should provide additional important details, again be brief and descriptive. Could be an additional brief description of the form purpose/goal. |
| 3 | Text field | Text field is an element described in the Selection controls section. |
| 4 | Required | An asterisk `*` sign is used to mark the required elements of the form content. |
| 5 | Radio List | A list of radio items. Check the Selection controls section. |
| 6 | Error Label | Once an Error occurs, there is a red Error label. |
| 7 | Button pair | A button pairs. Check Buttons. |

#### Behavior

##### Focus state

<img src="https://user-images.githubusercontent.com/10553294/83520812-fb134980-a4e6-11ea-9f90-af93ff38c7d9.png" width="100%" alt="Forms" />

> On focus, a form is outlined with a `3px` border. The border color is `#566FE6`

##### Hover state

<img src="https://user-images.githubusercontent.com/10553294/83520826-ff3f6700-a4e6-11ea-833e-e941cfb225d8.png" width="100%" alt="Forms" />

> On hover state, the form item changes the background color to `#C8C9C7` by `60%`

##### Disabled state

<img src="https://user-images.githubusercontent.com/10553294/83520837-036b8480-a4e7-11ea-8752-9430b382fab9.png" width="100%" alt="Forms" />

> On Disabled state the form is inactive and all elements becomes `#C8C9C7` 

#### Specification

<img src="https://user-images.githubusercontent.com/10553294/83520856-08303880-a4e7-11ea-9df1-81a2c2cfd287.png" width="100%" alt="Forms" />

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Form Title | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top Padding</li><li>Bottom Padding</li><li>Left Padding</li></ul> |  <ul><li>System Default</li><li>Regular</li><li>`1.5em`</li><li>Sentence case</li><li>`#000000`</li><li>`1.75em`</li><li>`1.25em`</li><li>`1.5em`</li></ul> |
| Form Subtitle (_Optional_) | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top/Bottom Padding </li><li>Left Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>Sentence case</li><li>`#000000`</li><li>`1.25em`</li><li>`1.5em`</li></ul> |
| Form Element – _check the Element’s section_ | <ul><li>Top/Bottom Padding</li><li>Left/Right Padding</li></ul> | <ul><li>`1.5em`</li><li>`1.5em`</li></ul> |
| Error Label | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top/Bottom Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>Sentence case</li><li>`#B20000`</li><li>`0.5em`</li></ul> |
| Button pairs - _check Buttons_ | <ul><li>Top/Left/Right Padding</li><li>Bottom Padding </li><li>Padding btw the Buttons</li></ul> | <ul><li>`1.5em`</li><li>`1.75em`</li><li>`1.5em`</li></ul> |

> The main rule is you should always keep `1.5em` space between each 2 Form Elements.

## Multiple Columns Form 

A multiple columns form is basically form build in more than one column structure. The elements are organized in vertical &horizontal hierarchy. 

### Simple Multiple Columns Form 

Simple multi-column form is built by the simplest possible elements: inputs (text fields/data inputs), text area & buttons.

<img src="https://user-images.githubusercontent.com/10553294/83522311-2a2aba80-a4e9-11ea-9391-15a7ff633aa9.png" width="100%" alt="Forms" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Form Title | Displays the Form Title. Should be brief and descriptive. |
| 2 | Subtitle | Displays the Form Subtitle. Should provide additional important details, again be brief and descriptive. Could be an additional brief description of the form purpose/goal. |
| 3 | Text field | Text field is an element described in the Selection controls section. |
| 4 | Required | An asterisk `*` sign is used to mark the required elements of the form content. |
| 5 | Error Label | Once an Error occurs, there is a red Error label. |
| 6 | Text Area | Text Area is an element described in detail under the Selection controls section. |
| 7 | Button pair | A button pairs. Check Buttons. |

#### Behavior 

##### Focus state 

<img src="https://user-images.githubusercontent.com/10553294/83522324-3151c880-a4e9-11ea-973a-dbc634569190.png" width="100%" alt="Forms" />

> On focus, a form is outlined with a `3px` border. The border color is `#566FE6`

##### Hover state

<img src="https://user-images.githubusercontent.com/10553294/83522521-7413a080-a4e9-11ea-834e-5cdbaa011cfd.png" width="100%" alt="Forms" />

> On hover state, the form item changes the background color to `#C8C9C7` by `60%`

##### Disabled state

<img src="https://user-images.githubusercontent.com/10553294/83522539-7a098180-a4e9-11ea-93bf-81079a39d167.png" width="100%" alt="Forms" />

> On Disabled state the form is inactive and all elements becomes `#C8C9C7`

#### Specification

<img src="https://user-images.githubusercontent.com/10553294/83522547-7d9d0880-a4e9-11ea-88fc-378ea465a073.png" width="100%" alt="Forms" />

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Form Title | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top Padding</li><li>Bottom Padding</li><li>Left Padding</li></ul> |  <ul><li>System Default</li><li>Regular</li><li>`1.5em`</li><li>Sentence case</li><li>`#000000`</li><li>`1.75em`</li><li>`1.25em`</li><li>`1.5em`</li></ul> |
| Form Subtitle (_Optional_) | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top/Bottom Padding </li><li>Left Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>Sentence case</li><li>`#000000`</li><li>`1.25em`</li><li>`1.5em`</li></ul> |
| Form Element – _check the Element’s section_ | <ul><li>Top/Bottom Padding</li><li>Left/Right Padding</li></ul> | <ul><li>`1.5em`</li><li>`1.5em`</li></ul> |
| Error Label | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top/Bottom Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>Sentence case</li><li>`#B20000`</li><li>`0.5em`</li></ul> |
| Button pairs - _check Buttons_ | <ul><li>Top/Left/Right Padding</li><li>Bottom Padding </li><li>Padding btw the Buttons</li></ul> | <ul><li>`1.5em`</li><li>`1.75em`</li><li>`1.5em`</li></ul> |
| Columns | <ul><li>Padding btw 2 columns</li></ul> | <ul><li>`2em`</li></ul> | 

> The main rule for multiple columns used in form is you should always keep `2em` space between each `2 columns`. The number of columns depends of the need, we do __NOT__ recommend using of more than `3 columns`. 

### Complex Multiple Columns Form

Complex multi-column form is built by the combination of more complex elements such as: radio, checkbox, date picker, dropdowns & button pairs.

<img src="https://user-images.githubusercontent.com/10553294/83525210-58aa9480-a4ed-11ea-8a0a-da7ceeef7b77.png" width="100%" alt="Forms" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Form Title | Displays the Form Title. Should be brief and descriptive. |
| 2 | Subtitle | Displays the Form Subtitle. Should provide additional important details, again be brief and descriptive. Could be an additional brief description of the form purpose/goal. |
| 3 | Error Label | Once an Error occurs, there is a red Error label. |
| 4 | Required | An asterisk `*` sign is used to mark the required elements of the form content. |
| 5 | Radio | Radio list options, usually used for Gender, ect. |
| 6 | Checkbox list | Checkbox list give option for multiple selection, check Selection controls section. |
| 7 | Button pair | A button pairs. Check Buttons. |


#### Behavior 

##### Focus state

<img src="https://user-images.githubusercontent.com/10553294/83525227-5d6f4880-a4ed-11ea-813c-2458079f34c0.png" width="100%" alt="Forms" />

> On focus, a form is outlined with a `3px` border. The border color is `#566FE6`

##### Hover state

<img src="https://user-images.githubusercontent.com/10553294/83525242-606a3900-a4ed-11ea-83f5-2ad7722bc124.png" width="100%" alt="Forms" />

> On hover state, the form item changes the background color to `#C8C9C7` by `60%`

##### Disabled state

<img src="https://user-images.githubusercontent.com/10553294/83525256-63fdc000-a4ed-11ea-81d5-7d6c39fcac67.png" width="100%" alt="Forms" />

> On Disabled state the form is inactive and all elements becomes `#C8C9C7`

#### Specification

<img src="https://user-images.githubusercontent.com/10553294/83525267-6829dd80-a4ed-11ea-878d-42021886d59e.png" width="100%" alt="Forms" />

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Form Title | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top Padding</li><li>Bottom Padding</li><li>Left Padding</li></ul> |  <ul><li>System Default</li><li>Regular</li><li>`1.5em`</li><li>Sentence case</li><li>`#000000`</li><li>`1.75em`</li><li>`1.25em`</li><li>`1.5em`</li></ul> |
| Form Subtitle (_Optional_) | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top/Bottom Padding </li><li>Left Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>Sentence case</li><li>`#000000`</li><li>`1.25em`</li><li>`1.5em`</li></ul> |
| Form Element – _check the Element’s section_ | <ul><li>Top/Bottom Padding</li><li>Left/Right Padding</li></ul> | <ul><li>`1.5em`</li><li>`1.5em`</li></ul> |
| Error Label | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top/Bottom Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>Sentence case</li><li>`#B20000`</li><li>`0.5em`</li></ul> |
| Button pairs - _check Buttons_ | <ul><li>Top/Left/Right Padding</li><li>Bottom Padding </li><li>Padding btw the Buttons</li></ul> | <ul><li>`1.5em`</li><li>`1.75em`</li><li>`1.5em`</li></ul> |
| Columns | <ul><li>Padding btw 2 columns</li></ul> | <ul><li>`2em`</li></ul> |

> The main rule for multiple columns used in form is you should always keep `2em` space between each `2 columns`. The number of columns depends of the need, we do NOT recommend using of more than `3 columns`. 

!> Potentially we could add Active Behavior state per each Form & Real-world Forms examples if needed.