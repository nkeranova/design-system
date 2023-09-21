> Tooltips display additional information upon click, hover, or focus. The information should be contextual, useful, and nonessential. 

## Usage

A Tooltip is a small piece of contextual information about an element on the screen, which is displayed when a user hovers or focuses on the element it is describing.  

Use tooltips to identify or add a small amount of information to an element. Typically, tooltips are used to help users understand the meaning or purpose of icons, showing the full version of a truncated text, or even displaying the alt text for an image. 

### Best principles
* __Transient__ - Tooltips appear on hover, focus, or touch, and disappear after a short duration.
* __Paired__ - Tooltips are always placed nearby the element with which they are associated.
* __Succinct__ - Tooltips typically include short, descriptive text and optionally link to the documentation.

### Types
* __Icon__ tooltip 
* __Definition__ tooltip 
* __Interactive__ tooltip 

### Placement

Icon tooltips and interactive tooltips may be positioned top, bottom, left, or right to the trigger item. The container of the tooltip text may be aligned to start, center or end. 

## Anatomy

Tooltips display informative text when users hover over or focus on an element.

<img src="https://user-images.githubusercontent.com/10553294/84898707-5b41e800-b0b0-11ea-8cb2-076884131174.png" width="100%" alt="Tooltip" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Tooltip Container | Tooltip Container with arrow depends on the position. Typically, the arrow is oriented to the Info Icon. Displayed by stroke around a tooltip content. Containers improve the discoverability of the element by creating a contrast between the tooltip and the surrounding content. |
| 2 | Title | Displays the Tooltip Title. Should be brief and descriptive. |
| 3 | Body | Displays additional information of specific element as a tooltip. There should be a character count limit. The tooltip height depends on the text length. |

### Tooltip with Link

<img src="https://user-images.githubusercontent.com/10553294/84898724-6137c900-b0b0-11ea-9608-c5e1570f29b9.png" width="100%" alt="Tooltip" />

| # | Element | Description |
| - | ------- | ----------- |
| 4 | Link | Link redirects the user to official documentation or additional recourses. |

## Behavior

A tooltip is displayed upon hovering or focusing over it (Desktop). Continuously display the tooltip as long as the user long-presses or hovers over the element.

Display the tooltip until the user takes another action and the tooltip will disappear.

The position of tooltips is flexible and will change depending on how close the element is to the edge of the screen.

The tooltips appear on a hover and focus of the Info Icon. Interactive tooltips may contain rich text and other interactive elements like links. Interactive tooltips are best used for onboarding experiences and product tours.

### On Hover

<img src="https://user-images.githubusercontent.com/10553294/84898759-6bf25e00-b0b0-11ea-825f-141557e36637.png" width="100%" alt="Tooltip" />

> On hover of the Info Icon the tooltips appear, stays until the user takes another action, then the tooltip disappears. On hover the icon background container becomes `60%` of `#C8C9C7`. Reference – [Iconography](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography) & [Action Panels](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/action-panel)

### On Focus

<img src="https://user-images.githubusercontent.com/10553294/84898769-701e7b80-b0b0-11ea-98ad-10b7cc71e247.png" width="100%" alt="Tooltip" />

> On a focus of the Info Icon the tooltips appear, stays until the user takes another action, then the tooltip disappears. On focus the icon background container border becomes `3px` of `#566FE6`. Reference – [Iconography](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography) & [Action Panels](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/action-panel)

## Specification

<img src="https://user-images.githubusercontent.com/10553294/84898779-757bc600-b0b0-11ea-9f4d-b924d9b43084.png" width="100%" alt="Tooltip" />

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Title | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Top / Left Padding</li><li>Bottom Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1.5em`</li><li>Sentence case</li><li>`#000000`</li><li>`1.5em`</li><li>`1em`</li></ul> |
| Body | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Left / Right / Bottom Padding</li><li>Top Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.875em`</li><li>Sentence case</li><li>`#000000`</li><li>`1.5em`</li><li>`1em`</li></ul> |
| Container | <ul><li>Border Color</li><li>Border Radius</li></ul> | <ul><li>`#707070`</li><li>`0.625em`</li></ul> |

### Tooltip with Link

<img src="https://user-images.githubusercontent.com/10553294/84898795-7a407a00-b0b0-11ea-8f90-3ea5815aa84f.png" width="100%" alt="Tooltip" />

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Link | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Case</li><li>Color</li><li>Left / Right / Bottom Padding</li><li>Top Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`1em`</li><li>Sentence case</li><li>`#006580`</li><li>`1.5em`</li><li>`1em`</li></ul> | 

!> Optionally a Documentation Link Icon could be added. Reference - [Iconography](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/iconography)
 