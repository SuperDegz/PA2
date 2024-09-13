## PA2

# Normalization Problem 

### Problem Given: 
Normalization is one of the most basic preprocessing techniques in data analytics. This involves centering and scaling process. Centering means subtracting the data from the mean and scaling means dividing with its standard deviation. Mathematically, normalization can be expressed as:  𝑍 = 𝑋 − 𝑥̅ / 𝜎

### Code Description: 
This Python script creates a 5x5 array of random integers ranging from 0 to 1, computes the mean and standard deviation, then normalizes the array using standard score normalization. The normalized array is then stored as a.npy file for further usage.

### Problems Encountered:
The file X_normalized.npy was not saved in the intended location. The issue was created by running the script from a different directory than expected.

### Solution:
I fixed issue by confirming that the working directory was correctly defined.



# Divisible by 3 Problem:

### Problem Given
Create the following 10 x 10 ndarray. Which are the squares of the first 100 positive integers.
From this ndarray, determine all the elements that are divisible by 3. Save the result as div_by_3.npy

### Code Description: 
This code creates an array, A, of squares of numbers from 1 to 100 using the np.arange() function and squares each element. The array is then reshaped into a 10x10 matrix using the .reshape() method. From this matrix, elements divisible by 3 are selected using the condition A % 3 == 0 and stored in the variable div_by_3. The selected elements are saved to a .npy file named 'div_by_3.npy' for future use, using the np.save() function. Additionally, the code defines a function display_div_by_3() that formats and prints the elements of the original array A, with each element displayed in a 6-character wide column. Finally, the code prints the array of squares divisible by 3, providing a clear output of the selected elements.

### Problems Encountered:
When displaying the array, I initially used print(A) but found it difficult to visually parse the output.

### Solution:
To improve readability, I wrote the function display_div_by_3, which aligns each element to 6-character-wide columns.
