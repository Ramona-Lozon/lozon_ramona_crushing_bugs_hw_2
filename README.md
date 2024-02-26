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