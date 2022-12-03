# Welcome to My Bouncing Box
***

## Task
i am to replicate the famous window saver bouncing box, a html code is already provided i am to complete it with a javascript code.
the box is to move diagonally and each time it reaches a border it is to change direction of the border it touched.

## Description
i began by declaring variables x andy and seting them both equal to 0 which defines the location. I declared two other variable vertDir and horDir and set the vertDir equal to -1 and the horDirv equal to 1 t odefine the direction the box will move.
i declared a function called moveBox, inside it code block i declareda variable box which is equal to document.getElementById('my_bouncing_box') to return the element's value,
to define the boundaries i declared two variables, first is rightWall which is equal to window.innerWidth to return the interior width of the window,
the second variable is called bottomWall which is equal to window.innerHeight to return the interior height of the window.
to make the box change direction i used the switch statement, the first one is switch(x)
in it code block, it is case rightWall and case 0, if x = rightWall the horDir should be -1 else it should be 1,
for switch(y) it is case  wall and case 0, if y = bottomWall it should the vertDir should be -1, else it should be 1.
to change x and y, it is x = x + horDir and y = Y + vertDir. 
to change the location of the box, i did box.style.left = x + 'px' and then box.style.top = y + 'px'
to make the box move every miliseconds, i called the setInterval(moveBox, 1).
## Installation
i have not gotten to the part where i need Installation

## Usage
i have not gottento the part where i need usage

### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
