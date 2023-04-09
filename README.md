Stack using array
Stack is a linear data structure that follows a particular order in which the operations are performed. LIFO (Last In First Out) implies that the element that is inserted last, comes out first and FILO (First In Last Out) implies that the element that is inserted first, comes out last.

![image](https://user-images.githubusercontent.com/70435939/230756264-8158f93e-3e04-43b9-9978-51739076feaf.png)

Operations on Stack:

push(): When we insert an element in a stack then the operation is known as a push. If the stack is full then the overflow condition occurs.

![image](https://user-images.githubusercontent.com/70435939/230756455-41c3e82d-59e5-4399-98ad-677b9d08241f.png)

pop(): When we delete an element from the stack, the operation is known as a pop. If the stack is empty means that no element exists in the stack, this state is known as an underflow state.

![image](https://user-images.githubusercontent.com/70435939/230756517-f9de02b8-c8ad-4f33-a073-d895d7cb0263.png)

isEmpty(): It determines whether the stack is empty or not.

isFull(): It determines whether the stack is full or not.

Algorithm of the program:
Declare variable top and assign it to -1.

Declare an array of 10 integers.

Create main function and give the user the choice to perform operations as Push, Pop, Display and Exit . Call the functions according to the choice given by user.

Declare and define the function push
PUSH FUNCTION:

Check if top==9, print overflow
else accept data from user,increment top, insert data at top position.
Declare and define the function pop
POP FUNCTION:
Check if top==-1, print underflow
else decrement top.
Declare and define the function display
DISPLAY FUNCTION:
Print the array using for loop.

Applications of Stack:
Balancing of symbols: Stack is used for balancing a symbol.As we know, each program has an opening and closing braces; when the opening braces come, we push the braces in a stack, and when the closing braces appear, we pop the opening braces from the stack. Therefore, the net value comes out to be zero. If any symbol is left in the stack, it means that some syntax occurs in a program.

Expression conversion: Stack can also be used for expression conversion. This is one of the most important applications of stack. The list of the expression conversion is given below: Infix to prefix Infix to postfix Prefix to infix Prefix to postfix Postfix to infix

UNDO/REDO: It can also be used for performing UNDO/REDO operations. For example, we have an editor in which we write 'a', then 'b', and then 'c'; therefore, the text written in an editor is abc. So, there are three states, a, ab, and abc, which are stored in a stack. There would be two stacks in which one stack shows UNDO state, and the other shows REDO state. If we want to perform UNDO operation, and want to achieve 'ab' state, then we implement pop operation.


