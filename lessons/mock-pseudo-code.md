# Mock Lesson Pseudo Code
This page documents a Mock Lesson for the 

## Target Pseudo Code

```
When someone clicks on the green flag (Event)

// First we have to figure out where to start on the screen
Set my initial x,y position on the screen (Motion)

Set speed to its initial value (Variables)

Loop (Control)
  point towards mouse pointer (Motion)
  move some number of steps (Motion)
End Loop
```

## Questions to ask in order to get there: 

* What's the first thing we have to do?
* Do we have to trigger on anything?
* What gets this thing started?
  
* Okay, after that, where do we start the sprite on the map?
* What is going to be sprite's initial position?
* Should we set the initial position to something known?  Where?
  
* Okay, we've triggered the program and determined where on the map we need to start, what's next?
* We need to get the sprite to chase the pointer because that's what this program does. 
* After we tell the sprite what to chase, then what?  Should we move it?  How far? 
   
* Then what?  Are we done?  We need to do this again?  How many times? 
* Hmmm, sounds a little bit like we could use a loop. 
* Should we put these steps in a loop?  What kind of loop?
  
* Okay, so inside a loop, point the sprite at the mouse and take some steps over and over and over 
* Sounds good.  Let's write it up. 
