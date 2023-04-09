# Arrays

An array in C is a collection of elements of the same data type that are stored in a contiguous memory location. To declare an array, we use the syntax type arrayName[arraySize], where type is the data type of the elements in the array, arrayName is the name of the array, and arraySize is the number of elements the array can hold.

To initialize an array, we use an initializer list enclosed in braces { }. For example, int numbers[5] = {1, 2, 3, 4, 5}; initializes an array of integers named numbers with the values 1, 2, 3, 4, and 5.

Array elements can be accessed using an index that starts at 0. For example, int firstNumber = numbers[0]; assigns the first element of the numbers array to a variable named firstNumber. To change an element's value, we can assign a new value to its index. For instance, numbers[1] = 6; changes the second element of the numbers array to 6.
In C, an array is a collection of elements of the same type, stored in contiguous memory locations. An array can be declared using the following syntax:
![image](https://user-images.githubusercontent.com/91204160/230775219-c0415181-e868-47a1-abd7-816b26946e39.png)

Here, type is the data type of the elements that will be stored in the array, arrayName is the name of the array, and arraySize is the number of elements that the array can hold.

For example, to declare an array of integers that can hold 5 elements, we can use the following statement:
