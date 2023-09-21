> Buttons are clickable items which allow users to perform an action, make choices, with a single tap.

## Usage

Generally __buttons are used to initialize an action__. The different labels express what action will occur when the user interacts with it. __Please don’t use buttons as navigational elements__. (see navigation for more information) 

__Examples for Actions are__: `Add`, `Save`, `Delete`, `Cancel`, `Close`, `Submit`, `Edit`, `Merge` and `Sign in`/`Sign up`, etc.  They are used to perform an action on the current page. 

__Examples how & where buttons are used:__
* __Forms__ – once you fill and Submit a form. 
* __Modals__ - a pop-up window which allow you to perform an action I.e. `Cancel`/`Save`. 
* __Dialogs__ – a modal window that appears to provide critical information or ask for a decision I.e. adding/deleting an account. 
* __Cards__ – allow the user to perform an action for the specific element on the cars I.e. Service’s authorization cards set and button to generate Refresh token. 
* __Toolbars__ – normally is a set of icons / buttons that are part of a software’s interface and more.

### Good practices
Once we implement Buttons on our UI, we should follow the good established principles:
* __Recognizable__ – buttons should indicate could perform an action. The user needs to be sure that the UI element is a button and by tabbing it will trigger an action.
* __Discoverable__ – should be easy to find beside the other UI elements or buttons, which means we should keep the Hierarchy of Button order (_The Secondary / Primary button order_) and alignment (depends on the usage)
* __Clear__ – the action and state should be clear to the user.

## General Anatomy
The button’s anatomy contains required and optional elements depending on the button type. They may include a text label, icon or both.

### Text Label
Button labels should clearly indicate the action of the button. This is a required component for every type button besides the toggle. A good practice is to use active verbs, such as Add or Delete.

* Use specific labels, such as `Save` or `Discard`, instead of using `OK` and `Cancel`. This is helpful when the user is confirming an action.
* Button text is a call to action used different types of buttons (such as text, outlined and contained buttons) and in tabs, dialogs, and cards.
* The text label should be Sentenced-case capitalization, it is used because it conveys a friendly tone that invites users to press the button.
* The text label should be as short as possible, enough meaningful and clear to the users. Normally the maximum allowed words per label are `3`, however in some cases three words nd is optional for the rest button types. Normally, we use glyphs (`1em = 16px`) within buttons or should match the text label size. They could appear to the left of the label. Glyphs used in buttons must be directly related to the action that the user is taking. The icon must be the same color value as the text within a button. could be a lot more than acceptable, that’s why in general the text label should be less than `20 characters`.
* Single word text label is the best possible option, otherwise try to be up to `20 characters` (two words).
* If a text label is not used, an icon should be present to describe the action that will occur if a user taps a button.

### Icon
The icon is required element for the toggle buttons a for reference currently we have on several Axway products `+ API` button which stands for `Adding new API`. In this case the plus icon replaces the actual verb and is enough clear what does the action perform once hit the button.

### Button Elements

<img src="https://user-images.githubusercontent.com/10553294/79491877-c6772b80-8027-11ea-8c74-cf67c13c79ab.png" width="100%" alt="Button Elements"/>

| # | Button Type | Required | Optional |
| - | ----------- | -------- | -------- |
| 1 | Text button | 1. Text label | 2. Icon |
| 2 | Outlined button | 1. Text label <br>2. Container | 3. Icon |
| 3 | Contained button | 1. Text label <br>2. Container | 3. Icon |
| 4 | Toggle button | 1. Icon | 2. Container |

## Hierarchy

### Buttons order
When using multiple buttons, they should be well organized on the layout by the action priority. The primary button appears to the right and any less priority buttons appear to the left. The buttons placement normally show consistency throughout a product, platform or company style.  

* __Primary__ – triggers the main CTA on a page.
* __Secondary__ – provides an alternative option to the primary action on a page.
* __Tertiary__ - buttons are usually used any other action except in Action Panels.

## The Button Types

### The Primary Button
The primary button should be only one per layout to trigger the most important CTA. It may be used in conjunction with a secondary button indicating the secondary action.  Ex.: Primary: Save and Secondary: Cancel.

The primary button is displayed as a filled container by solid color around a text label.

### Secondary Button
They contain important actions but not the primary one of the product/platform. They display a stroke around a text label.

### Tertiary Buttons

The layout could have more than one button at a time. They should be carefully organized, follow the __Buttons order__ principles and hierarchy. 

The text buttons are typically used for low priority actions (_Tertiary buttons_). Usually they are used with cards & dialogs.

### Toggle/Icon Button 

