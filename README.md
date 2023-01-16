# The easiest way to make a triggerbot
This project was made for educational purposes.
I do not encourage the usage of third party software.

---

---

## <a id="intro"></a>What is a triggerbot?
A triggerbot will help you in-game by shooting automatically once your crosshair is on an enemy entity.

## <a id="requirements"></a>Things you will need
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
