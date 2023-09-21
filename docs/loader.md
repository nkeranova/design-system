> Loading spinners are used when retrieving data or performing slow computations and help to notify users that loading is underway.

## Usage

Loaders express an unspecified wait time or display the length of a process. They notify to the user that their request is being processed. It is best practice to use a loading spinner whenever the wait time is anticipated to be longer than three seconds. 

### Principles 

* __Informative__ – spinners look and animate in ways that reflect the status of a process.
* __Animated__ – loaders are animated to capture user attention and inform them an activity’s progress.
* __Consistent__ - loaders should be applied to all instances of a process in a consistent format (__linear__ or __circular__).

### Types

* __Determinate__ – loader display how long a process will take.

* __Indeterminate__ - loader express an unspecified amount of wait time.

## Anatomy

<img src="https://user-images.githubusercontent.com/10553294/82355312-b4afec00-9a0a-11ea-8244-6d1841fb8e0b.png" width="100%" alt="Loader"/>

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Track | The loader circular track is fixed rule, with set boundaries for the indicator to travel along. Generally, is visible and is made from two circles with different radius. |
| 2 | Indicator | The loader circular indicator animates along the length of the track. Simply is partial circular track separate by a different color. |

## Behavior 

> Circular progress indicators display progress by animating an indicator along a visible circular track in a clockwise direction. They can be applied directly to a surface, such as actual component I.e. button, card, etc.

__Indeterminate circular indicators__ grow and shrink in size while moving along the track. 

<img src="https://user-images.githubusercontent.com/10553294/82357102-4fa9c580-9a0d-11ea-81aa-32cfcec671cc.png" width="100%" alt="Loader"/>

> Displays circular track in a clockwise direction

### Gif animation

<img src="https://user-images.githubusercontent.com/10553294/82758224-e26fa900-9ded-11ea-8ffe-eb856fae991b.gif" width="100%" alt="Loader"/>

> Gif animation of the spinning movement

### Placement

Circular progress indicators are positioned to indicate the process that they represent. 

When centered on the screen, they indicate the initial loading of screen content. 

When placed above or below existing content, they draw attention to where new content will appear. 

### Loader Sizes

> Loading spinners may be scaled down if the loading experience is contextual to a certain item on the page

<img src="https://user-images.githubusercontent.com/10553294/82357118-56d0d380-9a0d-11ea-8c1c-961a79a11d80.png" width="100%" alt="Loader"/>

| Element | Description |
| ------- | ----------- |
| Small | The small loaders, normally are used along small elements like Toggles |
| Medium | The medium loaders are the mostly used ones, that’s why are taken as default. They are used along elements as Icons or Buttons |
| Large | The large loaders are used along bigger UI elements as Modals or Panels |
| X-Large | The X-Large loaders are typically used on the entire Layout |

## Specification

<img src="https://user-images.githubusercontent.com/10553294/82357136-5afcf100-9a0d-11ea-854b-f38df73692fc.png" width="100%" alt="Loader"/>

> The circular loader track is a circle inside a square with a specific size of the side in em.
> The circular indicator is a partial track and animates along the length of it.

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Circular loader track | <ul><li>Size</li><li>Color</li></ul> | <ul><li>Depends on the Loader size</li><li>Axway Dark Teal - `#03819F`</li></ul> |
| Circular loader indicator | <ul><li>Size</li><li>Color</li></ul> | <ul><li>Depends on the Loader size</li><li>20% of Axway Dark Teal - `#03819F`</li></ul> |

### Loader Sizes Specs

<img src="https://user-images.githubusercontent.com/10553294/82357154-5fc1a500-9a0d-11ea-9f3f-5e2488d3ca3f.png" width="100%" alt="Loader"/>

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Small | <ul><li>Track Size</li><li>Indicator width</li></ul> | <ul><li>`1em` x `1em`</li><li>`0.125em`</li></ul> |
| Medium | <ul><li>Track Size</li><li>Indicator width</li></ul> | <ul><li>`3em` x `3em`</li><li>`0.25em`</li></ul> |
| Large | <ul><li>Track Size</li><li>Indicator width</li></ul> | <ul><li>`4.5em` x `4.5em`</li><li>`0.375em`</li></ul> |
| X-Large | <ul><li>Track Size</li><li>Indicator width</li></ul> | <ul><li>`7.5em` x `7.5em`</li><li>`0.75em`</li></ul> |

> The default loader is the Medium Size
