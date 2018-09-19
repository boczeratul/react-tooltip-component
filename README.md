# React Tooltip

A simple tooltip component for ReactJS.
React v16 compatible fork of [react-tooltip-component](https://github.com/minhtranite/react-tooltip-component)

## Installation

```bash
npm install --save-dev react-tooltip-component-16
```

## Usage

### Style

#### Webpack

```js
import 'react-tooltip-component-16/lib/tooltip.css';
//require('react-tooltip-component-16/lib/tooltip.css');
```

### Other

```html
<link rel="stylesheet" type="text/css" href="path/to/react-tooltip-component-16/lib/tooltip.css">
```

### JS

```js
import Tooltip from 'react-tooltip-component-16';

<Tooltip title='Tooltip on top' position='top'>
  <button className='btn btn-default'>Tooltip on top</button>
</Tooltip>
```

### UMD

```html
<link rel="stylesheet" type="text/css" href="path/to/react-tooltip-component-16/dist/tooltip.css">
<script src="path/to/react-tooltip-component-16/dist/react-tooltip-component-16.js"></script>
```

```js
const Tooltip = window.ReactTooltipComponent;
```

## Props

| Name | Type | Required | Default | Description |
|------|------|----------|---------|-------------|
| title | string | true |  |  |
| position | string | false | `top` | ['left', 'top', 'right', 'bottom'] |
| fixed | bool | false | true | fixed or not |
| container | element | false | document.body |  |
| children | node | true |  |

## Example

View [demo](http://minhtranite.github.io/react-tooltip-component) or example folder.
