#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) I would say this is algorithm uses O(n) because the runtime largely depends on the value of n


b) This first for loop is O(n), and the while loop goes through half the iterations because 'j' is multiplying by 2 rather than
icrementing by 1. So the while loops is O(logn). Together that makes the algorithm O(nLogn)


c) I would say this algorithm uses O(n) because it loops an amount of times based off of the input value

## Exercise II
Start at the bottom floor and move your way up, dropping an egg at each level.
This way you will only break 1 egg, and that is when you reach floor f. The runtime complexity of this algorithm is O(1),
as the amount of time the loop runs does not depend on the amount of floors given to the building. It only depends on what floor the egg will break,
and it will stop the loop once the egg has broken.

f = 0

for floor in floors:
    if egg_broken:
        return f
    else:
        f += 1
