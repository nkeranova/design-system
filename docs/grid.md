## Anatomy

<img src="https://user-images.githubusercontent.com/10553294/78037852-bf3bf680-7374-11ea-8a38-f474dd25684c.png" width="100%" alt="Anatomy"/>

| # | Component Name | Guidelines |
| - | -------------- | ---------- |
| 1 | Fixed UI Region (Menu) | Fixed width component that does not rescale with the screen size. TBD: if this region collapses below 600 width. |
| 2 | Fluid Responsive Grit Area | Fluid grids use columns that scale and resize content. A fluid grid’s layout can use breakpoints to determine if the layout needs to change dramatically. |
| 3 | Margin-Left | Margins are the space between content and the left and right edges of the screen. <br>Margin widths are defined as fixed values at each breakpoint range. To better adapt to the screen, the margin width can change at different breakpoints. Wider margins are more appropriate for larger screens, as they create more whitespace around the perimeter of content. |
| 4 | Margin- Right | See Margin-Left |
| 5 | Column | Content is placed in the areas of the screen that contain columns. <br>Column width is defined using percentages, rather than fixed values, to allow content to flexibly adapt to any screen size. The number of columns displayed in the grid is determined by the breakpoint range (a range of predetermined screen sizes) at which a screen is viewed, whether it’s a breakpoint for mobile, tablet, or another size. |
| 6 | Gutter | Gutters are the spaces between columns. They help separate content. <br>Gutter widths are fixed values at each breakpoint range. To better adapt to the screen, gutter width can change at different breakpoints. Wider gutters are more appropriate for larger screens, as they create more whitespace between columns. |

## Breakpoints

The Axway DS provides responsive layouts based on the following column structures. Layouts using 4-column, 8-column, and 12-column grids are available for use across different screens, devices, and orientations. 

Each breakpoint range determines the number of columns, and recommended margins and gutters, for each display size. 

### 840+
> Examples

**Screen Example 1440 width**

<img src="https://user-images.githubusercontent.com/10553294/78038595-ad0e8800-7375-11ea-9bb4-59a6b065b297.png" width="100%" alt="Screen Example 1440 width"/>

**Screen Example 1024 width**

<img src="https://user-images.githubusercontent.com/10553294/78038942-21e1c200-7376-11ea-8cfe-f691b238a77f.png" width="100%" alt="Screen Example 1024 width"/>

| Screen Size | Margin-Left | Margin-Right | Gutter | Columns |
| ----------- | ----------- | ------------ | ------ | ------- |
| 840+ | `1.5em` | `3em` | `1.5em` | 12 |

### 720 – 839

**Screen Example 839 width**

<img src="https://user-images.githubusercontent.com/10553294/78039276-97e62900-7376-11ea-84ac-70cb25a8fb20.png" width="100%" alt="Screen Example 839 width"/>

| Screen Size | Margin-Left | Margin-Right | Gutter | Columns |
| ----------- | ----------- | ------------ | ------ | ------- |
| 720-839 | `1.5em` | `1.5em` | `1.5em` | 8 |

### 600 – 719

**Screen Example 719 width**

<img src="https://user-images.githubusercontent.com/10553294/78039600-fad7c000-7376-11ea-8f3d-ba117357c327.png" width="100%" alt="Screen Example 719 widt"/>

| Screen Size | Margin-Left | Margin-Right | Gutter | Columns |
| ----------- | ----------- | ------------ | ------ | ------- |
| 600-719 | `1.5em` | `1.5em` | `1em` | 8 |

## References 

[http://www.responsivegridsystem.com/](http://www.responsivegridsystem.com/)