# Stack_and_Queue_DSA
Stacks are a type of container adaptors with LIFO(Last In First Out) type of working, where a new element is added at one end (top) and an element is removed from that end only.

## THEORY
a)Stack<br>
Stack uses an encapsulated object of either vector or deque (by default) or list (sequential container class) as its underlying container, providing a specific set of member functions to access its elements. For creating  a stack, we must include the <stack> header file in our code. We then use this syntax to define the std::stack:<br>
Type – is the Type of element contained in the std::stack. It can be any valid C++ type or even a user-defined type.<br>
Container – is the Type of underlying container object.<br>
Member Types:-<br>
value_type- The first template parameter, T. It denotes the element types.<br>
container_type- The second template parameter, Container. It denotes the underlying container type.<br>
size_type- Unsigned integral type.<br>
The functions associated with stack are: <br>
empty() – Returns whether the stack is empty – Time Complexity : O(1) <br>
size() – Returns the size of the stack – Time Complexity : O(1) 
top() – Returns a reference to the top most element of the stack – Time Complexity : O(1) <br>
push(g) – Adds the element ‘g’ at the top of the stack – Time Complexity : O(1) <br>
pop() – Deletes the most recent entered element of the stack – Time Complexity : O(1) <br>
b)Queue<br>
Queues are a type of container adaptors that operate in a first in first out (FIFO) type of arrangement. Elements are inserted at the back (end) and are deleted from the front. Queues use an encapsulated object of deque or list (sequential container class) as its underlying container, providing a specific set of member functions to access its elements.<br>
queue::empty()	Returns whether the queue is empty. It return true if the queue is empty otherwise returns false.<br>
queue::swap()	Exchange the contents of two queues but the queues must be of the same data type, although sizes may differ.<br>
queue::emplace()	Insert a new element into the queue container, the new element is added to the end of the queue.<br>
queue::front()	Returns a reference to the first element of the queue.<br>
queue::back()	Returns a reference to the last element of the queue.<br>
queue::push(g) 	Adds the element ‘g’ at the end of the queue.<br>
queue::pop() 	Deletes the first element of the queue.<br>

## ALGORITHM
