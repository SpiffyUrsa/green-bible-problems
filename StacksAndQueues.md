1. One option would be to have an array of arrays with each inner array acting as its own stack.

2. Create a stack to hold the most recent min values. Keep track of the currMin by comparing the values. If a currMin is removed from the stack, pop the next recent min value from the min stack and set that to currMin.

3. Create an array of arrays. For the last indexed stack, if it exceeds the stack size, push a new array to the larger array. When you remove values from the stack, remove from the last indexed array. If the last indexed array becomes empty, remove it. 

4. Use two stacks. One stack will hold the oldest values and the other the newest values. Before trying to get the oldest value, we populate the oldest stack by popping values from newest and pushing those values in. 

5. Use sort method. Have two stacks. One that is sorted and one that is not. Also have a temp variable to hold the current value being sorted. Pop off a value from the toSort stack and hold it in temp. Pop off values from the sorted side until the value below is less than the temp. Push those popped values into our unsorted stack. Do this until the unsorted stack is empty

6. LinkedList.remove() => this.head = head.next. LinkedList.add() = this.tail.next = newNode tail = newNode. Have two separate queues for dogs and cats. The queue is ordered by age. When we dequeue any, we can look at both head values and dequeue the value that is older


