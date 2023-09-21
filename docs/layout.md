## Usage

The layout principles provide guidance how the individual organisms (Atom Design Brad Frost) relate on a single application page.  The layouts have to be flexible enough to be customizable to each application while providing enough unifying structure to be branded. 

Templates are specific layouts used in Axway’s applications.

<img src="https://user-images.githubusercontent.com/10553294/80420514-8d6e6f00-88e3-11ea-9d65-c0523831eb92.jpg" width="100%" />

### The Four Different Layouts in the Grid 
 

* 1- Column layout 
* 2- Column layout 
* 3- Column layout 
* Mixed Column Layout that may contain any of the other layouts.  

The main difference is their behavior is based on the grid and their behavior based on different monitor widths. 

#### 1- Column Layout

<img src="https://user-images.githubusercontent.com/10553294/80420723-e5a57100-88e3-11ea-8c02-76d2b2b14544.png" width="100%" />

__Example:__
<img src="https://user-images.githubusercontent.com/10553294/80420746-f229c980-88e3-11ea-8a84-36b4737965e5.png" width="100%" />


| Number | Item |
| ------ | ---- |
| 1 | Content Area |

#### 2- Column Layout

<img src="https://user-images.githubusercontent.com/10553294/80420925-42a12700-88e4-11ea-8f10-057fbe2b126d.png" width="100%" />

__Example:__
<img src="https://user-images.githubusercontent.com/10553294/80420964-52b90680-88e4-11ea-9231-c2bd6cc92ac8.png" width="100%" />

| Number | Item |
| ------ | ---- |
| 1 | Content Area |


#### 3- Column Layout

<img src="https://user-images.githubusercontent.com/10553294/80421043-7c722d80-88e4-11ea-908d-233ecbc7bbb5.png" width="100%" />

__Example:__
<img src="https://user-images.githubusercontent.com/10553294/80421102-9b70bf80-88e4-11ea-8d64-c65be3911c0a.png" width="100%" />

| Number | Item |
| ------ | ---- |
| 1 | Content Area |

### Mixed Column Layout

<img src="https://user-images.githubusercontent.com/10553294/80421215-c9ee9a80-88e4-11ea-99b1-f2e19644a378.png" width="100%" />

__Example:__
<img src="https://user-images.githubusercontent.com/10553294/80421234-d1ae3f00-88e4-11ea-92fa-31b2f357dd6a.png" width="100%" />

| Number | Item |
| ------ | ---- |
| 1 | Content Area |

## The Anatomy

### The Grid 

The layouts impact ONLY the Fluid Responsive Grid Area (see grit) and not the navigation on the left.  The width of the left-hand menu impacts the overall width of the fluid responsive grit on a display and adapt based on grid breakpoints. 

__Example:__

| Screen Dimension @ `72dpi` | Left Navigation | Fluid Responsive Grid Area | Breakpoint |
| -------------------------- | --------------- | -------------------------- | ---------- |
| 1440 px | 250 px | 1190 px | 840+ |
| 1440 px | 50 px | 1390 px | 840+ |
| 1024 px | 250 px | 774 px | 720-839 |
| 1024 px | 50 px | 974 px | 840+ |
| 800 px | 250 px | 550 px | 600-719 |
| 800 px | 50 px | 750 px | 840+ |

#### Examples
##### 250px Navigation

<img src="https://user-images.githubusercontent.com/10553294/80421833-c6a7de80-88e5-11ea-81d8-3d2d78fb23e2.png" width="100%" />

##### 50px Navigation

<img src="https://user-images.githubusercontent.com/10553294/80421843-ca3b6580-88e5-11ea-8295-58decfe56666.png" width="100%" />

### Content Area

A content area defines a complete function or content block.   

__Example to be considered on content area:__  
1. Short paragraphs introducing the table and what the purpose of the table is, and the data table itself).  The three items are co-dependant and therefore considered a content area.
2. A list with multiple list items.
3. A text block with multiple paragraphs. The header works here as a separation between content areas.

__What is not a Content area:__
1. A header type (indicating the text), short paragraph, another header type and then a table.  That are 4 different content areas.  Header acts as a separation between different areas of a page.
2. A table and a list with different list items.  These are two content areas that should have each own header type to explain what the user is looking at.
3. A paragraph and a table that do not relate.  The paragraph may explain the usage of APIs and the table may display unrelated data.  If the information do not directly relate, they must be treated as two content areas.  Again, header types are needed to identify specific content areas.

## Specifications

### 1- Column Layout

<img src="https://user-images.githubusercontent.com/10553294/80422255-8ac14900-88e6-11ea-9047-8e61fd618d62.png" width="100%" />

| Fluid Responsive Grid Area | Column |
| -------------------------- | ------ |
| 840+ | 1 x 12 columns |
| 720-839 | 1 x 8 columns |
| 600-719 | 1 x 8 columns |


### 2- Column Layout

<img src="https://user-images.githubusercontent.com/10553294/80422274-901e9380-88e6-11ea-9300-a96098c815d1.png" width="100%" />

| Fluid Responsive Grid Area | Column |
| -------------------------- | ------ |
| 840+ | 2 x 6 columns |
| 720-839 | 2 x 4 columns |
| 600-719 | 2 x 4 columns |

### 3- Column Layout

<img src="https://user-images.githubusercontent.com/10553294/80422284-96147480-88e6-11ea-930a-7e2b956ad4dc.png" width="100%" />

| Fluid Responsive Grid Area | Column |
| -------------------------- | ------ |
| 840+ | 3 x 4 columns |
| 720-839 | 2 x 4 columns |
| 600-719 | 2 x 4 columns |

### Mixed Column Layout

<img src="https://user-images.githubusercontent.com/10553294/80422469-e12e8780-88e6-11ea-89e5-9a7153690ab0.png" width="100%" />

### The Content Area and Number of Columns

The columns in the grid are either 8 or 12 are depending on the screen dimension.  Please, reference the grid for breakpoints and dimensions for columns and gutter width. 

### The Margins of the Columns of the Grid

__Left Hand Navigation__

The grid (see grid) in the fluid responsive area has a margin-left of 1.5em that remains consistent at all the breakpoints regardless of the width of the left-hand navigation.

The right-hand margin depends on the screen dimensions. See grid for the margin guidelines

__No Left-Hand Navigation (for mobile down the road)__

The grid is centered with a margin on the left and right of 1.5em.

__The top margin to the Top Navigation Bar (Amplify Bar)__

The margin to the headline is 3.25em on all screen dimensions.

__The button margin to the footer (Amplify Bar)__

The margin to the footer is 6em on all screen dimensions.

### Margins Between Content Areas

The padding between content areas are `3em` except between header types and content areas. The top padding depends

<img src="https://user-images.githubusercontent.com/10553294/80422975-cc9ebf00-88e7-11ea-8e3a-2a63b4043f4d.png" width="100%" />


| Heading Type | Padding Bottom |
| ------------ | -------------- |
| H1 | 3em |
| H2 | 1.75em |
| H3 | 1.5em |
| H4 | 1.25em |

### Padding  

__Padding within the Responsive Grid Area__

There is no padding for the content within the responsive fluid grid area. The content area has no padding on the right, left, top and bottom. 

#### Between Related Content in One Content Area

<img src="https://user-images.githubusercontent.com/10553294/80422992-d32d3680-88e7-11ea-8041-3deb96c035d7.png" width="100%" />

The padding between content within one content area is `1.25em`. Example: the padding between two related paragraphs, or a paragraph and a table. The `1.25em` measures from the baseline to the top of the next content.
