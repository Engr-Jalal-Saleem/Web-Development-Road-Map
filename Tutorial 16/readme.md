# CSS Specificity & Cascade Project

This project demonstrates the concepts of CSS Specificity and the Cascade.

## Project Structure

The project consists of two main files:

1. `index.html`: This file contains the HTML structure of the webpage. It includes an h1 element with multiple classes and a data attribute.
2. `style.css`: This file contains the CSS styles for the webpage. It demonstrates the concepts of CSS Specificity and the Cascade by applying different styles to the h1 element based on different selectors.

## CSS Specificity and the Cascade

CSS Specificity is the set of rules applied to CSS selectors in order to determine which style is applied to an element. The Cascade is the process of combining different stylesheets and resolving conflicts between different CSS rules and declarations when more than one rule applies to a certain element.


## The Cascade Algorithm:

---



CSS stands for Cascading Stylesheets. The cascade is the algorithm for solving conflicts where multiple CSS rules apply to an HTML element. It's the reason that the text of the button styled with the above CSS will be purple.

Understanding the cascade algorithm helps you understand how the browser resolves conflicts like this. The cascade algorithm has 4 distinct stages.

1. **Position and order of appearance** : the order in which your CSS rules appear
2. **Specificity** : an algorithm that determines which CSS selector has the strongest match
3. **Origin** : the order in which CSS appears and where it comes from, whether that is a browser style, CSS from a browser extension, or your authored CSS
4. **Importance** : some CSS rules are weighted more heavily than others, especially with the `!important` rule type

## Running the Project

To view the project, open the `index.html` file in your web browser. Make sure that the `style.css` file is in the same directory as the `index.html` file for the styles to be applied correctly.****


#### Specificity Calculation:

To calculate specificity, assign a value to each part of the selector:

* Universal Selector: 0
* Element selectors and pseudo-elements: 1
* Class selectors, attribute selectors, and pseudo-classes: 10
* ID selectors: 100
* Inline styles: 1000
