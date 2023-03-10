# Table actions extra

Simple & customizable table with search, sort, pagination and checkbox functions
in vanilla JS with extra functionalities

## Development

Docker container running lite-server and watching code changes

```bash
make watch
```

Results can be tested in demos:

- [http://localhost:3000/demo/html-data-table.html](http://localhost:3000/demo/html-data-table.html)
- [http://localhost:3000/demo/json-data-table.html](http://localhost:3000/demo/json-data-table.html)

## Generate bundle

Local bundle pack with project name and actual project version in root folder

```bash
make bundle
```

## Run tests

Execute all tests suites of root `/tests` folder

```bash
make test
```

## More

To see all make commands

```bash
make help
```

## Installation

```bash
yarn add table-actions
```

Or directly in the HTML file

```html
<!-- Add to head HTML tag -->
<link rel="stylesheet" href="./css/table-actions.min.css" />
<!-- Add to the bottom of body HTML tag -->
<script src="./dist/table-actions.js"></script>

<!-- or directly from unpkg -->
<link
  rel="stylesheet"
  href="https://unpkg.com/table-actions@latest/css/table-actions.min.css"
/>
<script src="https://unpkg.com/table-actions@latest/dist/table-actions.min.js"></script>
```

## Run

```js
// Utils library functions: toNormalForm and newElement can be imported here
import { TableActions } from "table-actions";

const table = new TableActions("elementOrQuerySelector", {
  /* options */
}); // only this line when included with script HTML tag
```

## Features

- Select column search with all values of a column to be selected as filter
