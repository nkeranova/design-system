> Tags are elements used to label, categorize, or organize items using keywords that describe them.

## Usage

Use tags to visually label UI objects for quick recognition and navigation. Tags can be used for various types of objects, including free form text, predefined text, rules, or contacts. Keep in mind that tags increase the amount of visual noise, particularly when combined with other visual labelling elements, so use them in moderation.

The Tag is compact elements that represent an input, attribute, or action. Those elements allow users to enter information, make selections, filter content, or trigger actions.

### Best principles
* __Compact__ - compact components that represent discrete information. 
* __Relevant__ - should have a clear and helpful relationship to the content. 
* __Focused__ - should make tasks easier to be complete 

### When to use
* Use tags when content is mapped to multiple categories, and the user needs a way to differentiate between them.
* Use tags as a method of filtering data, to show only items within that category.

## Anatomy
> Use short labels for easy scanning.

<img src="https://user-images.githubusercontent.com/10553294/84795720-84a33b00-b000-11ea-88cc-169e4f270bb2.png" width="100%" alt="Tag" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Tag Label | Tag Label text is used to inform users as for what the used tag stands for. Every tag should have a label. |
| 2 | Dismiss Tag Icon | Close Icon will dismiss the alert. Check Iconography. |
| 3 | Tag Container | Displayed by stroke around a tag label. Containers improve the discoverability of the element by creating a contrast between the tag and the surrounding content. |

## Behavior
> Tags can be permanent or removable (by displaying the remove icon). 

### Adding Tag

<img src="https://user-images.githubusercontent.com/10553294/84795735-8967ef00-b000-11ea-90fc-d2cf68baf270.png" width="100%" alt="Tag" />

> Adding a new Tag could be done via typing in the Tags Input Field and pressing Enter. On focus, the tag input is outlined with a `3px` border & color is `#566FE6`. Once you add tag it’s shown immediately below the field. The padding between the Input & Tag is 0.75em. 

### Removing Tag

<img src="https://user-images.githubusercontent.com/10553294/84795746-8d940c80-b000-11ea-890f-71f003b5bfbd.png" width="100%" alt="Tag" />

> Removing a Tag could be done via the dismiss icon. On focus, the tag is outlined with a `3px` border & color is `#566FE6`. Once you hit the dismiss icon the tag disappears immediately.

## Specification

<img src="https://user-images.githubusercontent.com/10553294/84795755-908efd00-b000-11ea-9546-6d7c3f5727ee.png" width="100%" alt="Tag" />

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Tag Label | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Top/Bottom/Left Padding</li><li>Right Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>`#000000`</li><li>Sentence-case</li><li>`0.75em`</li><li>`0.5em`</li></ul> |
| Tag Container | <ul><li>Border Size</li><li>Border Color</li></ul> | <ul><li>`1px`</li><li>`#929292`</li></ul> |
| Dismiss Icon | <ul><li>Size</li><li>Color</li><li>Top/Bottom/Right Padding</li><li>Left Padding</li></ul> | <ul><li>`0.75em x 0.75em` (_Check Iconography_)</li><li>`#000000`</li><li>`0.75em`</li><li>`0.5em`</li></ul> | 