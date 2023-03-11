# dsa-js
Data Structure and Algorithm problems in JavaScript

# how to run a program in node.js

Install Node.js: If you haven't already, download and install Node.js from the official website (https://nodejs.org/). Follow the installation instructions for your operating system.

Create a new file: Open a text editor and create a new file with a .js extension. For example, you can create a file named binarySearch.js.

Write the code: Copy and paste the code for the binary search algorithm into the file.

Save the file: Save the file to a location on your computer.

Open a command prompt or terminal: Open a command prompt or terminal window on your computer.

Navigate to the directory: Use the cd command to navigate to the directory where you saved the JavaScript file. For example, if you saved the file to the Desktop folder, you can navigate to it by typing cd Desktop in the command prompt or terminal window.

Run the program: Type node filename.js in the command prompt or terminal window, where filename.js is the name of the JavaScript file you created in step 2. In this case, you would type node binarySearch.js.

View the output: If the program runs successfully, you should see the output in the command prompt or terminal window. In the case of the binary search algorithm, the output would be the index of the target value in the array, or -1 if the target value is not found.

# 1 : Binary Search

This implementation takes an array (arr) and a target value (target) as inputs and returns the index of the target value in the array, or -1 if the target value is not found.

The algorithm works by dividing the search space in half at each iteration, eliminating the half of the search space that cannot contain the target value. The left and right indices represent the current search space, and the mid index is the midpoint of the search space. The algorithm checks if the target value is equal to the element at the midpoint, and if not, narrows the search space by updating the left and right indices accordingly.

Note that this implementation assumes that the input array is sorted in ascending order.