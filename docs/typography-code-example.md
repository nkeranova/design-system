> Most of the samples are from [`axway-react-ui`](https://git.ecd.axway.org/amplify/axway-react-ui) - a library for reusable React components within Axway. It is not tied to any particular product (e.g. Builder, Central) and is treated as standalone. Being the case, Axway React UI has its own JIRA project which should be used to track all changes.
> Storybook Demo  - [Storybook](https://amplify.git-pages.ecd.axway.org/axway-react-ui/master/index.html)
> Run `npm start` to test this out locally.
> To use the given React samples below, you should install the library via `npm install --save-dev axway-react-ui`

## Headings

<img width="307" alt="typography-headlings" src="https://user-images.githubusercontent.com/10553294/77541368-41c44200-6ead-11ea-9e05-83fcb0724b6c.png">

<!-- tabs:start -->
#### __HTML__
<!-- panels:start -->
<!--div:html-->
```html
<div id="content">
	<h1>h1. heading</h1>
	<h2>h2. heading</h2>
	<h3>h3. heading</h3>
	<h4>h4. heading</h4>
	<h5>h5. heading</h5>
	<h6>h5. heading</h6>
</div>;
```

<!-- panels:end -->
#### __React__
<!-- panels:start -->
<!--div:react-->
```react
/* React example */

```
<!-- panels:end -->
<!-- tabs:end -->

## Links

<img width="274" alt="typography-links" src="https://user-images.githubusercontent.com/10553294/77541413-5274b800-6ead-11ea-9679-f9a8b7e3450a.png">

<!-- tabs:start -->
#### __HTML__
<!-- panels:start -->
<!--div:html-->
```html
<div id="content">
	<button className="text">button.text</button><br />
	<button className="text" disabled>button.text (disabled)</button><br />

	<br />

	<a href={`/foo/${new Date().getTime()}`}>a. (unvisited)</a><br />
	<a href="/#" className="visited">a. (visited)</a><br />
	<a href="/#" role="button">a. (role=&quot;button&quot;)</a><br />

	<br />

	<a href={`/foo/${new Date().getTime()}`} className="hyperlink">a.hyperlink</a><br />
	<a href="/#" className="hyperlink">a.hyperlink (visited)</a><br />
</div>;
```

<!-- panels:end -->
#### __React__
<!-- panels:start -->
<!--div:react-->
```react
/* React example */

```
<!-- panels:end -->
<!-- tabs:end -->

## Preformatted


<pre style="background: lightgrey">
	text that
	spans two lines.
</pre>

<!-- tabs:start -->
#### __HTML__
<!-- panels:start -->
<!--div:html-->
```html
<pre>
	text that
	<br />
	spans two lines.
</pre>;
```

<!-- panels:end -->
#### __React__
<!-- panels:start -->
<!--div:react-->
```react
/* React example */

```
<!-- panels:end -->
<!-- tabs:end -->

## Text Styles

normal text

span.text-body

**Bold**

_Italic_

<span style="text-decoration:underline">Underline<span><br />

<label htmlFor="label">label</label>

<span style="color:lightblue">span.ux-primary</span>

<!-- tabs:start -->
#### __HTML__
<!-- panels:start -->
<!--div:html-->
```html
<div id="content">
	<span>normal text</span><br />
	<br />
	<span className="text-body">span.text-body</span><br />
	<br />
	<span style={{ fontWeight: 'bold' }}>Bold</span><br />
	<br />
	<span style={{ fontStyle: 'italic' }}>Italic</span><br />
	<br />
	<span style={{ textDecoration: 'underline' }}>Underline</span><br />
	<br />
	<label htmlFor="label">label</label><br />
	<br />
	<span className="ux-primary">span.ux-primary</span><br />
</div>;
```

<!-- panels:end -->
#### __React__
<!-- panels:start -->
<!--div:react-->
```react
/* React example */

```
<!-- panels:end -->
<!-- tabs:end -->

## Titles

__*.text-header__

*.subtitle

<!-- tabs:start -->
#### __HTML__
<!-- panels:start -->
<!--div:html-->
```html
<div>
	<span className="text-header">*.text-header</span><br />
	<span className="subtitle">*.subtitle</span>
</div>;
```

<!-- panels:end -->
#### __React__
<!-- panels:start -->
<!--div:react-->
```react
/* React example */

```
<!-- panels:end -->
<!-- tabs:end -->

## Type Sizes

<img width="264" alt="type-sizes" src="https://user-images.githubusercontent.com/10553294/77541793-da5ac200-6ead-11ea-9288-baf29a9762d3.png">

<!-- tabs:start -->
#### __HTML__
<!-- panels:start -->
<!--div:html-->
```html
<div id="content">
	<span className="ux-type-size-one">*.ux-type-size-one</span><br />
	<span className="ux-type-size-two">*.ux-type-size-two</span><br />
	<span className="ux-type-size-three">*.ux-type-size-three</span><br />
	<span className="ux-type-size-four">*.ux-type-size-four</span><br />
	<span className="ux-type-size-five">*.ux-type-size-five</span><br />
</div>;
```

<!-- panels:end -->
#### __React__
<!-- panels:start -->
<!--div:react-->
```react
/* React example */

```
<!-- panels:end -->
<!-- tabs:end -->

## Type Styles

<img width="1169" alt="tipe-style" src="https://user-images.githubusercontent.com/10553294/77541829-e9417480-6ead-11ea-8e92-19f47a325af6.png">

<!-- tabs:start -->
#### __HTML__
<!-- panels:start -->
<!--div:html-->
```html
<div id="content">
	<h3>.ux-container</h3>
	<div>
		<p className="ux-container">
			The <code>ux-container</code> is a main UI container that has a bottom border
			and is aware of other containers, applying vertical separation between them.
			The last container does not have a border.
		</p>
		<p className="ux-container">
			<em>This container will have a vertical margin and no bottom border.</em>
		</p>
	</div>
</div>;
```

<!-- panels:end -->
#### __React__
<!-- panels:start -->
<!--div:react-->
```react
/* React example */

```
<!-- panels:end -->
<!-- tabs:end -->