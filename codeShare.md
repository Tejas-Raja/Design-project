# Design-project

// code to add objects onto the screen
addObject(new 'objectName'(), 300,200);
// 300 is the x coordinate and 200 is the y coordinate

//code to change screen when clicked on an object
if(Greenfoot.mouseClicked(this))
  {
    Greenfoot.setWorld(new 'theScreenName'());
  }
  
  //change screen when a key on the board is clicked
if(Greenfoot.isKeyDown("enter")) //this line indicates that when the 'enter' key is pressed, it goes to the below code
  {
    Greenfoot.setWorld(new 'theScreenName'());
  }
