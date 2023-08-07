# Coffee_House-
## hosted link: https://mayankkatheriya.github.io/Coffee_House-/
![image](https://github.com/Mayankkatheriya/Coffee_House-/assets/128832286/9c7dcc2f-feb6-4084-9ea6-2df231ec0e72)

first we set background color of our web page\
* {: This targets all elements on the page.

margin: 0;: It sets the margin of all elements to 0, effectively removing any default spacing between elements.\
padding: 0;: It sets the padding of all elements to 0, removing any default padding applied by the browser.\
box-sizing: border-box;: It sets the box-sizing property to border-box for all elements. This ensures that the total width and height of an element include padding and border, but not margin.\

body {: This targets the body element of the page.

background-color: rgb(237,212,212);: It sets the background color of the body element to a light pinkish color, specified by the RGB value rgb(237,212,212).\
![image](https://github.com/Mayankkatheriya/Coffee_House-/assets/128832286/84cf809a-f5de-402b-86a6-4008f278884a)

<br>

![image](https://github.com/Mayankkatheriya/Coffee_House-/assets/128832286/75dd211b-72cd-438c-8eab-8261bf011b43)
![image](https://github.com/Mayankkatheriya/Coffee_House-/assets/128832286/c9b19b32-b5fa-4df5-b0ae-9dea6a2df92a)

.nav {: This targets elements with the class "nav."

width: 100%;: The element's width is set to 100% of its parent's width.\
height: 300px;: The element's height is set to 300 pixels.\
position: relative;: The element is positioned relative to its normal position.\
background-image: url(https://i.pinimg.com/736x/e1/c2/3a/e1c23ac34847740f672717c89a62ae37.jpg);: The element's background image is set to the provided URL.\
background-repeat: no-repeat;: The background image will not be repeated.\
background-size: cover;: The background image will be scaled to cover the entire element.\
background-position: center;: The background image will be centered within the element.\
box-shadow: 0 0 10px 0 black;: The element will have a black box shadow with a blur radius of 10px.\

.search {: This targets elements with the class "search."

position: sticky;: The element is positioned relative to its nearest scrolling ancestor.\
left: 15%;: The element is positioned 15% from the left edge of its containing block.\
top: 60px;: The element is positioned 60 pixels down from the top edge of its containing block.\
padding: 10px;: The element has 10 pixels of padding on all sides.\
background-color: rgb(99,18,18);: The background color of the element is set to a dark red.\
color: white;: The text inside the element will be displayed in white.\
width: 70%;: The element's width is set to 70% of its containing block's width.\
height: 20%;: The element's height is set to 20% of its containing block's height.\
border-radius: 10px;: The element's corners will have a border radius of 10 pixels.\
border: none;: The element will have no border.\

.search:focus {: This targets the .search element when it is in focus (when clicked or selected).

background-color: rgba(99,18,18,0.9);: The background color of the element is set to a slightly transparent dark red when in focus.\
outline: none;: The default focus outline is removed.\
![image](https://github.com/Mayankkatheriya/Coffee_House-/assets/128832286/cc25e3cc-8277-4703-a308-490a6e09f29b)
<br>
outr nav bar is ready\
now come to the next step\

<br>

![image](https://github.com/Mayankkatheriya/Coffee_House-/assets/128832286/e409a6c5-f1b4-4f6a-bb40-4ab9b1945d1f)
![image](https://github.com/Mayankkatheriya/Coffee_House-/assets/128832286/7f1a2a82-dae9-4bc3-b511-09cf8a215b0d)

.main: Represents a container with flex layout, padding, and space-evenly justified content.

padding: Sets 40 pixels top and bottom padding, 0 pixels left and right.\
display: Specifies a flex container.\
justify-content: Positions flex items with space evenly between them.\

.coffee: Represents a flex container with flex-direction column and centered items.

display: Specifies a flex container.\
flex-direction: Sets the flex items' stacking direction to column.\
align-items: Aligns flex items along the center of the container.\
color: Sets the font color to a semi-transparent black.\
.image: Represents an image element with predefined height and width.

height: Sets the image height to 150 pixels\
width: Sets the image width to 150 pixels\

img: Represents all image elements.

width: Sets the image width to 100% of its container.\
height: Sets the image height to 100% of its container.\
border-radius: Applies a circular border radius to create a circular image.\
box-shadow: Adds a black box shadow of 8px offset and 8px blur around the image.\
hover: Applies the following styles on hover:\
Increases the box shadow to 18px offset and 18px blur.\
Increases the image height and width to 152 pixels.\

h4: Represents heading level 4 elements.

margin-top: Adds 15 pixels of top margin to the heading.
![image](https://github.com/Mayankkatheriya/Coffee_House-/assets/128832286/c307ce0f-2f47-4fa5-8843-620dc1624336)

<br>


![image](https://github.com/Mayankkatheriya/Coffee_House-/assets/128832286/07074c78-31f3-4c42-8736-9f154477ec3d)
![image](https://github.com/Mayankkatheriya/Coffee_House-/assets/128832286/6b81cede-f0c3-4e31-9883-5f17c1857066)

.details: Represents a container with flex layout, centered content, and padding.

width: Sets the container width to 100% of its parent.\
display: Specifies a flex container.\
flex-direction: Sets the flex items' stacking direction to column.\
align-items: Aligns flex items along the center of the container.\
padding: Adds 5 pixels top and bottom padding, 0 pixels left and right.\

.del: Represents a container with a background color, padding, border radius, and box shadow.

background-color: Sets the background color to a shade of reddish-brown.\
width: Sets the container width to 90% of its parent.\
padding: Adds 30 pixels of padding inside the container.\
border-radius: Applies a 10-pixel border radius to create rounded corners.\
box-shadow: Adds a brown box shadow to the container.\

h2: Represents heading level 2 elements.

color: Sets the text color to a shade of reddish-brown.\

.para: Represents a paragraph text element.

color: Sets the text color to a shade of reddish-brown.\
line-height: Sets the line height between lines of text to 20 pixels.\

ul li: Represents list items within an unordered or ordered list.

list-style-type: Sets the list item marker to a decimal number.\
line-height: Sets the line height between list item markers to 30 pixels.\
color: Sets the text color of list items to a shade of reddish-brown.\
padding-inline-start: Adds 5 pixels of left padding to the list items.\

.para_last: Represents the last paragraph text element in the container.

color: Sets the text color to a shade of reddish-brown.\
line-height: Sets the line height between lines of text to 20 pixels.\
margin-top: Adds 20 pixels of top margin to the paragraph.\
![image](https://github.com/Mayankkatheriya/Coffee_House-/assets/128832286/39f7cba9-f785-4e7a-90ff-3abe5e88d60d)

<br>

![image](https://github.com/Mayankkatheriya/Coffee_House-/assets/128832286/2883f240-70b7-4819-95af-c1b2af9369ec)
![image](https://github.com/Mayankkatheriya/Coffee_House-/assets/128832286/7e4eca8a-cf4c-47a4-baae-19c27959e2ce)

.down: Represents elements with this class.

margin-top: Adds 30 pixels of top margin to the elements.\
margin-bottom: Adds 45 pixels of bottom margin to the elements.\
![image](https://github.com/Mayankkatheriya/Coffee_House-/assets/128832286/94b7213e-810e-4302-8e8a-39596c0ed662)

## Your web page is ready;
# Thankyou
