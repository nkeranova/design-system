## Usage
Cards contain content and actions about a single subject.  The card items may include text or text and image. All card elements should be placed on them in a way that clearly indicates hierarchy. Cards are surfaces that display content and actions on a single topic. They should be easy to scan for relevant and actionable information. The additional information in the card items should be short and easily readable.  

## Types

### Card 

A basic card is an item which can be selected individually. Actions can be applied to one singular card item.

Each card includes: 
* Card container 
* Header 
* Details section (supporting text or media) 
* Attributes 
* Action panel 

__& more:__ Thumbnail, Icons, Buttons (_optional_) 

### Cards collection

When multiple cards are present, they are grouped together into a collection. 

In a multi-select card listing several card items can be selected to apply one or multiple actions to the selected card items.  

Each Card collection includes: 
* Sortable column header (_if applicable_)
* Record display 
* Pagination 
* Card items 
* Multi-select option (_if applicable_) 
* Action Panel

## Anatomy
Cards Listing are optimized for scanning and actionable information comprehension. A card list consists of several columns (depending on the used responsive grid) with card items.

### Card Listing 

<img src="https://user-images.githubusercontent.com/10553294/79130400-93c2fe00-7daf-11ea-8195-24efc0035567.png" width="100%" alt="List Item"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 1 | Record Display | Displays how many cards are currently displayed in the screen out of the total # of card items. |
| 2 | Card Item Sorting | Sorts the card items. Functions like a Drop-Down Menu. |
| 3 | Card item | See below for additional information. |
| 4 | Instruction Copy | Displays informative copy for #5. |
| 5 | Drop Down Menu | See Drop Down Menu. |
| 6 | Pagination | See Pagination. |
| 7 | Action Panel | See Action Panel. |

### Card Item
<img src="https://user-images.githubusercontent.com/10553294/79130596-e2709800-7daf-11ea-97b0-6f50de4e0f6f.png" width="100%" alt="List Item"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 1 | Card Title | Displays the Card Item Title. Should be brief and descriptive. |
| 2 | Status of Card Item (optional) | Shows the current status of the item if applicable. |
| 3 | Description of Card Item (optional) | Displays a description of the card item. There should be a character count limit for this text area. |
| 4 | Attribute 1 (optional) | Displays the most important attribute of the card item.  The user may use this attribute to select the Card item.  This may include tags, downloads, etc. |
| 5 | Attribute 2 (optional) | Displays the second important attribute of the card item.  This attribute helps the user to decide to act on this card item. |
| 6 | Attribute 3 (optional) | Displays the third important attribute of the card item.  This attribute helps the user to decide to act on this card item. |
| 7 | Action Panel | Displays the CTA that are applicable to the card items.  Examples are edit, delete, share, like. |

<img src="https://user-images.githubusercontent.com/10553294/79130996-88240700-7db0-11ea-9702-1ca34780bc7a.png" width="100%" alt="List Item"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 10 | Card Checkbox | Displays the Card checkbox. Should be next to the Card Item Title |

> In the following content will give an additional example with a checkbox for each section

### Card Item with Icon

<img src="https://user-images.githubusercontent.com/10553294/79131186-d76a3780-7db0-11ea-93d4-dafe6671df84.png" width="100%" alt="List Item"/>

<img src="https://user-images.githubusercontent.com/10553294/79131198-e05b0900-7db0-11ea-85e4-509ec9aaf92b.png" width="100%" alt="List Item"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 8 | Icon | Use a descriptive icon to identify the Card Item. The icon must be unique and identifying the card item. |

### Card Item with Photo or Logo

<img src="https://user-images.githubusercontent.com/10553294/79131413-3b8cfb80-7db1-11ea-9bce-f672c2445ccd.png" width="100%" alt="List Item"/>

<img src="https://user-images.githubusercontent.com/10553294/79131434-434ca000-7db1-11ea-99c7-181101d5ade7.png" width="100%" alt="List Item"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 9 | Photo | Use a photo with a 4: 3 ratios. The photo illustrates the card listing. It may be a logo or identifying graphic. |

