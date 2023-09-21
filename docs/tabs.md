> Tabs are used to quickly navigate between views within the same context. They organize content across different screens, data sets, and other interactions.

## Usage

Tabs organize and allow navigation between groups of content that are related and at the same level of the hierarchy. Tabs keeps related content that is shown and hidden through navigation. Each tab should contain content that is distinct from other tabs in a set. For example, tabs can present different sections of news, different genres of music, or different themes of documents.

### Good Principles

* __Scalable__ - UI could have as many tabs as needed. In most scenarios, you should use no more than six tabs. This maintains an uncluttered UI and reduces cognitive load for users. If more than six tabs are needed, consider other navigation patterns, such as side navigation.
* __Informative__ - Tabs organize content into categories to help users easily find different types of information. Each tab label describes the content contained within it.
* __Peers__ – should be displayed next to each other as peers. Tab order should be consistent across an experience. Tabs with related content should be grouped adjacent to each other.

### Variations

There are two variations of tabs, default and container. They are hierarchically the same and should never be nested within each other. 

* __Default__ - A standalone tab/(s) that can also be nested within components. It is commonly used with smaller content areas. We review them in detail under the Tabs section. 
* __Container__ - An emphasized tab that is always paired with an attached background container. It is commonly used for larger content areas, like sub-pages. We review them in detail under the Tabs with a Dropdown section. 

## Tabs

> The default tabs are used to quickly navigate between views within the same context.

### Anatomy

<img src="https://user-images.githubusercontent.com/10553294/81408172-6c104d00-9145-11ea-93dc-758720a9f1f3.png" width="100%" alt="Tabs" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Tab Container | Stroked container around a tab header. Container improve the discoverability of the tab by creating a contrast between the surrounding content. |
| 2 | Tab Header | Tab Header should clearly and succinctly describe the content of the tab they represent. Tab Headers appear in a single row. Each tab label describes the content contained within it. Headers are concise and use no more than two words. The character length of a Header will impact the experience as well, keep the length less as possible. Do not use icons in tab labels. |
| 3 | Tab Shape | Generally, the tab container is a partial button container. The shape is consistent and with common design style. The tab header has top/bottom & left/right padding helping for better visual acceptance. |

### Behavior

> Tabs are used to quickly navigate between different views. 
 
__Moving between tabs__

Users can navigate between tabs by tapping a tab, once the action was preformed navigate you to a specific view. 

__Tap a tab__

Navigate to a tab by tapping on it. 

#### Focus State

<img src="https://user-images.githubusercontent.com/10553294/81408191-73cff180-9145-11ea-95f2-94323f293d2c.png" width="100%" alt="Tabs" />

> On focus, a tab is outlined with a `3px` border & color - `#566FE6`. 

#### Hover State

<img src="https://user-images.githubusercontent.com/10553294/81408199-77637880-9145-11ea-960c-a168971c784f.png" width="100%" alt="Tabs" />

> On hover state, the tab container changes the background color to #E9EAEA. 

#### Active State

<img src="https://user-images.githubusercontent.com/10553294/81408223-80544a00-9145-11ea-90e3-e49c1afbc112.png" width="100%" alt="Tabs" />

> If an item is currently selected, the tab container changes colors, the tab header is #FFFFFF and the background color is #407CA0.  

#### Disabled State
<img src="https://user-images.githubusercontent.com/10553294/81408231-834f3a80-9145-11ea-8d19-70e2924f9196.png" width="100%" alt="Tabs" />

> Once the tab is disabled, the tab container border and the tab header become #E2E2E2 

### Specification

<img src="https://user-images.githubusercontent.com/10553294/81408238-86e2c180-9145-11ea-9949-ebac05bd349c.png" width="100%" alt="Tabs" />

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Tab Header | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Top/Bottom Padding</li><li>Left/Right Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1.25em`</li><li>`#000000`</li><li>Sentence-case</li><li>`1em`</li><li>`2em`</li></ul> |
| Tab Container | <ul><li>Border Color</li><li>BG Color</li><li>Border Radius (_Left/Right upper corner_)</li></ul> | <ul><li>`#676767`</li><li>`#FFFFFF`</li><li>`0.625em`</li></ul> |

