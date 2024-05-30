# zzha0069_9103_Tut8_GroupB

# Functioning prototype 
## Instructions
A random click of the mouse on the screen begins to change. On the first click, the middle circle and arc move to the right, and the large circle and small circle move down. On the second click, the middle circle and arc move down, and the large circle and small circle move to the right. On the third click, the middle circle and arc move to the right, and the large circle and small circle move down. Fourth click, stop moving. When clicking again, repeat the movement of clicking one, two, three, four times.


## Individual approach
I chose to use the mouse for interaction. After the mouse click, the large circle and the small circle, the middle circle and the arc move respectively. Since our graphics are all circles, and layer after layer, my first idea was to make the circle rotate, but I wanted to make some breakthroughs, so that the circle moved parallel, so that the whole animation has a sense of contrast. There's something about breaking the rules and still being alive.

I didn't change the code, I just added interaction via the mouse. This section refers to the tutrial6 tutorial from week7.
1. 'clickcount': Records the number of mouse clicks.
2. 'draw' function: determines the change mode based on the value of 'clickcount'.
3. 'mousePressed' function: Make sure the value of 'clickcount' is 0-3.
4. Function: Three modes of change.
