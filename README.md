# lozon_ramona_crushing_bugs_hw_2
 
bug #1

bug #1 is that you can drag and drop more than one puzzle piece into a zone

in order to prevent this we can add code that checks if a box already has a puzzle piece in it

if the area is already occupied by a puzzle piece, we can add some code that prevents a new piece from being dropped

we can start with an "if" statement, to check whether a condition is true or false 

after that we can include a this.querySelector, since it is within the bracket of a line of code above it is referencing the Handledrop event

we can spedify what css element the querySelector is looking for, if we include the 'img' tag then it will see if the zone contains any images.

so if the zone does not contain any images it will not allow any puzzle pieces to be dropped via the appendchild function below

like this

if(this.querySelector('img))

by adding this line, java will check if there is any images in the zone. if there are NO images in the zone it will not allow you to drop any images

but we want this line of code to do the opposite, to check if there is an image and if there IS, to prevent the appendChild(draggedpiece) from functioning, and prevent further images from being dropped

in order to do this we can add an exclaimation point to our like of code like so:

if(!this.querySelector('img))

now this line of code will make the java check the zone to see if there IS an image, that is true, if there is an image, it will prevent any more images from being dropped.

bug fix #2

there is a second bug within the java script. 

on the site there is a reset button that should remove all pieces from the puzzle board when pressed. 

it does not work. 

there are also 4 different puzzles that can be made on this puzzle site. 

when switching between puzzles, the puzzle pieces should also reset.

in order to fix this we can create a new function

we can call this function reserPuzzle to make it simple