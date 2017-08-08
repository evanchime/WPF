Implementation of styles. Styles is applied when event is triggered. In this 
example, we have a green square. It has a trigger that fires once the mouse is over, 
in which case it fires of several animations, all defined in the EnterActions part of the trigger. 
In there, we animate the thickness of the border from its default 0 to a thickness of 3, and then we animate 
the width and height from 100 to 125. This all happens simultaneously, because they are a part of the same 
StoryBoard, and even at slightly different speeds, since we have full control of how long each animation should run. 