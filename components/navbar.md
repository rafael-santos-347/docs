# NavBar
A powerful navigation header, the navbar includes support for styling just the way you want it.

### Usage
Imports:
```js
import { NavBar } from 'galio-framework';
```

Simple example:
```jsx
<NavBar title="Screen Title" />
```

### Props

|      Prop     |     Type     |      Default      |                          Description                          |
|:-------------:|:------------:|:-----------------:|:-------------------------------------------------------------:|
| back          | bool         | false             | Adds a back button for your navBar.                           |
| transparent   | bool         | false             | Sets the backgroundColor and borderColor to 'transparent'     |
| title         | node, string | null              | Title of the NavBar                                           |
| titleStyle    | object       | null              | Sets the styling for the title                                |
| left          | node         | null              | Left side of the NavBar                                       |
| leftStyle     | object       | null              | Sets the styling for the View wrapping the left side element. |
| leftIconColor | string       | theme.COLORS.ICON | Sets the color of the left side's icon.                       |
| onLeftPress   | function     | () => {}          | Function for the left side of the navbar                      |
| right         | node         | null              | Right side of the NavBar                                      |
| rightStyle    | object       | null              | Sets the styling for the View wrapping the left side element. |