Simply is just an icon or icon in a container. Mostly are used in [Action panels](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/action-panel), list items & toolbars. They are commonly found in product/platform bars and toolbars.

## Button alignment
Button alignment depends on where the buttons appear I.e. modals, side panels, etc. The alignment depends on the fact is there only one button, buttons pair or buttons groups.

* __Primary buttons always appear to the right of the page layout__. Secondary buttons appear to the left of the primary button.
* __Secondary buttons always appear to the left to the primary action__.  Secondary buttons appear to the left of the primary button.
* __Tertiary buttons always appear to the right of the page layout__.  Tertiary buttons appear to the right of the page.

## Primary
The primary button is the main button at the layout. This high-emphasis button commands the most attention. Should be only one per layout. The primary button should indicate that can trigger the main important action. Primary buttons should be used in situations where the user may want to go `next`, `complete`, `start`, a task etc.

### Anatomy
The primary button is the contained button. In general, is displayed as a filled container by solid color around a text label.

<img src="https://user-images.githubusercontent.com/10553294/79493533-47cfbd80-802a-11ea-98a6-6cfc8ae901bc.png" width="100%" alt="Primary"/>

> The height should be `3em`, following the responsive design principles and prevent potential issues on a mobile version. The text label should be Sentence case capitalization is best because it conveys a friendly tone that invites users to press the button. Keep text label consistency at a product level. The text label size should be `1em`.

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Text label | The text labels should clearly indicate the action of the button. |
| 2 | Container | Filled container by solid color around a text label. |

### Behavior

#### Focus Sate

<img src="https://user-images.githubusercontent.com/10553294/79495609-86b34280-802d-11ea-804c-bfcc4cd59b14.png" width="100%" alt="Primary"/>

> The container color changes to `#3a86c9` and the border use `3px/0.1875em` and border color `#566FE6`

| # | Button |
| - | ------ |
| 1 | Regular Primary Button |
| 2 | Focused Primary Button |

#### Hover State

<img src="https://user-images.githubusercontent.com/10553294/79495892-f5909b80-802d-11ea-913d-af29467571ff.png" width="100%" alt="Primary"/>

> On hover the container color is `#E9EAEA` and the text label color is `#337AB7`

| # | Button |
| - | ------ |
| 1 | Regular Primary Button |
| 2 | Hovered Primary Button |

#### Disable State

<img src="https://user-images.githubusercontent.com/10553294/79496106-561fd880-802e-11ea-938f-8ed00af8c3fc.png" width="100%" alt="Primary"/>

> Once the button is disabled the container color is `#E2E2E2` and the text label color is `#FFFFFF`

| # | Button |
| - | ------ |
| 1 | Regular Primary Button |
| 2 | Disabled Primary Button |

### Specifications

<img src="https://user-images.githubusercontent.com/10553294/81048744-90f68d00-8ec5-11ea-8485-e6869d879c5b.png" width="100%" alt="Primary"/>

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Text label | <ul><li>Typeface</li> <li>Font</li> <li>Size</li> <li>Color</li> <li>Case</li> <li>Padding top/bottom</li> <li>Padding left/right</li></ul> |  <ul><li>System Default</li> <li>Medium</li> <li>`0.875em`</li> <li>`#FFFFFF`</li> <li>Sentence-case</li> <li>`1em`</li> <li>`2em`</li></ul> |
| Container | <ul><li>Radius</li> <li>Color</li> <li>Height</li> <li>Width</li></ul> | <ul><li>`1.875em`</li> <li>`#337AB7`</li> <li>`3em`</li> <li>Text label length + `2x2em`</li></ul> |

> Normally, users are scanning text rather than reading word for word in order to absorb the main points of a page. The button text label should be big enough for a user to scan it. The optimal web font size is `1em`.

## Secondary

The secondary button is the alternative option for the CTA. Normally, it accompanied the primary button and follow the company Buttons concept I.e. The Secondary / Primary button order (secondary to the left and primary to the right). The secondary button could be positioned in a pair with the Primary one.

Secondary buttons are the alternative we give users to the primary action. They could be the `go back` to the primary button’s `next`, or the `cancel` button to the `submit` button.

### Anatomy 

The secondary button is an outlined button. They display a stroke around a text label.

<img src="https://user-images.githubusercontent.com/10553294/79497932-30e09980-8031-11ea-9b04-9305c8a3fed0.png" width="100%" alt="Secondary"/>

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Text label | The text labels should clearly indicate the action of the button. |
| 2 | Container | Stroked container around a text label. |

### Behavior

