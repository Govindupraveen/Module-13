# Exp.No:31  
## IMPLEMENTATION OF STACK

---

### AIM  
To # Exp.No:31  
## IMPLEMENTATION OF STACK USING LIST AND BUILT-IN METHODS IN PYTHON

---

### AIM  
To implement a stack using Python list and perform push, pop, and peek operations using the built-in methods append() and pop().

---

### ALGORITHM

Start

Define a class st for stack operations.

Inside the class, define:

push(self, s): Uses append() to push elements onto the stack.

pop(self): Uses pop() to remove the top element and display it.

peek(self): Displays all elements in the stack.

Initialize an empty list stack.

Get an integer input a from the user to specify the size.

Create a list of even numbers from 1 to a-1 and push them to the stack.

Display the elements using peek().

Pop one element using pop() and show the updated stack using peek().

End

---

### PROGRAM

stack = []

class st:

   def push(self,s):
   
   stack.append(s)
   
   return
   

 def pop(self):
    
   print("Element popped : ",stack.pop())
   
   return
    

 def peek(self):
 
 print("Elements in the stack\n",stack)
    
obj=st()

a=int(input())

for i in range(1,a):

 if i%2==0:
 
   stack.append(i)
        
obj.peek()

obj.pop()

obj.peek()
    
 OUTPUT:

 ![image](https://github.com/user-attachments/assets/b42d1eca-1600-46db-9ee8-4d1ed5c19b71)

RESULT:

Thus the python program was initiated and executed successfully.


write a Python program to implement a stack using a list and its built-in methods (`append()`, `pop()`).

---

### ALGORITHM

1. **Start the program.**
2. **Define a class `st`** with the following methods:
   - `push(self, num)`: Adds the number `num` to the stack.
   - `pop(self)`: Removes and returns the top element from the stack.
3. **Create a stack object `s`** using the class `st`.
4. **Input the stack size**: Take an integer input `size` to define the size of the stack.
5. **Loop through numbers from 1 to size**: Add only the odd numbers to the stack using the `push()` method.
6. **Display the elements** in the stack after the loop completes.
7. **Call `pop()`** to remove the top element from the stack and display the popped element.
8. **Display the stack again** to show the remaining elements.
9. **End the program.**

---

### PROGRAM

```

```
