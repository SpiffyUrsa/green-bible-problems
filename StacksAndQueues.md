1. One option would be to have an array of arrays with each inner array acting as its own stack.

2. Create a stack to hold the most recent min values. Keep track of the currMin by comparing the values. If a currMin is removed from the stack, pop the next recent min value from the min stack and set that to currMin.

3. Create an array of arrays. For the last indexed stack, if it exceeds the stack size, push a new array to the larger array. When you remove values from the stack, remove from the last indexed array. If the last indexed array becomes empty, remove it. 

4. 

5. Use sort method

6. LinkedList.remove() => this.head = head.next. LinkedList.add() = this.tail.next = newNode tail = newNode

