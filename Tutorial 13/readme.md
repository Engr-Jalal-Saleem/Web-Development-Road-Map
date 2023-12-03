# CSS Box Model Project

This project demonstrates the use of the CSS Box Model in creating webpage layouts.

## Project Structure

The project consists of two main files:

1. `index.html`: This file contains the HTML structure of the webpage. It includes three div elements with the class "box", and additional classes "box1" and "box2" for the second and third divs respectively.
2. `style.css`: This file contains the CSS styles for the webpage. It demonstrates the use of the CSS Box Model by applying different margins, borders, paddings, and content dimensions to the div elements.

## CSS Box Model

The CSS Box Model is a fundamental concept for building layouts in CSS. It consists of:

- **Content**: The actual content of the box, where text and images appear.
- **Padding**: Clears an area around the content. The padding is transparent.
- **Border**: A border that goes around the padding and content.
- **Margin**: Clears an area outside the border. The margin is transparent.

The total width of an element should be calculated like this:

`Total element width = width + left padding + right padding + left border + right border + left margin + right margin`

The total height of an element should be calculated like this:

`Total element height = height + top padding + bottom padding + top border + bottom border + top margin + bottom margin`

## Running the Project

To view the project, open the `index.html` file in your web browser. Make sure that the `style.css` file is in the same directory as the `index.html` file for the styles to be applied correctly.****
