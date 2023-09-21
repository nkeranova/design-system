> Badges are labels which hold small amounts of information. A badge contains a numeric value, to indicate a running tally or quantity-based summary. Typically, represents dynamic information such as several pending requests. 

## Usage

Badges contain numeric values and indicate a running tally, such as the number of unread messages in a room. Use badges to label page items with a small amount of information that draws attention to new, updated or removed content. Badges are normally placed before or after the label of the thing they're quantifying and contain only numbers or a "`+`" sign to indicate a quantity greater than the displayed number. 

Badges are usually placed on the right upper corner of the according element.

### Best practices

__Badges should:__ 

* Be built by circle background on specific color & number indicator (__ex__: _in case of 3 Errors_) 
* Be placed on the top-right position of the element (__ex__: _Navigation_) 
* Be used in conjunction with a single line item or label, to avoid ambiguity around which item is being quantified. 

### Usage examples

* Badge is used to display a quantity status on global navigation 
* The badge, used to indicate the number of unread notifications 
* Badges used to convey the number of added and removed lines of code 

& more. 

## Anatomy

> A Badge is basically a small numerical value or status descriptor for UI elements.

<img src="https://user-images.githubusercontent.com/10553294/84304533-52598f80-ab61-11ea-95e1-3d428dce752b.png" width="100%" alt="Badge" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Badge container | Filled container by solid color around a numeric indicator. |
| 2 | Numeric indicator | Numeric indicator displays a specific count, typically, represents dynamic information such as several pending requests. |

## Behavior

The Badge have different state depends on the purpose i.e. indicate information with a specific state: `neutral`, `success`, `warning` and `danger`.

<img src="https://user-images.githubusercontent.com/10553294/84304544-55548000-ab61-11ea-9786-db5aac1e7963.png" width="100%" alt="Badge" />


| State | Purpose | Attribute | Value |
| ----- | ------- | --------- | ----- |
| Neutral | Is the neutral I.e. default badge | <ul><li>Color</li><li>BG Color</li></ul> | <ul><li>`#FFFFFF`</li><li>`#C8C9C7`</li></ul> |
| Success | Represent all successful cases | <ul><li>Color</li><li>BG Color</li></ul> | <ul><li>`#FFFFFF`</li><li>`#49B089`</li></ul> |
| Warning | Represent occurrence of Warnings | <ul><li>Color</li><li>BG Color</li></ul> | <ul><li>`#000000`</li><li>`#FF9E18`</li></ul> |
| Danger | Represent occurrence of Errors | <ul><li>Color</li><li>BG Color</li></ul> | <ul><li>`#FFFFFF`</li><li>`#D22630`</li></ul> |

## Specification

<img src="https://user-images.githubusercontent.com/10553294/84304548-57b6da00-ab61-11ea-97c6-45edadd294e4.png" width="100%" alt="Badge" />

### Badges by Numeric Indicator

> The allowed Numeric indicator displayed range is `[0-99]`, additionally add a sign i.e. `99+`

1. __Single Digit__ - single digit in the range `[0-9]` and size `0.75em`
2. __Two Digits__ - single digit in the range `[0-99]` and size `0.75em`
3. __Additional Sign__ - single digit in the range `[0-9]`, size `0.75em` and optional sign `+`/`-`

| Type | Attribute | Value |
| ---- | --------- | ----- |
| Badge | <ul><li>Size</li><li>Height</li><li>Radius</li><li>Left/Right Padding</li></ul> | <ul><li>`0.75em`</li><li>`1.5em`</li><li>`12em`</li><li>`8em`</li></ul> |

> The colors depend on the Behavior & Badge state, please check the previous section. 