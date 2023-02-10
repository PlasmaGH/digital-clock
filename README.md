# digital-clock
Compiles parts to create a digital clock interface.

---

## Useage:

```

[1] : number "The number to display"
[2] : table "The clock models"
[3] : boolean "Overflow clock" - If this is enabled, if there are more numbers than clocks all clocks will go to "9".

format(52, {script.Parent.Clock_1, script.Parent.Clock_2,}, true);
-- ^ The expected result is for the clock to display 52

```
> Created for rifle digital ammo counter

https://user-images.githubusercontent.com/77991203/217848828-c9dc222f-5bf2-46dd-a95c-160e052116bb.mp4

