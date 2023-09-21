## Usage

The Action Panels are one or multiple CTAs that can impact one or multiple items in a list, card view or data table. Action Panels use icons (see icons) to trigger an action such as edit, delete, and settings. The Action Panels do not use any labels to explain the actions.   
 
* Icons
* Border to icons
* Hover, Active, Focus and Disabled States

## Types

### Action Panel

The Action Panel for desktop applies an action to one item. The item can be a list item, a row in a data table or one singular card.  The action panel is displayed inline of the list item (see list item), in the row (see data table) or a card (see cards).

The main component for the Action Panel
* Icon as CTA without border. The icons for the Action Panel are in the icon section.
* Dropdown with Icons

### Multi-Select Action Panel
The Multi-Select Panel applies an action to 1 or more selected items in a list, rows in a data table or multiple cards. The Multi-Select Panel is located on the right top area of the list, data or card display.

The main component for the Action Panel
* Icon as CTA with a rounded corner border. The icons for the Action Panel are in the icon section.
* Dropdown with Icons as CTA with rounded corners border.

## Action Panels

### Anatomy
The max number of icons per row is 3 CTA’s including the expanded row panel button.  In case there is a need for more than 3 CTA’s, use the meatball menu button for triggering a drop-down menu.

__3 CTAs__
<img src="https://user-images.githubusercontent.com/10553294/78380277-450dab00-75dc-11ea-9264-4ddbf03bb33c.png" width="100%" alt="3 CTAs"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 1–3 | Icons | CTA triggering different actions to a specific item. |

__3 and more__
<img src="https://user-images.githubusercontent.com/10553294/78380461-9158eb00-75dc-11ea-8b0f-e753a04500dc.png" width="100%" alt="3 CTAs"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 1–3 | Icons | CTA triggering different actions to a specific item. |
| 4 | Selected meat ball menu | On click/tap (selection) triggers a dropdown menu with additional available CTAs (icons). <br>On click/tap outside the dropdown, retract the dropdown. <br>Keyboard: Select again the meatball menu to collapse the dropdown. Discuss this more with engineering. |
| 5-6 | Icons | CTA triggering different actions to a specific item. |

#### Action Panel for Tables with Expandable Rows

The Action Panel for Tables with Expandable rows differs from the action panel that there are just 2 CTAs and 1 CTA that expands the selected row in an accordion format. The expansion icon is always located at the end of the action panel.

__2 CTAs + Expanding Row__
<img src="https://user-images.githubusercontent.com/10553294/78381013-68852580-75dd-11ea-809c-155c0ccd175a.png" width="100%" alt="3 CTAs"/>

__3 and more CTAs + Expanding Row__
<img src="https://user-images.githubusercontent.com/10553294/78381110-8e122f00-75dd-11ea-9b46-9bef50c7eb58.png" width="100%" alt="3 CTAs"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 1–2 | Icons | CTA triggering different actions to a specific item. |
| 3 | Selected meat ball menu | On click/tap (selection) triggers a dropdown menu with additional available CTAs (icons). <br>On click/tap outside the dropdown, retract the dropdown. <br>Keyboard: Select again the meatball menu to collapse the dropdown. Discuss this more with engineering. |
| 4 | Expanding Row Icon | Used only in expanding rows in a data table. |
| 5-6 | Icons | CTA triggering different actions to a specific item. |

### Behavior

#### Focus State
<img src="https://user-images.githubusercontent.com/10553294/78381460-0f69c180-75de-11ea-8e58-866ec8d943a7.png" width="100%" alt="Focus State"/>

> On focus, an item is outlined with a `3px` border. The border color is `#566FE6`

#### Hover State
<img src="https://user-images.githubusercontent.com/10553294/78381593-4344e700-75de-11ea-9307-cc50348d932d.png" width="100%" alt="Hover State"/>

> On hover state, the list item changes color (the final color is still TBD). For testing the bg color is `#E9EAEA`

#### Active State
<img src="https://user-images.githubusercontent.com/10553294/78381848-9f0f7000-75de-11ea-9a6c-cd7319f1ecee.png" width="100%" alt="Active State"/>

> If a CTA is selected, the CTA changes colors (the final colors are still TBD). For testing the icons are `#FFFFFF` and the bg color is `#407CA0`

#### Disabled State
<img src="https://user-images.githubusercontent.com/10553294/78382011-d2ea9580-75de-11ea-858f-40dc354193b6.png" width="100%" alt="Disabled State"/>

> A disabled CTA (Icon) color is `#E2E2E2`

### Specification

#### Action Panel