> The tab container is simply partial Secondary Button for reference check the Buttons section

## Tabs with Dropdown

Tabs with Dropdown is like tabs with Picklist.

On tap of specific tab expand a widget that displays a list of predefined selectable options.

### Anatomy

<img src="https://user-images.githubusercontent.com/10553294/81410087-dbd40700-9148-11ea-9d60-adeb582064f4.png" width="100%" alt="Tabs with Dropdown" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Tab Container | Stroked container around a tab header. Container improve the discoverability of the tab by creating a contrast between the surrounding content. |
| 2 | Tab Header | Tab Header should clearly and succinctly describe the content of the tab they represent. Tab Headers appear in a single row. Each tab label describes the content contained within it. Headers are concise and use no more than two words. The character length of a Header will impact the experience as well, keep the length less as possible. Do not use icons in tab labels. |
| 3 | Tab Label (_Label + Icon_) | Tab Label contains text label & Action Icon. In general, is a read-only input field, informs the user regarding the Selections list purpose. |
| 4 | Active Picklist Label | Selected Tab Label which expand the Selections list. |
| 5 | Dropdown Container | The List box container displayed by stroke border. |
| 6 | Selections list | The Selection list is a list box of pre-defined options. |

### Behavior

> Users can navigate between tabs by tapping a tab, once the action was preformed expand the Dropdown with predefined options.

#### Focus State

<img src="https://user-images.githubusercontent.com/10553294/81410111-e4c4d880-9148-11ea-9341-cde068f21ba1.png" width="100%" alt="Tabs with Dropdown" />

> On focus, a tab is outlined with a `3px` border & color - `#566FE6`. 

#### Hover State

<img src="https://user-images.githubusercontent.com/10553294/81410128-e9898c80-9148-11ea-88cf-e468d7922b79.png" width="100%" alt="Tabs with Dropdown" />

> On hover state, the tab container changes the background color to `#E9EAEA`.

#### Active State

<img src="https://user-images.githubusercontent.com/10553294/81410146-ee4e4080-9148-11ea-8009-0680891edbea.png" width="100%" alt="Tabs with Dropdown" />

> If an item is currently selected, the tab container changes colors, the tab header is `#FFFFFF` and the background color is `#407CA0`. 

#### Disabled State

<img src="https://user-images.githubusercontent.com/10553294/81410190-002fe380-9149-11ea-8506-7b680668843f.png" width="100%" alt="Tabs with Dropdown" />

> Once the tab is disabled the tab container border and the tab header become #E2E2E2 

### Specification
<img src="https://user-images.githubusercontent.com/10553294/81410208-0625c480-9149-11ea-92a1-88860ef9c5c6.png" width="100%" alt="Tabs with Dropdown" />

| Item | Attribute | Value |
| ---- | --------- | ----- |
| Label | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Top/Bottom Padding</li><li>Left/Right Padding</li></ul> | <ul><li>System Default</li><li>Bold</li><li>`1.25em`</li><li>`#FFFFFF`</li><li>Sentence-case</li><li>`1em`</li><li>`2em`</li></ul> |
| Label Icon | <ul><li>Size</li><li>Color</li><li>Top/Bottom Padding</li><li>Left/Right Padding</li></ul> | <ul><li>Check Iconography</li><li>`#FFFFFF`</li><li>`1em`</li><li>`2em`</li></ul> |
| Active Label + Icon | <ul><li>Color</li><li>BG Color</li></ul> | <ul><li>`#FFFFFF`</li><li>`#337AB7`</li></ul> |
| Selection item | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Height</li><li>Top/Left/Bottom Padding </li><li>Right Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>`#333333`</li><li>Sentence-case</li><li>`3em`</li><li>`1em`</li><li>`2em`</li></ul> |
| Dropdown Container  | <ul><li>Top Padding</li><li>Border Color</li><li>BG Color</li><li>Border Radius</li></ul> | <ul><li>`0.375em`</li><li>`#676767`</li><li>`#FFFFFF`</li><li>`0.625em`</li></ul> |

!> The final color palette should be provided by the Marketing Department.