#### Focus Sate
<img src="https://user-images.githubusercontent.com/10553294/79498477-0e02b500-8032-11ea-81ed-13072418c585.png" width="100%" alt="Secondary"/>

> The container color changes to `#3a86c9` and the border use `3px/0.1875em` and border color `#566FE6`

| # | Button |
| - | ------ |
| 1 | Regular Secondary Button |
| 2 | Focused Secondary Button |

####  Hover Sate
<img src="https://user-images.githubusercontent.com/10553294/79498518-207cee80-8032-11ea-9280-0dc276d91db7.png" width="100%" alt="Secondary"/>

> On hover the container color is `#E9EAEA` and the text label color is `#337AB7`

| # | Button |
| - | ------ |
| 1 | Regular Secondary Button |
| 2 | Hovered Secondary Button |

####  Disable Sate
<img src="https://user-images.githubusercontent.com/10553294/79498548-2bd01a00-8032-11ea-9f00-1722d0a07da4.png" width="100%" alt="Secondary"/>

> Once the button is disabled the container and the text label color is `#E2E2E2`

| # | Button |
| - | ------ |
| 1 | Regular Secondary Button |
| 2 | Disabled Secondary Button |

### Specifications

<img src="https://user-images.githubusercontent.com/10553294/81048761-9a7ff500-8ec5-11ea-929f-453ac2ce1e6c.png" width="100%" alt="Secondary"/>

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Text label | <ul><li>Typeface</li> <li>Font</li> <li>Size</li> <li>Color</li> <li>Case</li> <li>Padding top/bottom</li> <li>Padding left/right</li></ul> |  <ul><li>System Default</li> <li>Medium</li> <li>`0.875em`</li> <li>`#337AB7`</li> <li>Sentence-case</li> <li>`1em`</li> <li>`2em`</li></ul> |
| Container | <ul><li>Radius</li> <li>Border</li> <li>Border Color</li> <li>BG color</li> <li>Height</li></ul> | <ul><li>`1.875em`</li> <li>`2px/0.125em`</li> <li>`#337AB7`</li> <li>Transparent</li><li>`3em`</li></ul> |

## Tertiary
Tertiary buttons are usually used for low priority actions is important but may not be what the user is looking to do right now. This is things like `add`, `edit`, or `delete` if they aren’t a primary action.

### Anatomy
The Tertiary buttons are text buttons. The text label is the most important element of the text button, as it describes the action that will be performed.

<img src="https://user-images.githubusercontent.com/10553294/79499493-b82f0c80-8033-11ea-993e-fa596a2f121b.png" width="100%" alt="Tertiary"/>

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Text label | The text labels should clearly indicate the action of the button. |

### Behavior 

#### Focus Sate
<img src="https://user-images.githubusercontent.com/10553294/79500323-ee20c080-8034-11ea-85a6-1d94f95ecbaf.png" width="100%" alt="Tertiary"/>

> `3px/0.1875em` border with color `#566FE6`  

| # | Button |
| - | ------ |
| 1 | Regular Tertiary Button |
| 2 | Focused Tertiary Button |

####  Hover Sate
<img src="https://user-images.githubusercontent.com/10553294/79500355-f5e06500-8034-11ea-8eea-2988169d3f0f.png" width="100%" alt="Tertiary"/>

> On hover the container color is `#E9EAEA` 

| # | Button |
| - | ------ |
| 1 | Regular Tertiary Button |
| 2 | Hovered Tertiary Button |

####  Disable Sate
<img src="https://user-images.githubusercontent.com/10553294/79500382-ff69cd00-8034-11ea-974d-d6e92a495b49.png" width="100%" alt="Tertiary"/>

> Once the button is disabled the text label color is `#E2E2E2`

| # | Button |
| - | ------ |
| 1 | Regular Tertiary Button |
| 2 | Disabled Tertiary Button |

### Specifications

<img src="https://user-images.githubusercontent.com/10553294/81048799-ac619800-8ec5-11ea-9fac-7d23b1f037a0.png" width="100%" alt="Tertiary"/>

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Text label | <ul><li>Typeface</li> <li>Font</li> <li>Size</li> <li>Color</li> <li>Case</li> <li>Padding top/bottom</li> <li>Padding left/right</li></ul> |  <ul><li>System Default</li> <li>Medium</li> <li>`0.875em`</li> <li>`#337AB7`</li> <li>Sentence-case</li> <li>`1em`</li> <li>`2em`</li></ul> |

## Icon buttons

Toggle buttons, generally are [Icons](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography) and are only used in [Action Panels](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/action-panel).

Icon buttons are commonly found in product/platform bars and toolbars. Icon buttons can be used to group related options and allow a single choice to be selected or deselected, such as adding or removing a star/hearth (favorite list) to an item.  

