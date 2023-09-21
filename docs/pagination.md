## Usage

Pagination is required for all data tables, list and card layouts except if they have less than 20 records and are all currently displayed on the page.

## Anatomy

Pagination is required for all data tables and list except if they have less than 20 records and are all currently displayed on the page.

<img src="https://user-images.githubusercontent.com/10553294/78794613-a8bd1d00-79bc-11ea-8f4c-804fef9c8448.png" width="80%"  alt="Anatomy"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 1 | 1<sup>st</sup> Page Selector | On Page open, Page 1 is active by default until the user navigates to another page. When the user navigates to another page, Page 1 selector is deactivated and becomes a link to return to the first page |
| 2 | Last Page Selector | Displays the last page. Is a link to navigate to the last page. In not active until the user is on the last page |
| 3 | Kebab Icon | Displays kebab icon to indicate that there are more pages.  This icon is not a link |
| 4 | Next Page Selector | <ul type="bullet"><li>Link to paginate to the next page in the sequence</li> <li>The link is hidden when the user is on the last page</li>  <li>When the user clicks/taps on the Next Page Selector on the First Page Pagination Panel, the First Page Pagination Panel is switched with the Pagination Panel starting with page #5</li> |
| 5 | Page Selectors in the First Page Pagination Panel | Links to the first four pages |
| 6 | Previous Page Selector | <ul type="bullet"><li>Link to paginate to the previous page in the sequence</li> <li>The link is hidden when the user is on the 1<sup>st</sup> Page Selector</li> <li>When the user clicks/taps on the Previous Page Selector on the Last Page Pagination Panel, the Last Page Pagination Panel is switched with the Pagination Panel starting with page Last Page minus 4</li>  |
| 7 | Page Selectors in Pagination Panel | Links to any four pages (in sequential order) |
| 8 | Page Selectors in Last Page Pagination Panel | Links to any last four pages (in sequential order) |

## Behaviour

### First Page Selector Interaction

<img src="https://user-images.githubusercontent.com/10553294/78796767-6fd27780-79bf-11ea-91eb-4a1afe6d1a0f.png" width="80%" alt="First Page Selector Interaction"/>

> If the user is either on the Last Page Pagination Panel or the Pagination Panel and clicks/taps on the First Page Selectors, the Panel switches to the First Page Pagination Panel in an active stage and loads the first page.

### Last Page Selector Interaction

<img src="https://user-images.githubusercontent.com/10553294/78796940-b58f4000-79bf-11ea-96e0-9a9f9ede3187.png" width="80%" alt="Last Page Selector Interaction"/>

> If the user is either on the First Page Pagination Panel or the Pagination Panel and clicks/taps on the Last Page Selectors, the Panel switches to the Last Page Pagination Panel in an active stage and loads the last page.

### Next Page Selector Interaction

<img src="https://user-images.githubusercontent.com/10553294/78797302-2e8e9780-79c0-11ea-93cd-91f7e212a559.png" width="80%" alt="Next Page Selector Interaction"/>

1. If the user is on the first page and clicks/taps on the Next Page Selector, the First Page Pagination Panel switches to the Pagination Panel (#2). 

1. If the user clicks/taps on the Next Page Selector (#3) the page counts one page up in the Page Selectors in Pagination Panel (#4) 

### Previous Page Selector Interaction

<img src="https://user-images.githubusercontent.com/10553294/78797489-701f4280-79c0-11ea-9676-3f5e1812eee3.png" width="80%" alt="Previous Page Selector Interaction"/>

3. If the user is on the last page and clicks/taps on the Previous Page Selector, the Last Page Pagination Panel switches to the Pagination Panel (#2). 

4. If the user clicks/taps on the Previous Page Selector (#3) the page counts one page down in the Page Selectors in Pagination Panel (#4) 

### Focus Stat

<img src="https://user-images.githubusercontent.com/10553294/78797692-b4aade00-79c0-11ea-8c5f-a1d1038842ea.png" width="80%" alt="Focus Stat"/>

> On focus, an item is outlined with a `3px` border. The border color is `#566FE6`

### Hover State

<img src="https://user-images.githubusercontent.com/10553294/78797813-e623a980-79c0-11ea-97f2-0a00f1a8f715.png" width="80%" alt="Hover State"/>

> On hover state, the list item changes color (the final color is still  TBD). For testing the bg color is `#E9EAEA`

### Active State

<img src="https://user-images.githubusercontent.com/10553294/78797997-2125dd00-79c1-11ea-9107-b934499bd607.png" width="80%" alt="Active State"/>

> If a CTA is selected, the CTA changes colors (final colors are still TBD).  For testing the icons are `#FFFFFF` and the bg color is `#407CA0`

## Specification

<img src="https://user-images.githubusercontent.com/10553294/78798229-65b17880-79c1-11ea-8a93-21c521021b17.png" width="80%"  alt="Pagination"/>

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Page Selector(s) | Typeface <br>Font <br>Size <br>Case <br>Font Color <br>Border Color <br>Border Thickness <br>BG Color | System Default <br>Bold <br>`1.25em`  <br>Sentence case <br>`#407CA0` <br>`#407CA0` <br>`1px` <br>`#FFFFFF` |
| Page Selector: Focus | Typeface <br>Font <br>Size <br>Case <br>Font Color <br>Border Color <br>Border Thickness <br>BG Color | System Default <br>Bold <br>`1.25em`  <br>Sentence case <br>`#407CA0` <br>`#566FE6` <br>`3px` <br>`#FFFFFF` |
| Page Selector: Hover | Typeface <br>Font <br>Size <br>Case <br>Font Color <br>Border Color <br>Border Thickness <br>BG Color | System Default <br>Bold <br>`1.25em`  <br>Sentence case <br>`#407CA0` <br>`#407CA0` <br>`1px` <br>`#E2E2E2` |
| Page Selector: Active | Typeface <br>Font <br>Size <br>Case <br>Font Color <br>Border Color <br>Border Thickness <br>BG Color | System Default <br>Bold <br>`1.25em`  <br>Sentence case <br>`#FFFFFF` <br>`#407CA0` <br>`1px` <br>`#407CA0` |