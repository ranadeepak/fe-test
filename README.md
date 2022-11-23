# FrontEnd Developer Test

Build a simple and small application. 

<p>As for any app the user should be able to log in and out. User should be able to login with the following credentials should work: userName: admin, password: changeMe.<br/><br/>
After login user should see a grid/table in the middle of the page. This grid should display the data from the <b>Sample Data</b> listed below.
A simple grid in the middle of a page is a bit dull: build a story around it, decorate, add other UI components.<br/>
Use of javaScript frameworks or toolkits is permitted. The whole UI should be responsive.</p><br/>


## Requirements:
**(implement as many as possible)**<br/>
	+ We should be able to run the app locally using npm. <br/>
	+ The grid has to be entirely made of DIV elements. Don't use the <table> element. <br/>
	+ The grid rows are generated from JSON sample data, or some online datasource. <br/>
	+ The grid should be responsive. <br/>
	+ Data rows must scroll vertically and horizontally. <br/>
	+ The column headers have to remain fixed when scrolling data vertically, but have to follow the columns when scrolling horizontally (when rows are wider than the grid's body). <br/>
	+ The columns have a max width but can still handle long text content. <br/>
	+ Clicking the column header labels sorts the data ASC / DESC. <br/>
	+ Column headers show an icon to indicate which way the data is sorted. <br/>
	+ The UI provides a way for the user to remove the columns. <br/>
	+ Different data types are displayed differently within the grid cells (e.g. text vs decimal values vs dates). <br/>
	+ Make the application accessible. <br/>
	+ The user should be able to change the browser's zoom factor. <br/>
	+ Adding unit test or end to end tests is a big plus. <br/>
<br/>

## Sample Data:
<pre>
[{
	type: 'POS',
	extdesc: 'ABC VONS Store 1797 SAN DIEGO CAUS',
	description: 'POS Transaction VONS Store 1797 SAN DIEGO CAUS',
	amount: '-4.43',
	differed: false,
	date: '2016-02-23'
}, {
	type: 'CC',
	extdesc: 'Amazon.com',
	description: 'online retailer Amazon.com',
	amount: '-76.99',
	differed: true,
	date: '2016-04-08'
}, {
	type: 'POS',
	extdesc: 'shop #1',
	description: 'online retailer #1',
	amount: '-100',
	differed: false,
	date: '2016-05-12'
}, {
	type: 'DDeb',
	extdesc: 'shop #2',
	description: 'retailer #2',
	amount: '-120',
	differed: false,
	date: '2016-06-17'
}, {
	type: 'POS',
	extdesc: 'shop #3',
	description: 'online retailer #3',
	amount: '-130',
	differed: false,
	date: '2016-08-20'
}, {
	type: 'CC',
	extdesc: 'shop #4',
	description: 'retailer #4',
	amount: '-320',
	differed: true,
	date: '2016-10-30'
}, {
	type: 'POS',
	extdesc: 'shop #5',
	description: 'online retailer #5',
	amount: '-101',
	differed: false,
	date: '2016-11-01'
}]
</pre>
