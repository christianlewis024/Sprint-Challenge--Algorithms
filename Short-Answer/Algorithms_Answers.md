#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n) the run time time will depend on n

b) O(n^2) because of the loop

c) O(n) again because the run time will depend on just n which in this case is bunnies

## Exercise II

-I have building with (n) stories and many eggs.
-If egg is thrown off a floor > or = F, then it will break
-If the egg is thrown off a floor < F, it will not break.
-Need to determine the value of F.
-Could I just drop one egg from the base and make my way up linearly,
dropping one egg at each floor until I reach the floor that it breaks at thus finding the value of f?
-- drop egg
-- does broken = false ?
-- if so, then f has not been found yet. change floors and repeat and add counter
-- if true, stop and return the value of f

I think this run time would be O(n) because it only has to worry about the value of n(which is floors) to determine its run time.
