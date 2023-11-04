
# Drag and Drop List Items

This is a simple HTML, CSS, and JavaScript project that allows you to drag and drop list items between two containers. The project provides a user-friendly interface with a visually appealing design and drag-and-drop functionality. Here's a brief overview of the code and how to use it:

## Project Structure

- **index.html**: This HTML file defines the structure of the web page. It contains two containers: `left` and `right`, with list items that can be dragged and dropped between them.

- **style.css**: The CSS file provides the styling for the page, including the container layout, list item appearance, and other visual elements.

- **script.js**: The JavaScript file contains the logic for making the list items draggable and implementing the drag-and-drop functionality.

## Usage

1. Open the `index.html` file in your web browser.

2. You will see two containers, the left one with draggable list items and the right one empty.

3. To move a list item, click and drag it from the left container (under "List Item 1," "List Item 2," etc.).

4. You can drop the list item into the right container. It will be added to the right container.

5. You can also drag the item back to the left container.

## Code Explanation

- The project uses HTML5's drag-and-drop API to make the list items draggable.

- The CSS file provides a visually appealing design, including a background color, border styles, and font choices.

- The JavaScript code adds event listeners to the list items. When a list item is dragged (`dragstart` event), it is marked as "selected."

- The right and left containers have event listeners for the `dragover` and `drop` events. When a list item is dropped into the right container, it is appended to the container. If it's dropped back into the left container, it's appended there.

## Contributing

Feel free to contribute to this project by opening issues, suggesting improvements, or submitting pull requests. Your contributions are highly appreciated.


Enjoy experimenting with drag and drop functionality with this project! If you have any questions or suggestions, please don't hesitate to reach out and contribute to this project.
