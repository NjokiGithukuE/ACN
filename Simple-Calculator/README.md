1. Create an add function that can add two integers
Create a function called add that works like this:

add(1,2)
// should return 3
add(-1,-1)
// should return -2

2. Modify the add function so that it can add multiple integers.
The add function should now behave like this:

add(1,2,3,4,5)
// should return 15
add(1,2)
// should still return 3
add(-1,-1)
// should still return -2
Please note that your function should NOT expect an array or list of numbers, for example:

add([1,2,3,4])
This is NOT what we are looking for. If you have square brackets inside your round brackets, you are doing it wrong. The same will apply to the multiply function you will build in the next section.

3. Create a multiply function that can multiply two integers
Create a function called multiply that works like this:

multiply(1,3)
// should return 3
multiply(-1,3)
// should return -3

4. Modify the multiply function so that it can multiply multiple integers.
The multiply function should now behave like this:

mutilply(1,2,3,4,5)
// should return 120
multiply(1,3)
// should still return 3
multiply(-1,3)
// should still return -3


Use Jasmine to test your code.