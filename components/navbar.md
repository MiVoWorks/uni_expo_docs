# Navbar

This components extends [Galio](http://galio.io/)'s NavBar component. 

This has the same props as the NavBar component but the whole navigation and programming logic is written inside of it.

#### Usage

To include

```text
import Navbar from '@components/Navbar'
```

```text
<Navbar
  navigation={this.props.navigation}
  title="Title"
  hasSearch
  showSearch
  searchCallback
  seachPlaceholder
  back
  white
/>
```

Props

| Prop          | Type         | Default           | Description                                                                     |
|---------------|--------------|-------------------|---------------------------------------------------------------------------------|
| back          | bool         | FALSE             | Adds a back button for your navBar.                                             |
| transparent   | bool         | FALSE             | Sets the backgroundColor and borderColor to 'transparent'                       |
| title         | node, string | null              | Title of the NavBar                                                             |
| titleStyle    | object       | null              | Sets the styling for the title                                                  |
| left          | node         | null              | Left side of the NavBar                                                         |
| leftStyle     | object       | null              | Sets the styling for the View wrapping the left side element.                   |
| leftIconColor | string       | theme.COLORS.ICON | Sets the color of the left side's icon.                                         |
| onLeftPress   | function     | () => {}          | Function for the left side of the navbar                                        |
| right         | node         | null              | Right side of the NavBar                                                        |
| rightStyle    | object       | null              | Sets the styling for the View wrapping the left side element.                   |
| optionLeft    | string       | Categories'       |                                                                                 |
| optionRight   | string       | Best Deals'       |                                                                                 |
| tabs          | array        | null              | array of objects following the next template: {id: 'example', title: 'Example'} |
| tabIndex      | number       | null              |                                                                                 |
| white         | bool         | FALSE             |                                                                                 |
| search        | bool         | FALSE             |                                                                                 |



