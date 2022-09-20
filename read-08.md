Flexbox is a common way to lay out a webpage that allows for a clean and straightforward layout. Many developers use flexbox, and many CSS frameworks have flexbox as their primary structure. 
Flexbox is a great way to keep a website responsive to all screen sizes without using media queries. 

## Readings: CSS Layout

Reading
[Learn CSS](https://web.dev/learn/css/flexbox/) - Flexbox

Flexbox is designed for one-dimensional content. Explain what this means.  
>When a parent element is set to flex, It can only move in one direction, either column or row. Setting justify content can adjust items along the main axis, but the direction they will move will depend upon the parent element being set to either column or row.



Explain the difference between the main axis and the cross axis.  
> The main axis is vertical if the parent element is positioned in a column. Moving elements in the flexbox will move them up and down with the justify-content property.
> If the parent element is positioned in a row, the main axis is horizontal, so moving child elements with justify-content will move them horizontally.
>the cross axis will run perpendicular to the main axis, allowing for align-items to move items up and down during column direction, and left and right with row direction.


How can using certain properties of flexbox negatively impact accessibility?  
>Some older browsers still do not support flexbox, which could impact the layout of a webpage for users on older systems. 


[CSS Layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - Flexbox

## Read up to “Flex-Flow Shorthand”

What are some advantages of using flexbox over float?  
>float can cause parent elements to collapse, creating visual bugs. Getting elements to line up just right can take a lot of CSS manipulation to accomplish what can be done simply with flexbox.



How does this topic connect with your long-term goals?  
> Understanding the advantages of flexbox and float can impact my design decisions. Especially if I build applications for older machines. Knowing how float works even if float becomes deprecated is vital because many sites will still be using the feature, and my future job could be updating and fixing such sites.


## Things I want to know more about
