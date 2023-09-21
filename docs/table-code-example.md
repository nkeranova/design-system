> Most of the samples are from [`axway-react-ui`](https://git.ecd.axway.org/amplify/axway-react-ui) - a library for reusable React components within Axway. It is not tied to any particular product (e.g. Builder, Central) and is treated as standalone. Being the case, Axway React UI has its own JIRA project which should be used to track all changes.
> Storybook Demo  - [Storybook](https://amplify.git-pages.ecd.axway.org/axway-react-ui/master/index.html)
> Run `npm start` to test this out locally.
> To use the given React samples below, you should install the library via `npm install --save-dev axway-react-ui`

## Actions

<img width="1193" alt="table-action" src="https://user-images.githubusercontent.com/10553294/77439954-5ee70b00-6df0-11ea-8a3f-e6f723e14edd.png">

<!-- tabs:start -->

#### __React__
<!-- panels:start -->
<!--div:react-->
```react
/* Actions Table React example */
<DataTable
	rowActions={[
		{ name: 'Action-1', action: () => {} },
		{ name: 'Action-2', action: () => {} }
	]}
	columns={[
		{
			key: 'one',
			name: 'Header-1',
			className: 'selected',
			format: item => {
				return (<a>{item.one}</a>);
			}
		},
		{
			key: 'two',
			name: 'Header-2'
		},
		{
			key: 'three',
			name: 'Header-3'
		},
		{
			key: 'rowActions',
			className: 'row-actions'
		}
	]}
	items={[
		{ one: 'Item one', two: 'value-2', three: 'value-3' },
		{ one: 'Item four', two: 'value-5', three: 'value-6' }
	]}
/>;
```
<!-- panels:end -->

#### __HTML__
<!-- panels:start -->
<!--div:html-->
```html
TDB
```
<!-- panels:end -->
<!-- tabs:end -->

## Clickable

<img width="1195" alt="table-clickable" src="https://user-images.githubusercontent.com/10553294/77441864-9a82d480-6df2-11ea-8354-78e92d307c8e.png">

<!-- tabs:start -->

#### __React__
<!-- panels:start -->
<!--div:react-->
```react
/* Clickable Table React example */
<DataTable
	clickable
	rowClick={(e, data) => { alert(data.one); }}
	columns={[
		{
			key: 'one',
			name: 'Header-1',
			className: 'selected',
			format: item => {
				return (<a>{item.one}</a>);
			}
		},
		{
			key: 'two',
			name: 'Header-2'
		},
		{
			key: 'three',
			name: 'Header-3'
		},
		{
			key: 'rowActions',
			className: 'row-actions'
		}
	]}
	items={[
		{ one: 'Item one', two: 'value-2', three: 'value-3' },
		{ one: 'Item four', two: 'value-5', three: 'value-6' }
	]}
/>;
```
<!-- panels:end -->

#### __HTML__
<!-- panels:start -->
<!--div:html-->
```html
TDB
```
<!-- panels:end -->
<!-- tabs:end -->

## Default

<img width="1189" alt="table-default" src="https://user-images.githubusercontent.com/10553294/77442713-42000700-6df3-11ea-9b12-34cbfd0985fd.png">

<!-- tabs:start -->

#### __React__
<!-- panels:start -->
<!--div:react-->
```react
/* Default Table React example */
<DataTable
	columns={[
		{
			key: 'one',
			name: 'Header-1',
			className: 'selected',
			format: item => {
				return (<a>{item.one}</a>);
			}
		},
		{
			key: 'two',
			name: 'Header-2'
		},
		{
			key: 'three',
			name: 'Header-3'
		},
		{
			key: 'rowActions',
			className: 'row-actions'
		}
	]}
	items={[
		{ one: 'Item one', two: 'value-2', three: 'value-3' },
		{ one: 'Item four', two: 'value-5', three: 'value-6' }
	]}
/>;
```
<!-- panels:end -->

#### __HTML__
<!-- panels:start -->
<!--div:html-->
```html
TDB
```
<!-- panels:end -->
<!-- tabs:end -->


## Expandable

<img width="1195" alt="table-expandable" src="https://user-images.githubusercontent.com/10553294/77443902-0fa2d980-6df4-11ea-9cf4-8e9c5874f037.png">

<!-- tabs:start -->

#### __React__
<!-- panels:start -->
<!--div:react-->
```react
/* Expandable Table React example */
<DataTable
	columns={[
		{
			key: 'one',
			name: 'Header-1',
			className: 'selected',
			format: item => {
				return (<a>{item.one}</a>);
			}
		},
		{
			key: 'two',
			name: 'Header-2'
		},
		{
			key: 'three',
			name: 'Header-3'
		},
		{
			key: 'rowActions',
			className: 'row-actions'
		}
	]}
	items={[
		{ one: 'Item one', two: 'value-2', three: 'value-3' },
		{ one: 'Item four', two: 'value-5', three: 'value-6' }
	]}
/>;
```
<!-- panels:end -->

#### __HTML__
<!-- panels:start -->
<!--div:html-->
```html
TDB
```
<!-- panels:end -->
<!-- tabs:end -->

## Multi Selectable

<img width="1186" alt="table-multiSelectable" src="https://user-images.githubusercontent.com/10553294/77444342-5bee1980-6df4-11ea-8aa0-99c35abdbe18.png">

<!-- tabs:start -->

#### __React__
<!-- panels:start -->
<!--div:react-->
```react
/* Multi Selectable Table React example */
<DataTable
	multiSelectable
	preSelectAll
	hideMultiSelectableText={false}
	columns={[
		{
			key: 'one',
			name: 'Header-1',
			className: 'selected',
			format: item => {
				return (<a>{item.one}</a>);
			}
		},
		{
			key: 'two',
			name: 'Header-2'
		},
		{
			key: 'three',
			name: 'Header-3'
		},
		{
			key: 'rowActions',
			className: 'row-actions'
		}
	]}
	items={[
		{ one: 'Item one', two: 'value-2', three: 'value-3' },
		{ one: 'Item four', two: 'value-5', three: 'value-6' }
	]}
/>;
```
<!-- panels:end -->

#### __HTML__
<!-- panels:start -->
<!--div:html-->
```html
TDB
```
<!-- panels:end -->
<!-- tabs:end -->

## Non-Striped

<img width="1192" alt="table-striped" src="https://user-images.githubusercontent.com/10553294/77444480-8f30a880-6df4-11ea-948b-95e0e362a465.png">

<!-- tabs:start -->

#### __React__
<!-- panels:start -->
<!--div:react-->
```react
/* Non-Striped Table React example */
<DataTable
	striped={false}
	columns={[
		{
			key: 'one',
			name: 'Header-1',
			className: 'selected',
			format: item => {
				return (<a>{item.one}</a>);
			}
		},
		{
			key: 'two',
			name: 'Header-2'
		},
		{
			key: 'three',
			name: 'Header-3'
		},
		{
			key: 'rowActions',
			className: 'row-actions'
		}
	]}
	items={[
		{ one: 'Item one', two: 'value-2', three: 'value-3' },
		{ one: 'Item four', two: 'value-5', three: 'value-6' }
	]}
/>;
```
<!-- panels:end -->

#### __HTML__
<!-- panels:start -->
<!--div:html-->
```html
TDB
```
<!-- panels:end -->
<!-- tabs:end -->

## Paginated

<img width="1205" alt="table-paginated" src="https://user-images.githubusercontent.com/10553294/77444744-e6cf1400-6df4-11ea-857d-6493c380e2b5.png">


<!-- tabs:start -->

#### __React__
<!-- panels:start -->
<!--div:react-->
```react
/* Paginated Table React example */
class PaginatedTable extends React.Component {

	constructor(props) {
		super(props);
		this.deferSetState = this.deferSetState.bind(this);
		this.changeItemsPerPage = this.changeItemsPerPage.bind(this);
		this.loadMoreItems = this.loadMoreItems.bind(this);
		this.state = {
			loading: false,
			itemsPerPage: 20,
			offset: 0
		};
		const itemCount = 1000;
		// Generate a large (arbitrary) number of items to display in the table
		this.items = new Array(itemCount).fill(undefined).map((v, i) => {
			return { one: `Item ${i + 1}`, two: 'value-2', three: 'value-3' };
		});
	}

	deferSetState(state) {
		this.setState({
			loading: true
		}, () => {
			setTimeout(() => {
				this.setState({
					loading: false,
					...state
				});
			}, 100);
		});
	}

	changeItemsPerPage(e) {
		this.deferSetState({
			itemsPerPage: +e.target.value
		});
	}

	getItems() {
		if (this.state.itemsPerPage === -1) {
			return this.items;
		}
		return this.items.slice(this.state.offset, this.state.offset + this.state.itemsPerPage);
	}

	loadMoreItems(index) {
		this.deferSetState({
			offset: this.state.itemsPerPage * (index - 1)
		});
	}

	render() {
		return (
			<DataTable
				// enable paging
				paging
				numItemsPerPage={this.state.itemsPerPage}
				// current position in collection to render
				offset={this.state.offset}
				// Total number of items in collection
				count={this.items.length}
				items={this.getItems()}
				// control when per-page count change
				onChangeItemsPerPage={this.changeItemsPerPage}
				// called when any paging changes. Returns the new page
				loadMore={this.loadMoreItems}
				loading={this.state.loading}
				columns={[
					{
						key: 'one',
						name: 'Header-1',
						className: 'selected',
						format: item => {
							return (<a>{item.one}</a>);
						}
					},
					{
						key: 'two',
						name: 'Header-2'
					},
					{
						key: 'three',
						name: 'Header-3'
					},
					{
						key: 'rowActions',
						className: 'row-actions'
					}
				]}
			/>
		);
	}
}
```
<!-- panels:end -->

#### __HTML__
<!-- panels:start -->
<!--div:html-->
```html
TDB
```
<!-- panels:end -->
<!-- tabs:end -->

## Sortable

<img width="1190" alt="table-sortable" src="https://user-images.githubusercontent.com/10553294/77445030-40cfd980-6df5-11ea-925c-784ab718ac0b.png">

<!-- tabs:start -->

#### __React__
<!-- panels:start -->
<!--div:react-->
```react
/* Sortable Table React example */
<DataTable
	sortable
	onHeaderClick={(column) => {
		alert(`sorting ${JSON.stringify(column)}`);
	}}
	columns={[
		{
			key: 'one',
			name: 'Header-1',
			className: 'selected',
			format: item => {
				return (<a>{item.one}</a>);
			}
		},
		{
			key: 'two',
			name: 'Header-2',
			sortable: true
		},
		{
			key: 'three',
			name: 'Header-3'
		},
		{
			key: 'rowActions',
			className: 'row-actions'
		}
	]}
	items={[
		{ one: 'Item one', two: 'value-2', three: 'value-3' },
		{ one: 'Item four', two: 'value-5', three: 'value-6' }
	]}
/>;
```
<!-- panels:end -->

#### __HTML__
<!-- panels:start -->
<!--div:html-->
```html
TDB
```
<!-- panels:end -->
<!-- tabs:end -->