## Usage
Lists are continuous, vertical indexes of items (list items).  The list items may include text, and text and images. List are used to scroll these list items and to get a brief overview of a list item. 

List are preferred for display if a user needs additional information (attributes) or description to decide on an action or selection. The additional information in the list items should be short and easily readable.  

## Types

### List 

A basic list has list items that can be selected individually.  Actions can be applied to one singular list item. 

Each list includes  
* Sortable column header if applicable 
* Record display 
* Pagination 

### Multi-Select List 

In a multi-select list several list items can be selected to apply one or multiple actions to the selected list items.  

Each list includes  
* Sortable column header if applicable 
* Record display 
* Pagination 
* List items 
* Multi-select option 
* Action Panel 

## Anatomy
Lists are optimized for reading comprehension. A list consists of a single continuous column with list items. A list

### List

<img src="https://user-images.githubusercontent.com/10553294/78395761-c4a87380-75f6-11ea-87c5-6b34e1238f28.png" width="100%" alt="List Item"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 1 | Record Display | Displays how many items are currently displayed in the list out of the total # of list items. |
| 2 | List Item Sorting | Sorts the list item.  Functions like a Drop-Down Menu |
| 3 | List item | See below for additional information |
| 4 | Instruction Copy | Displays informative copy for #5 |
| 5 | Drop Down Menu | See Drop Down Menu |
| 6 | Pagination | See Pagination |
| 7 | Action Panel | See Action Panel |

### Multi-Select List

<img src="https://user-images.githubusercontent.com/10553294/78395823-e73a8c80-75f6-11ea-9fdd-897867ef414b.png" width="100%" alt="List Item"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 8 | Checkbox | Use to check and uncheck a list item |
| 9 | Multi-Select Action Panel | Use to apply action(s) to multiple selected items |

### List Item
<img src="https://user-images.githubusercontent.com/10553294/78395920-10f3b380-75f7-11ea-8422-4f31810643fb.png" width="100%" alt="List Item"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 1 | Listing Title | Displays the List Item Title. Should be brief and descriptive |
| 2 | Status of List Item (optional) | Shows the current status of the item if applicable |
| 3 | Description of List Item (optional) | Displays a description of the list item. There should be a character count limit for this text area |
| 4 | Attribute 1 (optional) | Displays the most important attribute of the list item.  The user may use this attribute to select the list item.  This may include tags, downloads, etc. |
| 5 | Attribute 2 (optional) | Displays the second important attribute of the list item.  This attribute helps the user to decide to act on this list item |
| 6 | Attribute 3 (optional) | Displays the third important attribute of the list item.  This attribute helps the user to decide to act on this list item |
| 7 | Action Panel | Displays the CTA that are applicable to the list items.  Examples are edit, delete, share, like |

<img src="https://user-images.githubusercontent.com/10553294/78395973-2e288200-75f7-11ea-930f-bdce332c56ff.png" width="100%" alt="List Item"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 10 | Listing Checkbox | Displays the List checkbox. Should be next to the List Item Title |

> In the following content will give an additional example with a checkbox for each section

### List Item with Icon

<img src="https://user-images.githubusercontent.com/10553294/78397402-d63f4a80-75f9-11ea-8b30-15b190ef3b11.png" width="100%" alt="List Item"/>

<img src="https://user-images.githubusercontent.com/10553294/78396194-9a0aea80-75f7-11ea-8b7d-7b731d69d98e.png" width="100%" alt="List Item"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 8 | Icon | Use a descriptive icon to identify the List Item. The icon must be unique and identifying the list item |

### List Item with Photo or Logo

<img src="https://user-images.githubusercontent.com/10553294/78396272-bd359a00-75f7-11ea-9834-23dbd1b4a708.png" width="100%" alt="List Item"/>

<img src="https://user-images.githubusercontent.com/10553294/78396328-dcccc280-75f7-11ea-9d60-5c01a372bbc6.png" width="100%" alt="List Item"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 9 | Photo | Use a photo with a 4: 3 ratios. The photo illustrates the listing. It may be a logo or identifying graphic |

### List Items Examples (and Modifications)

<img src="https://user-images.githubusercontent.com/10553294/78793100-9c37c500-79ba-11ea-994c-fc478d4ed459.png" width="100%" alt="List Item"/>

## Behavior

### Focus State

<img src="https://user-images.githubusercontent.com/10553294/78396387-f66e0a00-75f7-11ea-909e-4abc7cf9d85d.png" width="100%" alt="List Focus State"/>

> On focus, an item is outlined with a `3px` border. The border color is `#566FE6`

### Hover State

<img src="https://user-images.githubusercontent.com/10553294/78396479-23222180-75f8-11ea-914d-f32774b282fc.png" width="100%" alt="List Hover State"/>

> On hover state, the list item changes color (the final color is still TBD). For testing the bg color is `#E9EAEA`

### Active State

<img src="https://user-images.githubusercontent.com/10553294/78396511-3503c480-75f8-11ea-8c4e-7e221341fa35.png" width="100%" alt="List Active State"/>

> If an item is currently selected, the list item changes colors (the final colors are still TBD).  For testing the icons and text are `#FFFFFF` and the bg color is `#407CA0`

## Accessibility
> Ask development teams to add the correct HTML+CSS semantics for accessibility compliance

## Specifications

### List

<img src="https://user-images.githubusercontent.com/10553294/78396640-63819f80-75f8-11ea-8224-8d4500b75161.png" width="100%" alt="List"/>

### Multi-Select List

<img src="https://user-images.githubusercontent.com/10553294/78396710-80b66e00-75f8-11ea-890e-6678ec0d87db.png" width="100%" alt="Multi-Select List"/>

### List Item

<img src="https://user-images.githubusercontent.com/10553294/78396967-fcb0b600-75f8-11ea-8e95-f7a2cd4320a6.png" width="100%" alt="List Item"/>

| Element | Attribute | Value |
| ------- | --------- | ----- |
| List Item Title | Typeface <br>Font <br>Size <br>Case <br>Color | System Default <br>Bold <br>`1em` <br>Sentence case <br>`#000000` |
| List Item Status (Optional) | Typeface <br>Font <br>Size <br>Case <br>Color | System Default <br>Regular <br>`1em` <br>Sentence case <br>`#000000` |
| List Item Body (Optional) | Typeface <br>Font <br>Size <br>Case <br>Color | System Default <br>Regular <br>`0.875em` <br>Sentence case <br>#575757 |
| List Item Attribute(s) - Max 3 (Optional) | Typeface <br>Font <br>Size <br>Case <br>Color | System Default <br>Regular <br>`0.875em` <br>Sentence case <br>`#575757` |

### List Item with Icon

<img src="https://user-images.githubusercontent.com/10553294/78396967-fcb0b600-75f8-11ea-8e95-f7a2cd4320a6.png" width="100%" alt="List Item"/>

<img src="https://user-images.githubusercontent.com/10553294/78397123-5913d580-75f9-11ea-8e4f-87b3a0ec6bbb.png" width="100%" alt="List Item with Icon"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 8 | Icon | `3em` x `3em` |

### List Item with Photo or Logo

<img src="https://user-images.githubusercontent.com/10553294/78397165-72b51d00-75f9-11ea-9ba9-555bd6843796.png" width="100%" alt="List Item with Icon"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 9 | Photo | 4: 3 ratios |