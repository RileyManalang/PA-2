# PA-2
This is a compilation of my work and journal in coding the problems in PA 2

For starters:
In the first cell, it is essential to import the numpy library first and foremost to access its features

# 1st Problem: Normalization Problem

> The problem is basically normalizing data (random numbers), which involves centering and scaling processes. We were also instructed to use .mean() and .std() calls. Other conditions were make a 5x5 ndarray with randomized data numbers then save it as an .npy file. 
```
import numpy as np
 X = np.random.random((5,5))
 m = np.mean(X)
 s= np.std(X)
 Z = (X - m) / s
 print (Z)
 np.save('X_normalized.npy',Z) #save the file to a numpy file
```
- For the first problem, I followed the instructions and used the provided syntax, which is .std and .mean then I had a gap in knowledge about saving a file, which I discovered was np.save("name file", variable)
- The only challenge in the first problem was knowing how to save a .npy file in the notebook

# 2nd Problem: Divisible by 3 Problem

```
import numpy as np #access numpy features
z = np.arange (1,101) #utilize  a numpy function that will control the content of the array
squaredNumbers = z**2 #square the contents of the array
squaredNumbers.reshape(10,10) # change the shape of the array
b=squaredNumbers%3 #checks each number in the array if its divisible by 3
print (b)

np.save('div_by_3.npy', b)#save the file to a numpy file


```
> The task is to create a 10 x 10 ndarray which are the squares of the first 100 positive integers then determine which are divisible by 3. Also save it to an .npy file.
- In the second problem, which was divisible by three problem, I first tried a syntax, but unfortunately, it was invalid. I then backtracked with the lecture notes, then I discovered the np.arange feature which helped me control the contents of the array. Then, I squared every element in the array.
- After getting the desired content, it was challenging to make it a 10 x 10 matrix. After reviewing the lecture notes again, I thought of using the reshape or resize, but I decided on just using the np.reshape feature since this will allow me to change the shape of the data while retaining its contents.
- After making it a 10 x 10 matrix, I then used a modulo to test for datas in the matrix if it is divisible by 3. Then I saved the data just like what I did in the first problem

## Challenges
- How to save the file to a npy file
- Controlling the array size and shape along with the contents


