# Apparel Online Store
### Code Review Week 1 CSS 11/17/17

## By Sailor Winkelman

## Description

This webpage displays a clothing item for sale in an online store. It includes a summary of the item's features, a large image of the item, thumbnail images of different views of the item, a table to help the user determine their size, and a caption.

## Setup

Clone this repository.

Open the index.html in a web browser.

## Technologies Used:

HTML
CSS

## Elements Used:
 <table>
   <thead>
     <tr>
       <th>Term</th>
       <th>Description</th>
       <th>Implementation</th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td>box-sizing:border-box</td>
       <td>This property tells the browser to include the size of borders on elements in the total width and height of each element it is applied to.</td>
       <td>I gave a border-box box-sizing property to container elements in my stylesheet, in order to make sizing the containers easier to calculate (because I did not have to take border sizes into account.) </td>
     </tr>
     <tr>
       <td>Float</td>
       <td>Float takes an element out of the normal flow and aligns it with an area of the page (Ex. float:left; aligns the element with the left side of the page.)</td>
       <td>I used floats to make a left and right content area of the page, and to align the images within the content area. I also used floats to position elements in the navigation.</td>
     </tr>
     <tr>
       <td>display:block;</td>
       <td>HTML elements have default display properties that place them either on the same line or a new line as other elements. Display:block makes an element occupy it's own line like a block level element.</td>
       <td>I used display:block on <a> elements to make them block-level instead of on the same line. These are the links in the right column.</td>
     </tr>
     <tr>
       <td>display:inline;</td>
       <td>HTML elements have default display properties that place them either on the same line or a new line as other elements. Display:inline makes an element sit on the same line as other elements instead of being block-level</td>
       <td>I used display:inline to make the unordered list of site links in the left column display in a line.</td>
     </tr>
     <tr>
       <td>Centered Content</td>
       <td>There are a few different ways to use CSS to center content on the page. </td>
       <td>One way this project centers content is by using the display:table-cell and vertical-align:middle properties on the div with the class "center" to create an equal space above and below the content in the right column.</td>
     </tr>
     <tr>
       <td>Psuedo-Element</td>
       <td>Psuedo-Elements allow you to place content before and after elements in your HTML using CSS. </td>
       <td>In this project, I used li:after to add space between in line list items.</td>
     </tr>
     <tr>
       <td>Psuedo-class</td>
       <td>Psuedo-classes target elements in a specified state, such as when the mouse cursor is hovering over a place on the page</td>
       <td>I applied a hover psuedo-class to the div containting the main image on my product page, and set it to display the image at 200% mouse cursor hovers over the image.</td>
     </tr>
     <tr>
       <td>Clear-fix</td>
       <td>Clear fixes allow you to clear the effects of nearby floated elements from an element. </td>
       <td>I used a clear:both to allow the footer to not float left with the two columns abovr it on the page.</td>
     </tr>
     <tr>
       <td>Positional Selector</td>
       <td>Positional selectors allow you to specify an indivual element to select based on the order it appears in relation to it's parent.</td>
       <td>I used the ":first-child" selector to target the first row in the size chart table with my CSS</td>
     </tr>
     <tr>
       <td>Selector Combinator</td>
       <td>Descendant selectors are selector combinators that let you specify descendents of an element. You can also select children (<), adjacent siblings (+), and general siblings (~). </td>
       <td>I use the space combinator in my CSS to target elements inside of divs with ids and classes. </td>
     </tr>
   </tbody>
 </table>
## Legal
Copyright (c) 2017 Sailor Winkelman
