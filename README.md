# New Learnings

This is a simple HTML and CSS code example that demonstrates how to create a responsive grid layout using CSS Grid.

## HTML Structure

The HTML file consists of a container div that contains five child divs with different classes. These child divs represent boxes and will be styled using CSS.

## CSS Styling

The CSS file contains the styles for the grid layout and the individual boxes.

### Grid Layout

The container div is styled as a grid using the `display: grid` property. It has a fixed width and height of 550px and 600px respectively. The `grid-template-columns` and `grid-template-rows` properties define the number and size of the grid columns and rows. In this example, there are three columns and three rows, each taking up an equal fraction of the available space (`1fr`). The `grid-gap` property adds a 1rem gap between the grid cells.

The `grid-template-areas` property is used to assign specific grid areas to each box. This allows us to control the placement of the boxes within the grid. For example, the "boxone" div is assigned to the top left cell of the grid.

### Box Styling

Each box div has a unique class and is styled using the `.item` selector. The background color is set to `#356dfcc3`, and the text is centered using `display: flex` and `justify-content: center` properties. The font size is set to 15px, and the font weight is set to 100. The text color is `aliceblue`.

### Responsive Design

To make the layout responsive, a media query is used. When the screen width is less than or equal to 500px, the body element gets a green border, and the boxes stack vertically. This is achieved by changing the `flex-direction` property of the `.item` and `.container` selectors to `column`.

## Usage

This code can be used as a starting point for creating a responsive grid layout in HTML and CSS. It can be customized by modifying the grid template areas, box styles, and media query breakpoints to suit specific design requirements.

To use this code, simply copy the HTML and CSS code into separate files (e.g., index.html and style.css) and link the CSS file in the HTML file using the `<link>` tag.



The Layout is like:-
![Screenshot (127)](https://github.com/theamaan/Penthara_Technologies_Assignment/assets/90848726/be6cc57f-48d1-4c09-80ce-4e0571534edf)


The Responsive Design is like:-
![Screenshot (128)](https://github.com/theamaan/Penthara_Technologies_Assignment/assets/90848726/079c6f91-fac8-4185-9033-7a18c7cb876b)
