# PA-2
This is a compilation of my work and journal in coding the problems in PA 2

For starters:
In the first cell, it is important to import the numpy library first and foremost to access its features

# 1st Problem
- For the first problem, I followed the instructions and used the provided syntax, which is .std and .mean then I had a gap in knowledge about saving a file, which I discovered was np.save("name file", variable)
- The only challenge in the first problem was knowing how to save a .npy file in the notebook

# 2nd Problem
- In the second problem, which was divisible by three problem, I first tried a syntax, but unfortunately, it was invalid. I then backtracked with the lecture notes, then I discovered the np.arange feature which helped me control the contents of the array. Then, I squared every element in the array.
- After getting the desired content, it was challenging to make it a 10 x 10 matrix. After reviewing the lecture notes again, I thought of using the reshape or resize, but I decided on just using the np.reshape feature since this will allow me to change the shape of the data while retaining its contents.
- After making it a 10 x 10 matrix, I then used a modulo to test for datas in the matrix if it is divisible by 3. Then I saved the data just like what I did in the first problem

## Challenges
- How to save the file to a npy file
- Controlling the array size and shape along with the contents

