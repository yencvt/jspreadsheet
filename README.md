# Jspreadsheet CE v4: The JavaScript spreadsheet

<b>Jexcel CE</b> has been renamed to <b>Jspreadsheet CE</b><br><br>

<br>

[**Jspreadsheet CE**](https://bossanova.uk/jspreadsheet/v4/) is a lightweight Vanilla JavaScript <b>data grid</b> plugin to create amazing web-based interactive HTML tables, and spreadsheets compatible data grid with other spreadsheet software. You can create an online spreadsheet table from a JS array,
JSON, CSV or XSLX files. You can copy from excel and paste straight to your Jspreadsheet CE spreadsheet and vice versa.
It is very easy to integrate any third party JavaScript plugins to create your own custom columns, custom editors, and customize any
feature into your application. Jspreadsheet CE has plenty of different input options through its native column types to cover the most common web-based application
requirements. It is a complete solution for web data management. Create amazing applications with Jspreadsheet CE JavaScript spreadsheet.

### Jspreadsheet Pro - Enterprise Solution
- [Jspreadsheet Pro](https://jspreadsheet.com/)

<br>

## Main advantages

- Make rich and user-friendly data grid interfaces with excel controls.
- You can easily handle complicated data inputs in a way users are used.
- Improve your user software experience.
- Create rich CRUDS and beautiful UI.
- Compatibility with excel: users can move data around with common copy and paste shortcuts.
- Easy customizations with easy third-party plugin integrations.
- Lean, fast and simple to use.
- Speed up your work dealing with difficult data entry in a web-based software.


## Screenshot

![The JavaScript spreadsheet](https://bossanova.uk/templates/default/img/jexcel.gif)

<br>

## Installation

### As node package
`npm install jspreadsheet-ce`

### As standalone library/js plugin
[Download ZIP](https://github.com/jspreadsheet/ce/archive/master.zip)

put and use the files of `dist` folder in your project (js library and css files)

### With a framework

See examples section for code examples of jspreadsheets with popular frameworks
### Basic demo

A basic example to integrate the Jspreadsheet in your website to create your first rich data grid. <https://codepen.io/hchiam/pen/qBRzXKK>


#### Usage

Add jexcel/jspreadsheet and jsuites to your html file

```html
<script src="https://bossanova.uk/jspreadsheet/v4/jexcel.js"></script>
<script src="https://jsuites.net/v4/jsuites.js"></script>
<link rel="stylesheet" href="https://jsuites.net/v4/jsuites.css" type="text/css" />
<link rel="stylesheet" href="https://bossanova.uk/jspreadsheet/v4/jexcel.css" type="text/css" />
```

You should initialize your table based on a div container, such as:
```html
<div id="spreadsheet"></div>
```

To initialize a Jspreadsheet CE table you should run JavaScript, such as:
```javascript
var data = [
    ['Jazz', 'Honda', '2019-02-12', '', true, '$ 2.000,00', '#777700'],
    ['Civic', 'Honda', '2018-07-11', '', true, '$ 4.000,01', '#007777'],
];

jspreadsheet(document.getElementById('spreadsheet'), {
    data:data,
    columns: [
        { type: 'text', title:'Car', width:120 },
        { type: 'dropdown', title:'Make', width:200, source:[ "Alfa Romeo", "Audi", "Bmw" ] },
        { type: 'calendar', title:'Available', width:200 },
        { type: 'image', title:'Photo', width:120 },
        { type: 'checkbox', title:'Stock', width:80 },
        { type: 'numeric', title:'Price', width:100, mask:'$ #.##,00', decimal:',' },
        { type: 'color', width:100, render:'square', }
    ]
});
```

Serve your html file and then you will get the rendered table in your browser

![sampleTable](./docs/sampleTable.png)

<br>

## Development

### Build your package
% npm run build

### Start a web service
% npm run start

<br>

## Data grid examples

- [React Implementation](https://bossanova.uk/jspreadsheet/v4/examples/react)\
A full example on how to integrate Jspreadsheet CE with React.

- [VUE Implementation](https://bossanova.uk/jspreadsheet/v4/examples/vue)\
A full example on how to integrate Jspreadsheet CE with Vue.

- [Search and pagination](https://bossanova.uk/jspreadsheet/v4/examples/datatables)\
Full spreadsheet example with search and pagination to bring great compatibility for those who love datatables.

- [Column types](https://bossanova.uk/jspreadsheet/v4/examples/column-types)\
Learn more about the powerful column types. This example brings all native column types and how to create your own custom type.

- [Javascript dropdown](https://bossanova.uk/jspreadsheet/v4/examples/dropdown-and-autocomplete)\
Full examples on how to handle simple, advanced, multiple, autocomplete and conditional dropdowns. Create amazing JavaScript tables using categories and images in your dropdowns.

- [Javascript calendar](https://bossanova.uk/jspreadsheet/v4/examples/javascript-calendar)\
Example from basic to advanced calendar usage, date and datetime picker.

- [Image upload](https://bossanova.uk/jspreadsheet/v4/examples/image-upload)\
This examples shows how to upload images to your spreadsheet.

- [Programmatically updates](https://bossanova.uk/jspreadsheet/v4/examples/programmatically-updates)\
How to update your spreadsheet and its data by JavaScript.

- [Table Style](https://bossanova.uk/jspreadsheet/v4/examples/table-style)\
Bring a very special touch to your applications customizing your JavaScript spreadsheet.

- [Events](https://bossanova.uk/jspreadsheet/v4/examples/events)\
Learn how to handle events on Jspreadsheet CE.

- [Importing data](https://bossanova.uk/jspreadsheet/v4/examples/import-data)\
How to import data from an external CSV, json file or XLSX.

- [Formulas](https://bossanova.uk/jspreadsheet/v4/examples/spreadsheet-formulas)\
Unleash the power of your tables bringing formulas and custom JavaScript methods on your Jspreadsheet spreadsheet.

- [Custom toolbars](https://bossanova.uk/jspreadsheet/v4/examples/spreadsheet-toolbars)\
Full example on how to enable nor customize your JavaScript spreadsheet toolbar.

- [Column comments](https://bossanova.uk/jspreadsheet/v4/examples/comments)\
Allow comments in your table spreadsheet.

- [Headers](https://bossanova.uk/jspreadsheet/v4/examples/headers)\
Enabled nested headers in your spreadsheet and learn how to set or get header values.

- [Translations](https://bossanova.uk/jspreadsheet/v4/examples/translations)\
How to translate the default messages from Jspreadsheet.

- [Merged cells](https://bossanova.uk/jspreadsheet/v4/examples/merged-cells)\
Full example on how to handle merge cells in your JavaScript tables.

- [Sorting columns](https://bossanova.uk/jspreadsheet/v4/examples/sorting)\
Example how to sort the table by a column via JavaScript.

- [Lazy loading](https://bossanova.uk/jspreadsheet/v4/examples/lazy-loading)\
This example brings a very nice feature to deal with large table datasets.

<br>

## Jspreadsheet CE History

### Jspreadsheet CE 4.13.0

- FormulaJS integration
- Webpack integration

### Jspreadsheet CE 4.6

<b>Jexcel</b> has been renamed to <b>Jspreadsheet</b>

### Jspreadsheet CE 4.0.0

A special thank to the [FDL - Fonds de Dotation du Libre](https://www.fdl-lef.org/) support and sponsorship that make this version possible with so many nice features.

- Support workbooks/tabs
- Create a dymic jexcel table from a HTML static element
- Highlight the border from cells after CTRL+C
- Footer with formula support
- Multiple columns resize
- JSON update support (Helpers to update a remote server)
- Global super event (centralized method to dispatch all events in one)
- Custom helpers: =PROGRESS (progressbar), =RATING (5 star rating)
- Custom helpers: =COLUMN, =ROW, =CELL, =TABLE, =VALUE information to be used on formula execution
- Dynamic nested header updates
- A new column type for HTML editing
- New flags such as: includeHeadersOnCopy, persistance, filters, autoCasting, freezeColumns
- New events such as: onevent, onchangepage, onbeforesave, onsave
- More examples and documentation

### Jspreadsheet CE 3.9.0 (Jexcel)
- New methods
- General fixes

### Jspreadsheet CE 3.6.0 (Jexcel)
- Better formula parsing
- New events
- New initialization options
- General fixes

### Jspreadsheet CE 3.2.3 (Jexcel)
- getMeta, setMeta methods
- Npm package with jSuites
- General fixes

### Jspreadsheet CE 3.0.1 (Jexcel)

Jspreadsheet CE v3 is a complete rebuilt JavaScript Vanilla version. For that reason it was not possible to keep a
complete compatibility with the previous version. If you are upgrading you might need to implement a few updates in your code.
If you have questions, you can review the article upgrading from Jspreadsheet CE v2 or Handsontable.

The Jspreadsheet CE v3 brings lot of great new features:

- Drag and drop columns.
- Resizable rows.
- Merge columns.
- Search.
- Pagination.
- Lazy loading.
- Full screen flag.
- Image upload.
- Native color picker.
- Better mobile compatibility.
- Better nested headers compatibility.
- Amazing keyboard navigation support.
- Better hidden column management.
- Great data picker: dropdown, autocomplete, multiple, group options and icons.
- Importing from XLSX (experimental).

Big improvements are included, such as:

- Complete new formula engine with no external dependencies with much faster results.
- Absolutely no selectors, means a much faster application.
- New native columns.
- jQuery is not required anymore.
- React, Vue and Angular examples.
- XLSX support using a custom sheetjs (experimental).


### Jspreadsheet CE 2.1.0 (Jexcel)

We are glad to bring you the latest jQuery plugin version, with the following improvements:

- Mobile touch fixes.
- Paste fixes & New CSV parser.

### Jspreadsheet CE 2.0.0 (Jexcel)

- New radio column.
- New dropdown with autocomplete and multiple selection options.
- Header/body separation for a better scroll/column resize behavior and compatibility.
- Better text-wrap including alt+enter excel compatibility.
- New set/get meta information.
- New set/get config parameters.
- New set/get programmatically cell style.
- New set/get cell comments.
- New table custom toolbar.
- New responsive calendar picker.

### Jspreadsheet CE 1.5.7 (Jexcel)

- Checkbox column type improvements.
- Destroy jQuery table updates.

### Jspreadsheet CE 1.5.1 (Jexcel)

- Spreadsheet data overflow and fixed headers. See an <a href='/jexcel/examples/table-with-fixed-headers'>example</a>.
- Navigation improvements.


### Jspreadsheet CE 1.5.0 (Jexcel)

- Relative insertRow, deleteRow, insertColumn, deleteColumn.
- Redo, Undo action tracker for insertRow, deleteRow, insertColumn, deleteColumn, moveRow.
- New formula column recursive chain.
- New alternative design option bootstrap-like.
- `updateSettings` updates.

<br>

## Official websites
- [Jspreadsheet CE v4 - Javascript Spreadsheet](https://bossanova.uk/jspreadsheet/v4)
- [Jspreadsheet CE v3 - Vanilla JavaScript](https://bossanova.uk/jspreadsheet/v3)
- [Jspreadsheet CE v2 - jQuery Plugin](https://bossanova.uk/jspreadsheet/v2)
- [Jspreadsheet Pro v10 - Javascript Spreadsheet](https://jspreadsheet.com/v10)
- [Jspreadsheet Pro v9 - Javascript Spreadsheet](https://jspreadsheet.com/v9)
- [Jspreadsheet Pro v8 - Javascript Spreadsheet](https://jspreadsheet.com/v8)
- [Jspreadsheet Pro v7 - Javascript Spreadsheet](https://jspreadsheet.com/v7)
<br>

## Community
- [GitHub](https://github.com/jspreadsheet/ce/issues)

<br>

## Contributing

See [contributing](contributing.md)

<br>

## Copyright and license
Jspreadsheet CE is released under the [MIT license]. Contact contact@jspreadsheet.com

<br>

## Other tools
- [LemonadeJS v1 Reactive Library](https://lemonadejs.net/v1/)
- [LemonadeJS v2 Reactive Library](https://lemonadejs.net/v2/)
- [LemonadeJS v3 Reactive Library](https://lemonadejs.net/v3/)

<br>

## jSuites

### Image cropper

#### Documentation

*   [Getting started](https://jsuites.net/v4/image-cropper)
*   [Quick reference](https://jsuites.net/v4/image-cropper/quick-reference)

#### Examples

*   [Rotate and zoom](https://jsuites.net/v4/image-cropper/rotate-and-zoom)
*   [Brightness and contrast](https://jsuites.net/v4/image-cropper/brightness-and-contrast-filters "Brightness and contrast")

#### Integrations

*   [React integration](https://jsuites.net/v4/image-cropper/react-component)
*   [Vue integration](https://jsuites.net/v4/image-cropper/image-cropper-vue-example)
*   [Angular integration](https://jsuites.net/v4/image-cropper/image-cropper-angular-example)

### Javascript Template

#### Documentation

*   [Getting started](https://jsuites.net/v4/javascript-template)
*   [Quick reference](https://jsuites.net/v4/javascript-template/quick-reference)

#### Examples

*   [Basic](https://jsuites.net/v4/javascript-template/basic)
*   [Pagination and Searching](https://jsuites.net/v4/javascript-template/pagination-and-searching)
*   [Methods](https://jsuites.net/v4/javascript-template/methods)
*   [Event Handling](https://jsuites.net/v4/javascript-template/event-handling)

### JavaScript Organogram

#### Documentation

*   [Getting started](https://jsuites.net/v4/organogram)
*   [Quick Reference](https://jsuites.net/v4/organogram/quick-reference)

#### Examples

*   [Basic](https://jsuites.net/v4/organogram/basic)
*   [Methods](https://jsuites.net/v4/organogram/methods)

#### Integrations

*   [React organogram](https://jsuites.net/v4/organogram/organogram-with-react)
*   [Vue organogram](https://jsuites.net/v4/organogram/organogram-with-vue)
*   [Angular organogram](https://jsuites.net/v4/organogram/organogram-with-angular)

### Javascript Heatmap

#### Documentation

*   [Getting started](https://jsuites.net/v4/heatmap)
*   [Quick reference](https://jsuites.net/v4/heatmap/quick-reference)

#### Examples

*   [Basic](https://jsuites.net/v4/heatmap/basic)
*   [Colors](https://jsuites.net/v4/heatmap/colors)
*   [Title and tooltip](https://jsuites.net/v4/heatmap/title-and-tooltip)

### Core features

#### Core

*   [Ajax requests](https://jsuites.net/v4/core/ajax)
*   [Animations](https://jsuites.net/v4/core/animations)
*   [Toast](https://jsuites.net/v4/core/javascript-toast)
*   [Loading spin](https://jsuites.net/v4/core/loading-spin)
*   [Drag and drop](https://jsuites.net/v4/core/js-drag-and-drop)

#### Helpers

*   [Push to refresh](https://jsuites.net/v4/core/push-to-refresh)
*   [Custom scroll](https://jsuites.net/v4/core/scroll)
*   [Generic lazy loading](https://jsuites.net/v4/core/lazy-loading)
*   [File upload](https://jsuites.net/v4/core/files)

### JavaScript Dropdown

#### Documentation

*   [Getting started](https://jsuites.net/v4/dropdown-and-autocomplete)
*   [Quick Reference](https://jsuites.net/v4/dropdown-and-autocomplete/quick-reference)

#### Examples

*   [Basic](https://jsuites.net/v4/dropdown-and-autocomplete/basic)
*   [Multiple options](https://jsuites.net/v4/dropdown-and-autocomplete/multiple)
*   [Large sample](https://jsuites.net/v4/dropdown-and-autocomplete/large-sample)
*   [Remote search](https://jsuites.net/v4/dropdown-and-autocomplete/remote-search)
*   [Add new option](https://jsuites.net/v4/dropdown-and-autocomplete/new-options)
*   [Images](https://jsuites.net/v4/dropdown-and-autocomplete/images)
*   [Colors](https://jsuites.net/v4/dropdown-and-autocomplete/colors)
*   [Countries](https://jsuites.net/v4/dropdown-and-autocomplete/countries)
*   [Grouping elements](https://jsuites.net/v4/dropdown-and-autocomplete/grouping-elements)
*   [Events](https://jsuites.net/v4/dropdown-and-autocomplete/events)
*   [Methods](https://jsuites.net/v4/dropdown-and-autocomplete/methods)
*   [Mobile rendering](https://jsuites.net/v4/dropdown-and-autocomplete/mobile)

#### Integrations

*   [React dropdown](https://jsuites.net/v4/dropdown-and-autocomplete/javascript-dropdown-with-react)
*   [Vue dropdown](https://jsuites.net/v4/dropdown-and-autocomplete/javascript-dropdown-with-vue)
*   [Angular dropdown](https://jsuites.net/v4/dropdown-and-autocomplete/javascript-dropdown-with-angular)

### JavaScript Calendar

#### Documentation

*   [Getting started](https://jsuites.net/v4/javascript-calendar)
*   [Quick Reference](https://jsuites.net/v4/javascript-calendar/quick-reference)

#### Examples

*   [Basic](https://jsuites.net/v4/javascript-calendar/basic)
*   [Time picker](https://jsuites.net/v4/javascript-calendar/time-picker)
*   [Year and month picker](https://jsuites.net/v4/javascript-calendar/year-month)
*   [Events](https://jsuites.net/v4/javascript-calendar/events)
*   [Valid range](https://jsuites.net/v4/javascript-calendar/valid-range)
*   [International](https://jsuites.net/v4/javascript-calendar/international)
*   [Methods](https://jsuites.net/v4/javascript-calendar/methods)
*   [Inline calendar](https://jsuites.net/v4/javascript-calendar/inline)
*   [Mobile rendering](https://jsuites.net/v4/javascript-calendar/mobile)

#### Integrations

*   [React calendar](https://jsuites.net/v4/javascript-calendar/javascript-calendar-with-react)
*   [Vue calendar](https://jsuites.net/v4/javascript-calendar/javascript-calendar-with-vue)
*   [Angular calendar](https://jsuites.net/v4/javascript-calendar/javascript-calendar-with-angular)

### Tags and keywords

#### Documentation

*   [Getting started](https://jsuites.net/v4/javascript-tags)
*   [Quick Reference](https://jsuites.net/v4/javascript-tags/quick-reference)

#### Examples

*   [Basic](https://jsuites.net/v4/javascript-tags/basic)
*   [Suggestions](https://jsuites.net/v4/javascript-tags/remote-search)
*   [Events](https://jsuites.net/v4/javascript-tags/events)
*   [Validations](https://jsuites.net/v4/javascript-tags/validations)

#### Integrations

*   [React tags](https://jsuites.net/v4/javascript-tags/javascript-tags-with-react)
*   [Vue tags](https://jsuites.net/v4/javascript-tags/javascript-tags-with-vue)
*   [Angular tags](https://jsuites.net/v4/javascript-tags/javascript-tags-with-angular)

### JavaScript tabs plugin

#### Documentation

*   [Getting started](https://jsuites.net/v4/javascript-tabs)
*   [Quick Reference](https://jsuites.net/v4/javascript-tabs/quick-reference)

#### Examples

*   [Basic](https://jsuites.net/v4/javascript-tabs/basic)
*   [Style](https://jsuites.net/v4/javascript-tabs/style)
*   [Headers with icons](https://jsuites.net/v4/javascript-tabs/icons)
*   [Remote content](https://jsuites.net/v4/javascript-tabs/remote)
*   [Events](https://jsuites.net/v4/javascript-tabs/events)
*   [Methods](https://jsuites.net/v4/javascript-tabs/methods)

### Color picker plugin

#### Documentation

*   [Getting started](https://jsuites.net/v4/color-picker)
*   [Quick Reference](https://jsuites.net/v4/color-picker/quick-reference)

#### Examples

*   [Basic](https://jsuites.net/v4/color-picker/basic)
*   [Events](https://jsuites.net/v4/color-picker/events)
*   [Custom colors](https://jsuites.net/v4/color-picker/custom-colors)
*   [Palettes](https://jsuites.net/v4/color-picker/color-palettes)
*   [Responsive](https://jsuites.net/v4/color-picker/mobile)

#### Examples

*   [React color picker](https://jsuites.net/v4/color-picker/javascript-color-picker-with-react)
*   [Vue color picker](https://jsuites.net/v4/color-picker/javascript-color-picker-with-vue)
*   [Angular color picker](https://jsuites.net/v4/color-picker/javascript-color-picker-with-angular)

### Context menu plugin

#### Documentation

*   [Getting started](https://jsuites.net/v4/contextmenu)
*   [Quick Reference](https://jsuites.net/v4/contextmenu/quick-reference)

#### Examples

*   [Basic](https://jsuites.net/v4/contextmenu/basic)
*   [Vanilla example](https://jsuites.net/v4/contextmenu/vanilla)
*   [Icons](https://jsuites.net/v4/contextmenu/icons)
*   [Submenu](https://jsuites.net/v4/contextmenu/submenu)

### Input mask plugin

#### Documentation

*   [Getting started](https://jsuites.net/v4/javascript-mask)
*   [Quick reference](https://jsuites.net/v4/javascript-mask/quick-reference)

#### Examples

*   [Basic](https://jsuites.net/v4/javascript-mask/basic)
*   [Events](https://jsuites.net/v4/javascript-mask/events)
*   [Programmatically updates](https://jsuites.net/v4/javascript-mask/programmatically-updates)

### JavaScript Modal

#### Documentation

*   [Getting started](https://jsuites.net/v4/modal)
*   [Quick reference](https://jsuites.net/v4/modal/quick-reference)

#### Examples

*   [Basic](https://jsuites.net/v4/modal/basic)
*   [Events](https://jsuites.net/v4/modal/events)
*   [React modal](https://jsuites.net/v4/modal/javascript-modal-with-react)

### Rich HTML Forms

#### Documentation

*   [Getting started](https://jsuites.net/v4/rich-form)
*   [Quick reference](https://jsuites.net/v4/rich-form/quick-reference)

#### Examples

*   [Tracking changes](https://jsuites.net/v4/rich-form/tracking-for-form-changes)
*   [Updates](https://jsuites.net/v4/rich-form/methods)
*   [Validations](https://jsuites.net/v4/rich-form/validations)

### JavaScript rating plugin

#### Documentation

*   [Getting started](https://jsuites.net/v4/rating)
*   [Quick reference](https://jsuites.net/v4/rating/quick-reference)

#### Examples

*   [Events](https://jsuites.net/v4/rating/events)

#### Integrations

*   [React Rating](https://jsuites.net/v4/rating/javascript-rating-with-react)
*   [Vue Rating](https://jsuites.net/v4/rating/javascript-rating-with-vue)
*   [Angular Rating](https://jsuites.net/v4/rating/javascript-rating-with-angular)

### JavaScript toolbar

#### Documentation

*   [Getting started](https://jsuites.net/v4/toolbar)
*   [Quick reference](https://jsuites.net/v4/toolbar/quick-reference)

#### Examples

*   [Fontawsome](https://jsuites.net/v4/toolbar/fontawsome)
*   [Custom icons](https://jsuites.net/v4/toolbar/custom-icons)

### Text editor plugin

#### Documentation

*   [Getting started](https://jsuites.net/v4/text-editor)
*   [Quick reference](https://jsuites.net/v4/text-editor/quick-reference)

#### Examples

*   [Basic](https://jsuites.net/v4/text-editor/basic)
*   [Custom toolbar](https://jsuites.net/v4/text-editor/custom-toolbar)
*   [Dropping zone](https://jsuites.net/v4/text-editor/dropping-zone)
*   [URL Snippets](https://jsuites.net/v4/text-editor/website-snippet)

### Picker plugin

#### Documentation

*   [Getting started](https://jsuites.net/v4/picker)
*   [Quick reference](https://jsuites.net/v4/picker/quick-reference)

#### Examples

*   [Basic](https://jsuites.net/v4/picker/basic)
*   [Stylize options](https://jsuites.net/v4/picker/stylize-options)
*   [Static front](https://jsuites.net/v4/picker/static-front)
*   [Handle changes](https://jsuites.net/v4/picker/handle-changes)

#### Integrations

*   [React Picker](https://jsuites.net/v4/picker/picker-with-react)
*   [Vue Picker](https://jsuites.net/v4/picker/picker-with-vue)
*   [Angular Picker](https://jsuites.net/v4/picker/picker-with-angular)

### Image slider plugin

#### Documentation

*   [Getting started](https://jsuites.net/v4/image-slider)
*   [Quick reference](https://jsuites.net/v4/image-slider/quick-reference)

#### Examples

*   [Basic](https://jsuites.net/v4/image-slider/basic)

### All Components

#### Core

*   [Ajax requests](https://jsuites.net/v4/core/ajax)
*   [Animations](https://jsuites.net/v4/core/animations)
*   [Toast](https://jsuites.net/v4/core/javascript-toast)
*   [Loading spin](https://jsuites.net/v4/core/loading-spin)
*   [Drag and drop](https://jsuites.net/v4/core/js-drag-and-drop)

#### Extensions

*   [Cropper](https://jsuites.net/v4/image-cropper)
*   [Template](https://jsuites.net/v4/javascript-template)
*   [Organogram](https://jsuites.net/v4/organogram)
*   [Heatmap](https://jsuites.net/v4/heatmap)

#### Components

*   [Calendar](https://jsuites.net/v4/javascript-calendar)
*   [Color picker](https://jsuites.net/v4/color-picker)
*   [Context menu](https://jsuites.net/v4/contextmenu)
*   [Dropdown](https://jsuites.net/v4/dropdown-and-autocomplete)
*   [Mask](https://jsuites.net/v4/javascript-mask)
*   [Modal](https://jsuites.net/v4/modal)
*   [Picker](https://jsuites.net/v4/picker)
*   [Rating](https://jsuites.net/v4/rating)
*   [Rich forms](https://jsuites.net/v4/rich-form)
*   [Richtext](https://jsuites.net/v4/text-editor)
*   [Slider](https://jsuites.net/v4/image-slider)
*   [Tags](https://jsuites.net/v4/javascript-tags)
*   [Tabs](https://jsuites.net/v4/javascript-tabs)
*   [Toolbars](https://jsuites.net/v4/toolbar)

<table class="table">
<thead><tr><th>Method</th><th>Example</th></tr></thead>
<tbody>
<tr>
    <td><b>getData:</b> Get the full or partial table data<br>@Param boolan onlyHighlighedCells - Get only highlighted cells</td>
    <td>myTable.getData([bool]);</td>
</tr>
<tr>
    <td><b>getJson:</b> Get the full or partial table data in JSON format<br>@Param boolan onlyHighlighedCells - Get only highlighted cells</td>
    <td>myTable.getData([bool]);</td>
</tr>
<tr>
    <td><b>getRowData:</b> Get the data from one row by number<br>@Param integer rowNumber - Row number</td>
    <td>myTable.getRowData([int]);</td>
</tr>
<tr>
    <td><b>setRowData:</b> Set the data from one row by number<br>@Param integer rowNumber - Row number<br>@param array rowData - Row data</td>
    <td>myTable.setRowData([int], [array]);</td>
</tr>
<tr>
    <td><b>getColumnData:</b> Get the data from one column by number<br>@Param integer columnNumber - Column number</td>
    <td>myTable.getColumnData([int]);</td>
</tr>
<tr>
    <td><b>setColumnData:</b> Set the data from one column by number<br>@Param integer columnNumber - Column number<br>@param array colData - Column data</td>
    <td>myTable.setColumnData([int], [array]);</td>
</tr>
<tr>
    <td><b>setData:</b> Set the table data<br>@Param json newData - New json data, null will reload what is in memory.</td>
    <td>myTable.setData([json]);</td>
</tr>
<tr>
    <td><b>setMerge:</b> Merge cells<br>@Param string columnName - Column name, such as A1.<br>@Param integer colspan - Number of columns<br>@Param integer rowspan - Number of rows<br></td>
    <td>myTable.setMerge([string], [int], [int]);</td>
</tr>
<tr>
    <td><b>getMerge:</b> Get merged cells properties<br>@Param string columnName - Column name, such as A1.</td>
    <td>myTable.getMerge([string]);</td>
</tr>
<tr>
    <td><b>removeMerge:</b> Destroy merged by column name<br>@Param string columnName - Column name, such as A1.</td>
    <td>myTable.removeMerge([string]);</td>
</tr>
<tr>
    <td><b>destroyMerged:</b> Destroy all merged cells</td>
    <td>myTable.destroyMerge();</td>
</tr>
<tr>
    <td><b>getCell</b>: get current cell DOM<br>@Param string columnName - str compatible with excel, or as object.</td>
    <td>myTable.getCell([string]);</td>
</tr>
<tr>
    <td><b>getLabel</b>: get current cell DOM innerHTML<br>@Param string columnName - str compatible with excel, or as object.</td>
    <td>myTable.getLabel([string]);</td>
</tr>
<tr>
    <td><b>getValue:</b> get current cell value<br>@Param mixed cellIdent - str compatible with excel, or as object.</td>
    <td>myTable.getValue([string]);</td>
</tr>
<tr>
    <td><b>getValueFromCoords:</b> get value from coords<br>@Param integer x<br>@Param integer y<br></td>
    <td>myTable.getValueFromCoords([integer], [integer]);</td>
</tr>
<tr>
    <td><b>setValue:</b> change the cell value<br>@Param mixed cellIdent - str compatible with excel, or as object.<br>@Param string Value - new value for the cell<br>@Param bool force - update readonly columns</td>
    <td>myTable.setValue([string], [string], [bool]);</td>
</tr>
<tr>
    <td><b>setValueFromCoords:</b> get value from coords<br>@Param integer x<br>@Param integer y<br>@Param string Value - new value for the cell<br>@Param bool force - update readonly columns</td>
    <td>myTable.getValueFromCoords([integer], [integer], [string], [bool]);</td>
</tr>
<tr>
    <td><b>resetSelection:</b> Reset the table selection<br>@Param boolean executeBlur - execute the blur from the table<br></td>
    <td>myTable.resetSelection([bool]);</td>
</tr>
<tr>
    <td><b>updateSelection:</b> select cells<br>@Param object startCell - cell object<br>@Param object endCell - cell object<br>@Param boolean ignoreEvents - ignore onselection event</td>
    <td>myTable.updateSelection([cell], [cell], true);</td>
</tr>
<tr>
    <td><b>updateSelectionFromCoords:</b> select cells<br>@Param integer x1<br>@Param integer y1<br>@Param integer x2<br>@Param integer y2</td>
    <td>myTable.updateSelectionFromCoords([integer], [integer], [integer], [integer]);</td>
</tr>
<tr>
    <td><b>getWidth:</b> get the current column width<br>@Param integer columnNumber - column number starting on zero</td>
    <td>myTable.getWidth([integer]);</td>
</tr>
<tr>
    <td><b>setWidth:</b> change column width<br>@Param integer columnNumber - column number starting on zero<br>@Param string newColumnWidth - New column width</td>
    <td>myTable.setWidth([integer], [integer]);</td>
</tr>
<tr>
    <td><b>getHeight:</b> get the current row height<br>@Param integer rowNumber - row number starting on zero</td>
    <td>myTable.getHeight([integer]);</td>
</tr>
<tr>
    <td><b>setHeight:</b> change row height<br>@Param integer rowNumber - row number starting on zero<br>@Param string newRowHeight- New row height</td>
    <td>myTable.setHeight([integer], [integer]);</td>
</tr>
<tr>
    <td><b>getHeader:</b> get the current header by column number<br>@Param integer columnNumber - Column number starting on zero</td>
    <td>myTable.getHeader([integer]);</td>
</tr>
<tr>
    <td><b>getHeaders:</b> get all header titles</td>
    <td>myTable.getHeaders();</td>
</tr>
<tr>
    <td><b>setHeader:</b> change header by column<br>@Param integer columnNumber - column number starting on zero<br>@Param string columnTitle - New header title</td>
    <td>myTable.setHeader([integer], [string]);</td>
</tr>
<tr>
    <td><b>getStyle:</b> get table or cell style<br>@Param mixed - cell identification or null for the whole table.</td>
    <td>myTable.getStyle([string]));</td>
</tr>
<tr>
    <td><b>setStyle:</b> set cell(s) CSS style<br>@Param mixed - json with whole table style information or just one cell identification. Ex. A1.<br>@param k [optional]- CSS key<br>@param v [optional]- CSS value</td>
    <td>myTable.setSyle([object], [string], [string]);</td>
</tr>
<tr>
    <td><b>resetStyle:</b> remove all style from a cell<br>@Param string columnName - Column name, example: A1, B3, etc</td>
    <td>myTable.resetStyle([string]);</td>
</tr>
<tr>
    <td><b>getComments:</b> get cell comments<br>@Param mixed - cell identification or null for the whole table.</td>
    <td>myTable.getComments([string]);</td>
</tr>
<tr>
    <td><b>setComments:</b> set cell comments<br>@Param cell - cell identification<br>@Param text - comments</td>
    <td>myTable.setComments([string], [string]);</td>
</tr>
<tr>
    <td><b>orderBy:</b> reorder a column asc or desc<br>@Param integer columnNumber - column number starting on zero<br>@Param smallint sortType - One will order DESC, zero will order ASC, anything else will toggle the current order</td>
    <td>myTable.orderBy([integer], [boolean]);</td>
</tr>
<tr>
    <td><b>getConfig:</b> get table definitions</td>
    <td>myTable.getConfig();</td>
</tr>
<tr>
    <td><b>insertColumn:</b> add a new column<br>@param mixed - num of columns to be added or data to be added in one single column<br>@param int columnNumber - number of columns to be created<br>@param boolean insertBefore<br>@param object properties - column properties</td>
    <td>myTable.insertColumn([mixed], [integer], [boolean], [object]);</td>
</tr>
<tr>
    <td><b>deleteColumn:</b> remove column by number<br>@Param integer columnNumber - Which column should be excluded starting on zero<br>@param integer numOfColumns - number of columns to be excluded from the reference column</td>
    <td>myTable.deleteColumn([integer], [integer]);</td>
</tr>
<tr>
    <td><b>moveColumn:</b> change the column position<br>@Param integer columnPosition<br>@Param integer newColumnPosition</td>
    <td>myTable.moveColumn([integer], [integer]);</td>
</tr>
<tr>
    <td><b>insertRow:</b> add a new row<br>@Param mixed - number of blank lines to be insert or a single array with the data of the new row<br>@Param integer rowNumber - reference row number<br>@param boolean insertBefore</td>
    <td>myTable.insertRow([mixed], [integer], [boolean]);</td>
</tr>
<tr>
    <td><b>deleteRow:</b> remove row by number<br>@Param integer rowNumber - Which row should be excluded starting on zero<br>@Param integer numOfRows - number of lines to be excluded</td>
    <td>myTable.deleteRow([integer], [integer]);</td>
</tr>
<tr>
    <td><b>moveRow:</b> change the row position<br>@Param integer rowPosition<br>@Param integer newRowPosition</td>
    <td>&gt;myTable.moveRow([integer], [integer]);</td>
</tr>
<tr>
    <td><b>download:</b> get the current data as a CSV file<br>@Param bool - true to download parsed formulas.</td>
    <td>myTable.download([bool]);</td>
</tr>
<tr>
    <td><b>getMeta:</b> get the table or cell meta information<br>@Param mixed - cell identification or null for the whole table.</td>
    <td>myTable.getMeta([string]);</td>
</tr>
<tr>
    <td><b>setMeta:</b> set the table or cell meta information<br>@Param mixed - json with whole table meta information.</td>
    <td>myTable.setMeta[mixed]);</td>
</tr>
<tr>
    <td><b>fullscreen:</b> Toogle table fullscreen mode<br>@Param boolan fullscreen - define fullscreen status as true or false</td>
    <td>myTable.fullscreen([bool]);</td>
</tr>
<tr>
    <td><b>getSelectedRows:</b> Get the selected rows<br>@Param boolan asIds - Get the rowNumbers or row DOM elements</td>
    <td>myTable.getSelectedRows([bool]);</td>
</tr>
<tr>
    <td><b>getSelectedColumns:</b> Get the selected columns</td>
    <td>myTable.getSelectedColumns();</td>
</tr>
<tr>
    <td><b>showIndex:</b> show column of index numbers</td>
    <td>myTable.showIndex();</td>
</tr>
<tr>
    <td><b>hideIndex:</b> hide column of index numbers</td>
    <td>myTable.hideIndex();</td>
</tr>
<tr>
    <td><b>search:</b> search in the table, only if directive is enabled during inialization.<br>@Param string - Search for word</td>
    <td>myTable.search([string]);</td>
</tr>
<tr>
    <td><b>resetSearch:</b> reset search table</td>
    <td>myTable.resetSearch();</td>
</tr>
<tr>
    <td><b>whichPage:</b> Which page showing on Jspreadsheet - Valid only when pagination is true.</td>
    <td>myTable.whichPage();</td>
</tr>
<tr>
    <td><b>page:</b> Go to page number- Valid only when pagination is true.<br>@Param integer - Go to page number</td>
    <td>myTable.page([integer]);</td>
</tr>
<tr>
    <td><b>undo:</b> Undo last changes</td>
    <td>myTable.undo();</td>
</tr>
<tr>
    <td><b>redo:</b> Redo changes</td>
    <td>myTable.redo();</td>
</tr>
</tbody>
</table>


<table class="table">
<thead><tr><th>Event</th><th>description</th></tr></thead>
<tbody>
<tr>
    <td><b>onload</b></td>
    <td>This method is called when the method setData</td>
</tr>
<tr>
    <td><b>onbeforechange</b></td>
    <td>Before a column value is changed. NOTE: It is possible to overwrite the original value, by return a new value on this method. v3.4.0+</td>
</tr>
<tr>
    <td><b>onchange</b></td>
    <td>After a column value is changed.</td>
</tr>
<tr>
    <td><b>onafterchanges</b></td>
    <td>After all changes are applied in the table.</td>
</tr>
<tr>
    <td><b>onpaste</b></td>
    <td>After a paste action is performed in the javascript table.</td>
</tr>
<tr>
    <td><b>onbeforepaste</b></td>
    <td>Before the paste action is performed. Used to parse any input data, should return the data.</td>
</tr>
<tr>
    <td><b>oninsertrow</b></td>
    <td>After a new row is inserted.</td>
</tr>
<tr>
    <td><b>onbeforeinsertrow</b></td>
    <td>Before a new row is inserted. You can cancel the insert event by returning false.</td>
</tr>
<tr>
    <td><b>ondeleterow</b></td>
    <td>After a row is excluded.</td>
</tr>
<tr>
    <td><b>onbeforedeleterow</b></td>
    <td>Before a row is deleted. You can cancel the delete event by returning false.</td>
</tr>
<tr>
    <td><b>oninsertcolumn</b></td>
    <td>After a new column is inserted.</td>
</tr>
<tr>
    <td><b>onbeforeinsertcolumn</b></td>
    <td>Before a new column is inserted. You can cancel the insert event by returning false.</td>
</tr>
<tr>
    <td><b>ondeletecolumn</b></td>
    <td>After a column is excluded.</td>
</tr>
<tr>
    <td><b>onbeforedeletecolumn</b></td>
    <td>Before a column is excluded. You can cancel the insert event by returning false.</td>
</tr>
<tr>
    <td><b>onmoverow</b></td>
    <td>After a row is moved to a new position.</td>
</tr>
<tr>
    <td><b>onmovecolumn</b></td>
    <td>After a column is moved to a new position.</td>
</tr>
<tr>
    <td><b>onresizerow</b></td>
    <td>After a change in row height.</td>
</tr>
<tr>
    <td><b>onresizecolumn</b></td>
    <td>After a change in column width.</td>
</tr>
<tr>
    <td><b>onselection</b></td>
    <td>On the selection is changed.</td>
</tr>
<tr>
    <td><b>onsort</b></td>
    <td>After a colum is sorted.</td>
</tr>
<tr>
    <td><b>onfocus</b></td>
    <td>On table focus</td>
</tr>
<tr>
    <td><b>onblur</b></td>
    <td>On table blur</td>
</tr>
<tr>
    <td><b>onmerge</b></td>
    <td>On column merge</td>
</tr>
<tr>
    <td><b>onchangeheader</b></td>
    <td>On header change</td>
</tr>
<tr>
    <td><b>onundo</b></td>
    <td>On undo is applied</td>
</tr>
<tr>
    <td><b>onredo</b></td>
    <td>On redo is applied</td>
</tr>
<tr>
    <td><b>oneditionstart</b></td>
    <td>When a openEditor is called.</td>
</tr>
<tr>
    <td><b>oneditionend</b></td>
    <td>When a closeEditor is called.</td>
</tr>
<tr>
    <td><b>onchangestyle</b></td>
    <td>When a setStyle is called.</td>
</tr>
<tr>
    <td><b>onchangemeta</b></td>
    <td>When a setMeta is called.</td>
</tr>
</tbody>
</table>
