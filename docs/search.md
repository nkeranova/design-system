> Search is an essential pattern for navigation or discovery. The search engine is often the primary entry point for the user. User expectations are high for the way search should work, and consistency is critical.

## Usage

Searching is an intuitive method of discovery, offering users a way to explore an application or product using keywords. Search can be used as the primary means of discovering content, or as a filter to aid the user in finding content. 

The method of search you use depends on the size of the data set being searched and the location of the search within your product. 

The placement of your search field depends on the construction of your application and the scope of the search. 

### Best practices

* __Avoid dead ends__ - If a search returns “No results,” suggest a follow-up action. Provide suggestions and helpful resources to aid the user in finding what they are looking for. 
* __Include a loading indicator__ - If the search will take longer than a moment or two, include a loading indicator. 
* __Display the number of results__ - Always include the number of search results, including for searches with no results. 
* __Don’t include a label__ - Avoid adding a label to your search field. Users expect and understand search fields, and no label is necessary. A search icon along with useful placeholder text should clearly indicate that the field is intended for search. 

## Types

The search method and the placement of the bar are different depending on the search variation.  

### Global Search

Global Search is one of the most used features, and users expect it to be fast, intelligent, and simple. With a global search, users can get right to the records and apps by entering simple keywords or using powerful advanced search features. 

Typically, Global search lives in the header of the app, where it’s highly discoverable and always available for the potential users. 

### In-Context Search

With an in-context search, users can refine the content on a page to find the correct information without having to context-shift and navigate away when using a global search. Core examples of in-context search are in list views and feeds. 

Place the in-context search directly above the content the user is refining. 

## Search

> The simple search is just a Search bar with a Basic search algorithm.

### Anatomy

<img src="https://user-images.githubusercontent.com/10553294/84187414-aea5ac00-aa9a-11ea-8f33-07821bb7cf10.png" width="100%" alt="Search" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Search Text Field | Text entry field: The place where a user enters their search query. Displayed by a stroke around a placeholder/input search text. |
| 2 | Search Icon | Signifies a search field. The magnifying glass icon is a universal way to indicate search. Reference - Iconography. |
| 3 | Placeholder/Search entry | Placeholder text: Useful and short text hinting at what the user can search for. |

### Behavior

Search enables users to specify a word or a phrase to find relevant pieces of content without the use of navigation. Typically, used a basic search algorithm and immediately filter the page content.

#### Focus state

<img src="https://user-images.githubusercontent.com/10553294/84187443-ba916e00-aa9a-11ea-92a2-32b89c0ca541.png" width="100%" alt="Search" />

> On focus state the container border is `3px` and the color changes to `#566FE6`

!> Search Bar do NOT have __Hover__ or __Disabled__ state. Could be added in the future if needed. 

### Specification

<img src="https://user-images.githubusercontent.com/10553294/84187454-be24f500-aa9a-11ea-8050-9a4987244c5b.png" width="100%" alt="Search" />

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Search Bar/Textfield | <ul><li>Border Color</li><li>Height</li><li>Width</li></ul> | <ul><li>`#929292`</li><li>`2.25em`</li><li>`28em` (or no more then to have a `27-characters` text input) </li></ul> |
| Search Icon | <ul><li>Icon Size (W/H)</li><li>Color</li><li>BG color</li><li>Icon Area Size (_W/H_)</li></ul> | <ul><li>`1em x 1em` (_1.25em x 1.25em_)</li><li>`#03819F`</li><li>Transparent</li><li>`2.25em x 2.25em`</li></ul> |
| Placeholder | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>`#767676`</li><li>`Sentence-case`</li></ul> |
 
> A rule of thumb is to have a [27-characters text input](https://www.nngroup.com/articles/top-ten-guidelines-for-homepage-usability/) (it would accommodate 90% of queries).
 
## Search with Dropdown

> The complex search is a Search bar with Dropdown based on search algorithm (basic & advanced).

### Anatomy

<img src="https://user-images.githubusercontent.com/10553294/84187473-c715c680-aa9a-11ea-9295-53b80a60375c.png" width="100%" alt="Search" />

| # | Element | Description |
| - | ------- | ----------- |
| 1 | Search Bar | Contains Search text field, search icon & placeholder. Reference Search Anatomy. |
| 2 | Recent Search Label | Recent searches text label. |
| 3 | Recent Searches List | List of possible search values (recent searches list). |
| 4 | Recent Searches Dropdown | The Searches Dropdown container displayed by stroke border. |

### Behavior

> Search enables users to specify a word or a phrase to find relevant pieces of content without the use of navigation.

#### Focus state

<img src="https://user-images.githubusercontent.com/10553294/84187498-ce3cd480-aa9a-11ea-993a-44227652a7ff.png" width="100%" alt="Search" />

> On focus state the container border is `3px` and the color changes to `#566FE6`

#### Hover state

<img src="https://user-images.githubusercontent.com/10553294/84187509-d1d05b80-aa9a-11ea-87c0-341f09790eec.png" width="100%" alt="Search" />

> On hover the Search list item background color is `60%` by `#C8C9C7`

#### Disabled state

<img src="https://user-images.githubusercontent.com/10553294/84187521-d563e280-aa9a-11ea-8b47-5c0b5bc2f5dd.png" width="100%" alt="Search" />

> Once the Selection is disabled the color is #C8C9C7 

### Specification

<img src="https://user-images.githubusercontent.com/10553294/84187593-f0ceed80-aa9a-11ea-9ded-94dd61e7b6a8.png" width="100%" alt="Search" />

| Element | Attribute | Value |
| ------- | --------- | ----- |
| Recent Search Label | <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>`#767676`</li><li>`Sentence-case`</li><li>`1em`</li></ul> |
| Search List Item |  <ul><li>Typeface</li><li>Font</li><li>Size</li><li>Color</li><li>Case</li><li>Padding</li></ul> | <ul><li>System Default</li><li>Regular</li><li>`0.75em`</li><li>`#767676`</li><li>`Sentence-case`</li><li>`1em`</li></ul> |

## Search Algorithms 

A search algorithm is any algorithm which solves the search problem, namely, to retrieve information stored within some data structure, or calculated in the search space of a problem domain, either with discrete or continuous values. 

Depending on the used Search Algorithm the Search Bars could be Basic or Advanced. 

### Basic Search 

Basic search entails any search that directs users to a distinct results page. In these instances, offer either trending searches that match the active user’s keywords, recent searches by the active user, or both. 

A basic search does not actually query a data set until the user runs the search. 

* __Recent search suggestions__ - user’s recent searches, a trending searches, or both 
* __Type-ahead suggestions__ - type-ahead suggestions are generated from ongoing analyses of use search patterns, and place minimal load on servers. 

#### Basic Search Example

<img src="https://user-images.githubusercontent.com/10553294/84187568-e4e32b80-aa9a-11ea-80ef-0f5ac5f300ca.png" width="100%" alt="Search" />

### Advanced Search

An advanced or active search is a rapid way to search an application or data set. The search runs after each character is entered, and results are shown immediately below the search field. You can think of an active search to filter a dataset through keywords.

#### Active Search Example

<img src="https://user-images.githubusercontent.com/10553294/84187578-e9a7df80-aa9a-11ea-918b-5410824aa51b.png" width="100%" alt="Search" />
