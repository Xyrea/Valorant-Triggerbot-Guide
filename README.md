# ValorantTriggerbot
**NOT A TRIGGERBOT - ONLY A GUIDE HOW TO MAKE ONE YOURSELF**

foreword 
I got help from others while doing this and i just want to share it to you

## What you need
- A way to emulate mouse clicks (can be a software but also hardware)
- A way to read colors from screen pretty fast (We call this the `screenreader` for now)
- Code

## How it works
- Screenreader checks the middle of your screen for the enemy outline color of your choice (purple recommended); once the color is in the middle of the screen make your code click.

## Code example
(Not actual code)

Code should be a loop until process is being killed; Purple must be defined with a color checker because the rgb value varies depending on distance to object 

```
if(pixel(screen.width/2 && screen.height/2) === purple)
{
  mouse.click();
}

```
