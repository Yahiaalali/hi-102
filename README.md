**java**
  
In this example, the user is
shown a message at the top of
the page. The message is held
in an HTML element whose id
attribute has a value of message.
The message is going to be
changed using JavaScript.
+:ii.\11
<!DOCTYPE html>
<html>
<head>
Before the closing </body>
tag, you can see the link to the
JavaScript file. The JavaScript
file starts with a variable used
to hold a new message, and is
followed by a function called
updateMessage().
<ti t l e>Basic Function</title>
<l i nk rel ="stylesheet" href="css/ c03.css" />
</head>
<body>
<hl>TravelWorthy</ hl>
<div id="message">We lcome to our site! </ div>
<script src="js/ basic-function .js"></script>
</ body>
</ html>
JAVASCRIPT
You do not need to worry about
how this function works yet - you
will learn about that over the
next few pages. For the moment,
it is just worth noting that inside
the curly braces of the function
are two statements.
c03/basic-function.html
c03/js/basi c-function .js
var msg = 'Sign up to receive our newsletter for 10% off!';
function updateMessage() {
var el = document.getElementByld('message'};
el .textContent = msg;
}
updateMessage(};
l;IJiilil
Sign up to receive our
newsletter for 10% offl
. .JJl.'ft.711111/r
These statements update the
message at the top of the page.
The function acts like a store; it
holds the statements that are
contained in the curly braces
until you are ready to use them.
Those statements are not run
until the function is called. The
function is only called on the last
line of this script. 
