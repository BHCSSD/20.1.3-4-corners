# 20.1.2-4-corners
Marked

## todo
1. Change size to 600x400
2. set up an if statement that changes the colour of the background into a unique color depending on which quadrant the mouse is clicked in.
  - You will need to do some problem-solving...
  - remember: and = &&&,  or = ||
  - you will need mouseX and mouseY for this to work. 

```
//20.1.2-4-corners

function setup() {
  createCanvas(400, 400);
  background(220);
}

function draw() {
  // This function is called continuously
}

function mouseClicked() {
  // Check which quadrant the mouse click is in
  if (mouseX < ___ && mouseY < ___) {
    // Top-left quadrant (Change color to red)
    
   }// else if{
     // Bottom-right quadrant (Change color to yellow)
  
  // }
}



// goal is to change color in every corner 


function mouseClicked() {
  // Check which quadrant the mouse click is in
  if (mouseX < 200 && mouseY < 200) {
    // Top-left quadrant (Change color to red)
    background(255, 0, 0);
  } else if (mouseX >= 200 && mouseY < 200) {
    // Top-right quadrant (Change color to green)
    background(0, 255, 0);
  } else if (mouseX < 200 && mouseY >= 200) {
    // Bottom-left quadrant (Change color to blue)
    background(0, 0, 255);
  } else {
    // Bottom-right quadrant (Change color to yellow)
    background(255, 255, 0);
  }
```
