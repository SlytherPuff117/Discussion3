Arrays and ArrayLists can both be used to store lists of values of the same data type. 
Programs can then iterate through the arrays or ArrayLists using loops to access, add, or change elements within them. 
Some key differences between arrays and ArrayLists include their sizes, how they are declared and initialized, and how elements are accessed. 
Sizes:
Arrays have a set size that the programmer defines at initialization. 
This size cannot be changed afterwards and trying to access an elements at an index not within the size can result in an error. 
There is a method that can access the size of an array that is called through the .length method (Do not confuse this with the .length() method used for strings). 
By contrast, ArrayLists do not have a set size and the size can change as the program goes on. 
ArrayLists, as will be discussed later, have methods to add or remove elements from the list. 
To access the size of an ArrayList you will want to use the .size() method. 
Declaration and Initialization:
Array declaration, as shown in the program, consists of the data type(int, double, String) followed by a set of brackets (Use two sets of brackets to indicate a two-dimensional array). 
After the brackets you give your array a name, using camelHump notation. 
Now that the array is declared, it can be initialized anywhere within that class. 
Initialization uses the array name, the assignment operator(=), the keyword ‘new’, the data type, a set of brackets and the size which is inside the brackets. 
You can do initialization and declaration in one line. 
During initialization, you can also just fill the array, and the compiler will count the elements for you. 
To do this, type th array name and assignment operator followed by curly braces. 
Inside the curly braces, list out the elements with commas separating elements. 
Before you can declare an ArrayList you must import the ArrayList class from java.util. 
After that, ArrayList declaration looks looks as follows: ArrayList<dataType> name = new ArrayList<dataType>().
Accessing elements:
To access elements within an array, you just have to provide the array name, followed by brackets. 
Within the brackets you will put the index of the element you wish to access. 
At this point, you can change the value at that index. 
You may also copy and store that value into a different variable to keep that array unchanged. 
There are a number of different methods for ArrayLists that allow programs to access and change the elements within them. 
These methods include .add, .remove, .get, and .set. 
The add and remove methods have already been explained, but they will add or remove values at a specified index, as long as that index exists within the size of the ArrayList. 
The get method will get a copy of the value at that index and allow it to be stored in a different variable. 
The set method will change the value of an element at the specified index. 