<img src="https://user-images.githubusercontent.com/10553294/78382211-21982f80-75df-11ea-81d4-2d8593a9a185.png" width="100%" alt="Action Panel"/>

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Icon | Width <br>Height <br>Color <br>BG color | `1.25em` <br>`1.25em` <br>`#337AB7` <br>Transparent |
| Icon Focus, Hover | Color <br>BG color | `#337AB7` <br>Transparent |
| Icon Active | Color <br>BG color | `#FFFFFF` <br>`#407CA0` |
| Icon Disabled | Color <br>BG color | `#E2E2E2` <br>`#FFFFFF` |
| Icon Touch Area | Width <br>Height <br>Color | `3em` <br>`3em` <br>Transparent |
| Drop Down Panel | Width <br>Height <br>Borderline Color <br>BG color | `3em` <br># of CTA x 3 em <br>`#929292` <br>`#FFFFFF` |

#### Action Panel for Tables with Expandable Rows

<img src="https://user-images.githubusercontent.com/10553294/78382931-3de89c00-75e0-11ea-87b4-2e60d53078d9.png" width="100%" alt="Action Panel"/>

## Multi–Selected Action Panel

### Anatomy
The max number of icons per row is 3 CTA’s including the expanded row panel button.  In case there is a need for more than 3 CTA’s, use the meatball menu button for triggering a drop-down menu.

__3 CTAs__
<img src="https://user-images.githubusercontent.com/10553294/78383256-c23b1f00-75e0-11ea-9596-2220abeb2d7a.png" width="100%" alt="3 CTAs"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 1–3 | Icons | CTA triggering different actions to a specific item. |

__3 and more__
<img src="https://user-images.githubusercontent.com/10553294/78392315-b9524980-75f0-11ea-9994-58ce987364a6.png" width="100%" alt="3 CTAs"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 1–3 | Icons | CTA triggering different actions to a specific item. |
| 4 | Selected meat ball menu | On click/tap (selection) triggers a dropdown menu with additional available CTAs (icons). <br>On click/tap outside the dropdown, retract the dropdown. <br>Keyboard: Select again the meatball menu to collapse the dropdown. Discuss this more with engineering. |
| 5-6 | Icons | CTA triggering different actions to a specific item. |

### Behavior

#### Focus State

<img src="https://user-images.githubusercontent.com/10553294/78392360-d129cd80-75f0-11ea-8927-0d0ee2654970.png" width="100%" alt="Focus State"/>

> On focus, an item is outlined with a `3px` border. The border color is `#566FE6`

#### Hover State

<img src="https://user-images.githubusercontent.com/10553294/78392449-edc60580-75f0-11ea-816b-9e0ef29f4cb3.png" width="100%" alt="Hover State"/>

> On hover state, the list item changes color (the final color is still TBD). For testing the bg color is `#E9EAEA`

#### Active State

<img src="https://user-images.githubusercontent.com/10553294/78392511-033b2f80-75f1-11ea-8aa8-66107f7d2078.png" width="100%" alt="Active State"/>

> If a CTA is selected, the CTA changes colors (the final colors are still TBD). For testing the icons are `#FFFFFF` and the bg color is `#407CA0`

#### Disabled State

<img src="https://user-images.githubusercontent.com/10553294/78392596-2960cf80-75f1-11ea-8415-1753f6082c05.png" width="100%" alt="Disabled State"/>

> A disabled CTA (Icon) and border color is `#E2E2E2`

### Specification

<img src="https://user-images.githubusercontent.com/10553294/78392687-53b28d00-75f1-11ea-910b-11832988660b.png" width="100%" alt="Action Panel"/>

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Icon | Width <br>Height <br>Color <br>BG color | `1.25em` <br>`1.25em` <br>`#337AB7` <br>`#FFFFFF` |
| Icon Focus, Hover | Color <br>BG color | `#337AB7` <br>Transparent |
| Icon Active | Color <br>BG color <br>Border Color | `#FFFFFF` <br>`#407CA0` <br>`#407CA0` |
| Icon Disabled | Color <br>BG color <br>Border Color | `#E2E2E2` <br>`#FFFFFF` <br>`#E2E2E2` |
| Icon Touch Area | Width <br>Height <br>BG color <br>Border Color <br>Border Rounded Corner | `3em` <br>`3em` <br>`#FFFFFF` <br>`#337AB7` <br>`10px` |
| Drop Down Panel | Width <br>Height <br>Borderline Color <br>BG color | `3em` <br># of CTA x 3 em <br>`#929292` <br>`#FFFFFF` |

## Responsive Grid

### Anatomy
The number of CTAs on mobile (tablet and phone) are not limited.  The reason is that drop down in the Action Panels would complicate the mobile interaction unnecessarily. 
 
__Example: Mobile Action Panel__
<img src="https://user-images.githubusercontent.com/10553294/78392811-8d839380-75f1-11ea-8b0c-484165eaf4f5.png" width="100%" alt="Active State"/>

__Example: Mobile Mutli-Select Action Panel__
<img src="https://user-images.githubusercontent.com/10553294/78392892-a8560800-75f1-11ea-8582-a883a08c925f.png" width="100%" alt="Active State"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 1-4 | Icons | CTA triggering different actions to a specific item. |