1. Iterate over the linked list. For each node we visit, add the node value into a set if the value is not in the set already. Otherwise if value already exists, then set the prevNode.next to the currNode.next and continue iterating. 

2. Iterate over the linked list once to find the length of the linked list. Find the index of the target node by doing length - n + 1 (to account for the last node). Iterate over the linked list again keeping and return the node at the correct index.

3. ???

4. Iterate over the linked list. If the currNode.val is less than x, set it to the new Linked List we create. Iterate over the linked list again. If t he currNode.val is greater than or equal to x, add it to the new Linked List. Return the head of the new linked list. 

Another solution would be to iterate over the linked list once. Attach the values less than x to the new Linked List and attach the values that are not to a node chain. After the iteration, attach the node chain to the new linked list.

5. Create two variables to hold the numbers. Iterate over both linked lists and build the number as a string. Parse int both values and add them up. Turn it back into a string and create a linked List from the first digit. 

If the digits are stored in forward order, do the same thing but in reverse

6. Iterate over the linked list and add each value into an array. Reverse the array and compare each value, if a value is different, then return false. Otherwise return true.

Another solution would be to reverse the linked list by keeping track of the previous node and for each node changing the .next node to be equal to the previous node. Take the last node and set it as the head. Iterate over both linked lists comparing values and return true or false depending on that. 

7. Do an iteration inside of an iteration comparing the nodes directly. If two nodes are at the same reference, then return true. Otherwise return false.

8. Use the runner approach with two pointers. Have one pointer going twice as fast. If the two pointers meet, that means there is a cycle. 

Keep track of the nodes visited using a set. If the same node is visited, return that same node.