### Icon button Anatomy

<img src="https://user-images.githubusercontent.com/10553294/81074824-37588780-8ef2-11ea-83f0-a5f9ad7c7036.png" width="100%" />

> For reference check the Iconography section https://amplify.git-pages.ecd.axway.org/design-system-2020/#/action-panel?id=specification  

### Outlined Icon button Anatomy

<img src="https://user-images.githubusercontent.com/10553294/81075038-83a3c780-8ef2-11ea-976c-bb348a764cc5.png" width="100%" />

> For reference check the Iconography section https://amplify.git-pages.ecd.axway.org/design-system-2020/#/action-panel?id=specification-1  

### Behavior

#### Focus Sate

| # | Button |
| - | ------ |
| 1 | Regular Icon Button |
| 2 | Focused Icon Button |

<img src="https://user-images.githubusercontent.com/10553294/81075069-8e5e5c80-8ef2-11ea-8a4c-c368d2e86703.png" width="100%" />

> The container color changes to `#3a86c9` and the border use `3px/0.1875em` and border color `#566FE6`

##### Icon Button with Container

<img src="https://user-images.githubusercontent.com/10553294/81075086-93bba700-8ef2-11ea-920d-921933893ec3.png" width="100%" />

> The container color changes to `#3a86c9` and the border use `3px/0.1875em` and border color `#566FE6`

#### Hover Sate

| # | Button |
| - | ------ |
| 1 | Regular Icon Button |
| 2 | Hovered Icon Button |

<img src="https://user-images.githubusercontent.com/10553294/81075159-a9c96780-8ef2-11ea-8a10-aed7384905ae.png" width="100%" />

> On hover the container color is `#E9EAEA` and the text label color is `#337AB7`

##### Icon Button with Container

<img src="https://user-images.githubusercontent.com/10553294/81075105-9ae2b500-8ef2-11ea-95c8-cd0895fa5b1d.png" width="100%" />

> On hover the container color is `#E9EAEA` and the text label color is `#337AB7`

#### Disable Sate

| # | Button |
| - | ------ |
| 1 | Regular Icon Button |
| 2 | Disabled Icon Button |

<img src="https://user-images.githubusercontent.com/10553294/81075234-bb127400-8ef2-11ea-8bdd-00c135d3852e.png" width="100%" />

> Once the button is disabled the container color is `#E2E2E2` and the text label color is `#9A9A9A`

##### Icon Button with Container

<img src="https://user-images.githubusercontent.com/10553294/81075241-c06fbe80-8ef2-11ea-8e51-7da0e824a5f4.png" width="100%" />

> Once the button is disabled the container color is `#E2E2E2` and the text label color is `#9A9A9A`

### Specifications

<img src="https://user-images.githubusercontent.com/10553294/81075268-c9609000-8ef2-11ea-8951-c310cfb97f11.png" width="100%" />

| Element | Attribute | Values |
| ------- | --------- | ------ |
| Icon | <ul><li>Width</li><li>Height</li> <li>Color</li> <li>BG color</li></ul> | <ul><li>`1.25em`</li> <li>`1.25em`</li> <li>`#337AB7`</li> <li>Transparent</li></ul> |

#### Icon Button with Container

<img src="https://user-images.githubusercontent.com/10553294/81075301-d4b3bb80-8ef2-11ea-87eb-345844d6a10e.png" wwidth="100%" />

| Element | Attribute | Values |
| ------- | --------- | ------ |
| Icon | <ul><li>Width</li><li>Height</li> <li>Color</li> <li>BG color</li></ul> | <ul><li>`1.25em`</li> <li>`1.25em`</li> <li>`#337AB7`</li> <li>Transparent</li></ul> |
| Container | <ul><li>Radius</li><li>Border</li><li>Border Color</li><li>BG color</li><li>Width</li><li>Height</li></ul> | <ul><li>`0.625em`</li><li>`2px/0.125em`</li><li>`#337AB7`</li><li>Transparent</li><li>`3em`</li><li>`3em`</li></ul> |

## Destructive Buttons 

> Destructive buttons are used to indicate a destructive action to the user, like permanently erasing data, remove, delete, cancel, etc.

### Usage

Destructive buttons have a different visual style to inform users of potentially destructive actions they are about to take. If using the destructive button as a standalone, we recommend styling it as a Secondary button. Within a set, the destructive button should be styled as a Primary button.

### Primary Destructive Buttons & Behavior

