# Stacks In C

1. A stack is a linear data structure that consists of a group of identical elements.

2. A stack only has one endpoint where components can be added or removed.

3. Stacks work on the principle of "Last In, First Out" (LIFO) .

 The first thing to be "popped" off of the stack when an element is "pushed" onto it is that element. You must pop every preceding item in order to get to the oldest entered item.



![stack](https://user-images.githubusercontent.com/124857399/234071180-48a84366-70a9-44a0-9d4e-f5a66478f587.png)



## Operations Performed on Stacks

#### The following are the basic operations served by stacks.

push: Adds an element to the top of the stack.

pop: Removes the topmost element from the stack.

isEmpty: Checks whether the stack is empty.

isFull: Checks whether the stack is full.

top: Displays the topmost element of the stack.


## Underlying Mechanics of Stacks

Initially, a pointer (top) is set to keep the track of the topmost item in the stack. The stack is initialized to -1.

Then, a check is performed to determine if the stack is empty by comparing top to -1.

As elements are added to the stack, the position of top is updated.

As soon as elements are popped or deleted, the topmost element is removed and the position of top is updated.

#### NOTE:- Only a single element can be accessed at a time in stacks.

