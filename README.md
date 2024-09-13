#PA2

Normalization Problem: 

Problem: Normalization is one of the most basic preprocessing techniques in data analytics. This involves centering and scaling process. Centering means subtracting the data from the mean and scaling means dividing with its standard deviation. Mathematically, normalization can be expressed as:  𝑍 = 𝑋 − 𝑥̅ / 𝜎

The problem that I had in this code is how to input the formula and 






Divisible by 3 Problem:
This code creates an array, A, of squares of numbers from 1 to 100 using the np.arange() function and squares each element. The array is then reshaped into a 10x10 matrix using the .reshape() method. From this matrix, elements divisible by 3 are selected using the condition A % 3 == 0 and stored in the variable div_by_3. The selected elements are saved to a .npy file named 'div_by_3.npy' for future use, using the np.save() function. Additionally, the code defines a function display_div_by_3() that formats and prints the elements of the original array A, with each element displayed in a 6-character wide column. Finally, the code prints the array of squares divisible by 3, providing a clear output of the selected elements.