### Cards Items Examples (and Modifications)

> TBD
<!-- <img src="" width="100%" alt="List Item"/> -->

## Behavior

### Focus State

<img src="https://user-images.githubusercontent.com/10553294/79131567-7abb4c80-7db1-11ea-85f2-fe800819d4b2.png" width="100%" alt="List Focus State"/>

> On focus, an item is outlined with a `3px` border. The border color is `#566FE6`

### Hover State

<img src="https://user-images.githubusercontent.com/10553294/79131589-827af100-7db1-11ea-950e-b3199a53f3e7.png" width="100%" alt="List Hover State"/>

> On hover state, the list item changes color (the final color is still TBD). For testing the bg color is `#E9EAEA`

### Active State

<img src="https://user-images.githubusercontent.com/10553294/79131617-89096880-7db1-11ea-9e99-4cc13cdf220c.png" width="100%" alt="List Active State"/>

> If an item is currently selected, the list item changes colors (the final colors are still TBD).  For testing the icons and text are `#FFFFFF` and the bg color is `#407CA0`

## Accessibility
> Ask development teams to add the correct HTML+CSS semantics for accessibility compliance

## Specifications

### Card Item

<img src="https://user-images.githubusercontent.com/10553294/79131732-c110ab80-7db1-11ea-8df3-71fcb87f8ce0.png" width="100%" alt="List Item"/>

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Card Item Title | Typeface <br>Font <br>Size <br>Case <br>Color | System Default <br>Bold <br>`1.75em` <br>Sentence case <br>`#000000` |
| Card Item Status (Optional) | Typeface <br>Font <br>Size <br>Case <br>Color | System Default <br>Regular <br>`1.25em` <br>Sentence case <br>`#000000` |
| Card Item Body (Optional) | Typeface <br>Font <br>Size <br>Case <br>Color | System Default <br>Regular <br>`1.5em` <br>Sentence case <br>#575757 |
| Card Item Attribute(s) - Max 3 (Optional) | Typeface <br>Font <br>Size <br>Case <br>Color | System Default <br>Regular <br>`0.75em` <br>Sentence case <br>`#575757` |

<img src="https://user-images.githubusercontent.com/10553294/79131877-fc12df00-7db1-11ea-8bf8-d44894a811ac.png" width="100%" alt="List Item with Icon"/>

| Element | Attribute | Value |
| - | -------------- | ---------- |
| Card Checkbox | Size | `3em` x `3em` |

### Card Item with Icon

<img src="https://user-images.githubusercontent.com/10553294/79131890-0503b080-7db2-11ea-98b8-6d42b599f507.png" width="100%" alt="List Item"/>

| Element | Attribute | Value |
| - | -------------- | ---------- |
| Icon | Size | `3em` x `3em` |

### Card Item with Photo or Logo

<img src="https://user-images.githubusercontent.com/10553294/79131915-0af99180-7db2-11ea-8b08-c3ca1656f2ea.png" width="100%" alt="List Item with Icon"/>

| Element | Attribute | Value |
| - | -------------- | ---------- |
| Photo | Size | 4: 3 ratios |

## Responsive Grid

### 1400+
<img src="https://user-images.githubusercontent.com/10553294/79143573-2373a700-7dc6-11ea-8477-96b4cc7a8d52.png" width="100%" alt="List Item with Icon"/>

### 1024+
<img src="https://user-images.githubusercontent.com/10553294/79143599-2e2e3c00-7dc6-11ea-9acb-e00353e1ae98.png" width="100%" alt="List Item with Icon"/>

### 839+
<img src="https://user-images.githubusercontent.com/10553294/79143614-35554a00-7dc6-11ea-84a6-578853c695f6.png" width="100%" alt="List Item with Icon"/>

> References: [Grid section](https://amplify.git-pages.ecd.axway.org/design-system-2020/#/grid)