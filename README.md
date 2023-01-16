# The easiest way to make a triggerbot
This project was made for educational purposes.
I do not encourage the usage of third party software.

---

## Table of contents
- [Introduction](#intro)
- [Requirements](#req)
- [Logic](#logic)
- [Code example](#code)

---

## <a id="intro"></a>What is a triggerbot?
A triggerbot will help you in-game by shooting automatically once your crosshair is on an enemy entity.

---

## <a id="req"></a>Things you will need
- A way to emulate mouse clicks (can be a software but also hardware)
- A way to read colors from screen pretty fast (We call this the `screenreader` for now)
- Code

---

## <a id="logic"></a>How it works
- Screenreader checks the middle of your screen for the enemy outline color of your choice (purple recommended); once the color is in the middle of the screen make your code simulate a mouse click.

---

## <a id="code"></a>Code example
(Not actual code)

Code should be a loop until process is being killed; Purple must be defined with a color checker because the rgb value varies depending on distance to object 

**General example:**
```js
mouse = Mouse //define mouse here 
purple = //RGB VALUE HERE //define color here

function main() //function to check for enemies and shoot 
{
  screen = //define screen (can be a screenshot or whatever)
  if(pixel(screen.width/2 && screen.height/2) === purple) //check if the middle of your screen has color
  {
    mouse.click(); //simulate mouse click / shoot
  }
}

if(mouse.rightclick.isPressed() == true) //if RC is clicked 
{
  main(); //execute function 
}
```
^^^
Fictive code

Make sure to always write your own code and not to copy from the internet in order to ensure complete functionality.

---

## Liked this project?
Feel free to leave a star 🌟
