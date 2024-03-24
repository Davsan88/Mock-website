# CCS Quick Reference Guide


## CSS Selectors
- **Element**: Targets specific HTML elements.
- **.class**: Applies styles to elements with the specified class.
- **#id**: Targets a unique element with the specified ID.


## CSS Colors
- **Name**: Simple, named colors (e.g., `red`).
- **HEX**: Hexadecimal values (e.g., `#ff0000`).
- **RGB(A)**: Red, Green, Blue (Alpha for opacity) values.


## CSS Backgrounds
- **background-color**: Sets the element's background color.
- **background-image**: Applies an image as the background.
- **background-position**: Adjusts the image's starting position.
- **background-size**: Specifies the size of the background image.


## CSS Borders
- **border-style**: Defines the border's style (`solid`, `dashed`).
- **border-width**: Sets the border's thickness.
- **border-color**: Specifies the border's color.
- **border-radius**: Rounds the border's corners.


## CSS Margins
- **margin**: Controls the outer space around an element.
- **margin-top**: Sets the top margin.
- **margin-right**: Sets the right margin.
- **margin-bottom**: Sets the bottom margin.
- **margin-left**: Sets the left margin.


## CSS Padding
- **padding**: Controls the space between an element's border and its content.
- **padding-top**: Sets the top padding.
- **padding-right**: Sets the right padding.
- **padding-bottom**: Sets the bottom padding.
- **padding-left**: Sets the left padding.


## CSS Height, Width & Max-Min-
- **height**: Specifies the height of an element.
- **width**: Specifies the width of an element.
- **max-height**: Sets the maximum height.
- **max-width**: Sets the maximum width.
- **min-height**: Sets the minimum height.
- **min-width**: Sets the minimum width.


## CSS Text
- **color**: Sets the text color.
- **text-align**: Aligns text horizontally within an element (`left`, `right`, `center`, `justify`).
- **text-decoration**: Adds decoration to text (`none`,`underline`, `line-through`, `overline`).
- **text-transform**: Controls the capitalization of text (`uppercase`, `lowercase`, `capitalize`).
- **text-shadow**: Adds shadow to text.


## CSS Fonts
- **font-family**: Specifies the font for text.
- **font-size**: Sets the size of the font.
- **font-weight**: Controls the weight (boldness) of the font.
- **font-style**: Defines the style of the font (`normal`, `italic`, `oblique`).
- **@font-face**: Specify the font name, and specify the URL where it can be found.
- **@import**: Utilizing `url()` from the repository.

## CSS Icons
- **Web fonts or images**: Icons can be added using font libraries like FontAwesome, Booostrap or Google, or as images.


## CSS Links
- **:link**: Styles for normal, unvisited links.
- **:visited**: Styles for links that the user has visited.
- **:hover**: Styles for when the mouse is over the link.
- **:active**: Styles for when the link is being clicked.


## CSS Lists
- **list-style-type**: Specifies the type of list item marker (`none`, `disc`, `circle`, `square`, `decimal`, `upper-roman`, `lower-alpha`).
- **list-style-image**: Uses an image as the list item marker.
- **list-style-position**: Determines whether the list item marker appears inside or outside the content flow.
- **list-style**: Shorthand property to set all list properties at once.


## CSS Positions
- **position: static**: Default. Not positioned in any special way.
- **position: relative**: Positioned relative to its normal position.
- **position: absolute**: Positioned relative to the nearest positioned ancestor.
- **position: fixed**: Positioned relative to the viewport.
- **position: sticky**: Behaves like `relative` and changes to `fixed` upon reaching a scroll position.


## CSS z-index
- **z-index**: Controls the stack order of positioned elements.
- **Value**: An integer that determines the element's order. Higher values are closer to the front.
- **Applicability**: Only affects elements with a `position` value other than `static` (e.g., `relative`, `absolute`, `fixed`, `sticky`).
- **Usage Example**: `z-index: 3;` places the element higher than those with lower z-index values.


## CSS Display
- **`none`**: Hides the element, removing it from the document layout.
- **`block`**: Makes the element a block-level element, starting on a new line and taking the full width available.
- **`inline`**: The element does not start on a new line and only takes up as much width as necessary.
- **`inline-block`**: Behaves like an inline element but can have a width and height set.
- **`flex`**: Displays an element as a block-level flex container.
- **`grid`**: Displays an element as a block-level grid container.


## CSS Overflow
- **`visible`**: Default. Content flows outside the container.
- **`hidden`**: Content exceeding the container is clipped.
- **`scroll`**: Adds scrollbars to see the hidden content.
- **`auto`**: Automatically adds scrollbars only when needed.


## CSS Float
- **`left`**: Element floats to the left of its container.
- **`right`**: Element floats to the right of its container.
- **`none`**: Default value. The element does not float.
- **`inherit`**: Inherits the float value from its parent element.


## CSS Clear
- **`none`**: The element is not pushed below floating elements.
- **`left`**: The element is moved below any left-floating elements.
- **`right`**: The element is moved below any right-floating elements.
- **`both`**: The element is moved below floating elements on either side.


## CSS Combinations
- **Descendant Selector (`space`)**: Targets all elements that are descendants of a specified element.
- **Child Selector (`>`)**: Targets direct children of a specified element.
- **Adjacent Sibling Selector (`+`)**: Targets an element immediately following another specific element.
- **General Sibling Selector (`~`)**: Targets all siblings of a specified element that follow it.