<img src="https://user-images.githubusercontent.com/10553294/81079950-e1d3a900-8ef8-11ea-9e27-4c10ad35559e.png" width="100%" alt="Destructive" />

| Element | Attribute | Values |
| ------- | --------- | ------ |
| Destructive | <ul><li>Text label Color</li><li>Container Color</li></ul> | <ul><li>`#FFFFFF`</li> <li>`#A50034`</li></ul> |
| Hovered | <ul><li>Text label Color</li><li>Container Color</li></ul> | <ul><li>`#A50034`</li> <li>`#E9EAEA`</li></ul> |
| Focused | <ul><li>Border Color</li><li>Border Size</li></ul> | <ul><li>`#566FE6`</li><li>`3px/0.1875em`</li></ul> |
| Disabled | <ul><li>Text label Color</li><li>Container Color</li></ul> | <ul><li>`#FFFFFF`</li> <li>`#E9EAEA`</li></ul> |

### Secondary Destructive Buttons & Behavior

<img src="https://user-images.githubusercontent.com/10553294/81079963-e5ffc680-8ef8-11ea-8121-d467017e8b2c.png" width="100%" alt="Destructive" />

| Element | Attribute | Values |
| ------- | --------- | ------ |
| Destructive | <ul><li>Text label Color</li><li>Border Color</li></ul> | <ul><li>`#A50034`</li> <li>`#A50034`</li></ul> |
| Hovered | <ul><li>Text label Color</li><li>Border Color</li></ul> | <ul><li>`#A50034`</li> <li>`#E9EAEA`</li></ul> |
| Focused | <ul><li>Border Color</li><li>Border Size</li></ul> | <ul><li>`#566FE6`</li><li>`3px/0.1875em`</li></ul> |
| Disabled | <ul><li>Text label Color</li><li>Border Color</li></ul> | <ul><li>`#FFFFFF`</li> <li>`#E9EAEA`</li></ul> |

### Tertiary Destructive Buttons & Behavior

<img src="https://user-images.githubusercontent.com/10553294/81079984-eac47a80-8ef8-11ea-9681-34055a691b3b.png" width="100%" alt="Destructive" />

| Element | Attribute | Values |
| ------- | --------- | ------ |
| Destructive | <ul><li>Text label Color</li></ul> | <ul><li>`#A50034`</li></ul> |
| Hovered | <ul><li>Text label Color</li><li>BG Color</li></ul> | <ul><li>`#A50034`</li> <li>`#E9EAEA`</li></ul> |
| Focused | <ul><li>BG Border Color</li><li>Border Size</li></ul> | <ul><li>`#566FE6`</li><li>`3px/0.1875em`</li></ul> |
| Disabled | <ul><li>Text label Color</li><</ul> | <ul><li>`#E9EAEA`</li></ul> |

### Icon Destructive Buttons & Behavior

<img src="https://user-images.githubusercontent.com/10553294/81048864-c8653980-8ec5-11ea-8e6f-e2e3d75103eb.png" width="100%" alt="Destructive" />

| Element | Attribute | Values |
| ------- | --------- | ------ |
| Destructive | <ul><li>Icon Color</li></ul> | <ul><li>`#A50034`</li></ul> |
| Hovered | <ul><li>Icon Color</li><li>BG Color</li></ul> | <ul><li>`#A50034`</li> <li>`#E9EAEA`</li></ul> |
| Focused | <ul><li>BG Border Color</li><li>Border Size</li></ul> | <ul><li>`#566FE6`</li><li>`3px/0.1875em`</li></ul> |
| Disabled | <ul><li>Icon Color</li><</ul> | <ul><li>`#E9EAEA`</li></ul> |

### Border Icon Destructive Buttons & Behavior

<img src="https://user-images.githubusercontent.com/10553294/81048874-cd29ed80-8ec5-11ea-8299-646544254aa7.png" width="100%" alt="Destructive" />

| Element | Attribute | Values |
| ------- | --------- | ------ |
| Destructive | <ul><li>Icon Color</li><li>Border Color</li></ul> | <ul><li>`#A50034`</li> <li>`#A50034`</li></ul> |
| Hovered | <ul><li>Icon Color</li><li>Border Color</li></ul> | <ul><li>`#A50034`</li> <li>`#E9EAEA`</li></ul> |
| Focused | <ul><li>Border Color</li><li>Border Size</li></ul> | <ul><li>`#566FE6`</li><li>`3px/0.1875em`</li></ul> |
| Disabled | <ul><li>Icon Color</li><li>Border Color</li></ul> | <ul><li>`#FFFFFF`</li> <li>`#E9EAEA`</li></ul> |

!> The final color palette should be provided by the Marketing Department.