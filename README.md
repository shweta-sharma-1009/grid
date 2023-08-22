Hosted Link - https://shweta-sharma-1009.github.io/grid/

HTML -
![Screenshot (337)](https://github.com/shweta-sharma-1009/grid/assets/128416925/6772006a-ff60-45fa-a357-c2876e9e7f30) 
![Screenshot (338)](https://github.com/shweta-sharma-1009/grid/assets/128416925/2f059e06-8281-4c1f-9d88-37c6560c1db6)
![Screenshot (339)](https://github.com/shweta-sharma-1009/grid/assets/128416925/612335d0-a326-4c9c-b1b7-7a2db5fb5421)
![Screenshot (340)](https://github.com/shweta-sharma-1009/grid/assets/128416925/038ef26e-484e-47df-90d3-e84efc9ce613)
CSS - 
![Screenshot (341)](https://github.com/shweta-sharma-1009/grid/assets/128416925/0fcb16c0-2032-4434-bf7f-a07cf4375563)
![Screenshot (342)](https://github.com/shweta-sharma-1009/grid/assets/128416925/a18ec984-f391-4d41-9431-d011c7926bfb)
![Screenshot (343)](https://github.com/shweta-sharma-1009/grid/assets/128416925/2f0abd6c-357c-4683-ad6a-0ab07c5bca8d)
![Screenshot (344)](https://github.com/shweta-sharma-1009/grid/assets/128416925/22e25652-66c5-4966-b9a4-4a3d5249284b)
![Screenshot (345)](https://github.com/shweta-sharma-1009/grid/assets/128416925/328daa9b-5a4a-4b20-8138-d8f2f940bb2c)
![Screenshot (346)](https://github.com/shweta-sharma-1009/grid/assets/128416925/7d84cc1f-0c05-4bee-aabd-81f8c00ce38b)
![Screenshot (347)](https://github.com/shweta-sharma-1009/grid/assets/128416925/728a2dfd-75c7-4949-8913-fc9aed8df9a9)
![Screenshot (348)](https://github.com/shweta-sharma-1009/grid/assets/128416925/0fffd5ac-424b-4c2a-a9ff-3a58fe7767d9)

Description:-

HTML -
1 . Document Structure:
<!DOCTYPE html>: This declaration specifies that the document is an HTML5 document.
<html lang="en">: The root element of the HTML document, specifying the language of the content.
2 . Head Section:
<head>: This section contains metadata and resources related to the webpage.
<meta charset="UTF-8">: Sets the character encoding to UTF-8, which supports a wide range of characters.
<meta http-equiv="X-UA-Compatible" content="IE=edge">: Instructs Internet Explorer to use the latest rendering engine.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport properties for responsive design.
Google Font Stylesheet: Links to Google Fonts for including custom fonts.
Custom CSS Stylesheet: Links to an external stylesheet named "style.css".
<title>FEM grid</title>: Sets the title of the webpage that appears in the browser tab.
3 . Body Section:
<body>: The main content of the webpage.
<main class="testimonial-grid">: A container for the testimonial grid section.
4 . Testimonial Articles:
The webpage contains several testimonial articles, each represented by an <article> element with different classes for styling.
Testimonial 1:
grid-col-span-2 flow bg-primary-400 quote text-neutral-100: Classes for styling purposes.
Testimonial content including an image, name, position, and paragraphs of text.
Testimonial 2-5: Similar structure with different content and styles.
5 . Testimonial Content:
Each testimonial article follows a consistent structure:
<div class="flex">: A flex container for arranging content side by side.
<div> and <img>: Container for an image with the src attribute specifying the image file and alt attribute for accessibility.
<div>, <h2>, and <p>: Container for the testimonial author's name and position.
<p>: Paragraphs containing the testimonial content.
6 . Closing Tags:
The closing tags </article> and </main> close the opened elements.
7 . Image Paths:
The <img> elements reference image files using the src attribute, such as "./images/image-daniel.jpg". The ./ signifies the current directory.
8 . External CSS:
The stylesheet "style.css" is linked in the <head> section. It likely contains additional styling rules for the elements in the HTML.
  
Overall, the HTML code structures a webpage with a responsive grid layout displaying multiple testimonials from verified graduates of a bootcamp or learning program. The testimonials include images, names, positions, and personal experiences. 
The CSS styles defined in the linked "style.css" file likely handle the visual appearance and layout of the elements on the webpage.

CSS -

1 . CSS Variables: These are custom properties that can be used throughout the stylesheet to define reusable values. They are prefixed with "--". The variables in this code include colors, font settings, font weights, and font sizes. For instance:
--clr-primary-400: Defines the primary color in HSL format (hue, saturation, lightness).
--ff-primary: Specifies the primary font family.
--fs-300, --fs-400, --fs-500: Sets different font sizes.
2 . Global Styles:
box-sizing: Sets the box-sizing to border-box to include padding and border in the element's total width and height.
body styles: Sets default styles for the body element, including min-height, text-rendering, and line-height.
3 . Element Reset:
Resets margins for various HTML elements to 0, removing unwanted default spacing.
Removes list styles for lists (ul and ol) with a role attribute suggesting default styling should be removed.
Applies smooth scrolling behavior when focusing elements within the html element.
4 . Accessibility and Defaults:
a:not([class]): Styles unclassed anchor (a) elements to handle text decoration skipping.
Makes images (img, picture) responsive by setting max-width to 100% and display to block.
Inherit fonts for form elements (input, button, textarea, select).
5 . Reduced Motion Media Query:
Overrides animations and transitions for users with reduced motion preferences.
6 . Body Styles:
Defines overall styles for the body element, such as display: grid for centering content and setting the background color.
7 . Typography Styles:
Adjusts font weights for various heading levels (h1, h2, h3).
8 . Utility Classes:
.flex: Defines a flexible display with a customizable gap.
.flow: Adds margin-top to all children except the first child.
9 . Color and Background Classes:
Background and text color classes for various elements using custom HSL values.
10 . Component Styles:
Styles for a testimonial grid component.
.testimonial-grid defines the layout using CSS Grid, with different responsive layouts based on screen width.
.testimonial styles individual testimonial items, including font sizes, padding, box-shadow, and other visual details.
Media queries adjust the grid layout at different screen widths.
.testimonial.quote adds a background image to certain testimonial elements.
11 . Testimonial Details:
Styles for testimonial content, such as images, names, positions, and text paragraphs.

The CSS code provided seems to be part of a project's styling, particularly for a testimonial section. 
It includes responsive design considerations, utility classes, and component styles to create a consistent and visually appealing UI.









