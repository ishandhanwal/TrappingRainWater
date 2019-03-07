# TrappingRainWater
Trapping Rain Water : LeetCode solution

heights[] is traversed 0..size-1;
large variable is maintained and is updated as we travel along the array;
element from the heights[] is added to stack if stack is empty or current element < large;

if current > large then stack is emptied and water is calculated
large is made equal to stack.peek(); and compared on the go
after travelling the array if stack is not empty then it is emptied and water is calculated
