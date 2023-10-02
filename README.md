# Machine Learning Code Sandbox
Below are a selection of personal coding projects undertaken for the purpose of skill enhancement and practice in the domains of HTML, CSS, and JavaScript. Some of them were performed as capstone projects for the following courses: 
- <a href="https://www.coursera.org/learn/linear-algebra-machine-learning">Mathematics for Machine Learning: Linear Algebra</a> from Imperial College London on Coursera

🌱 Fellow learners are welcome to use these projects as a base for their own capstone projects. 

👋🏻 Feel free to consult <a href="https://www.freecodecamp.org/olgaalexee">my freeCodeCamp profile</a> and <a href="https://www.linkedin.com/in/bookwormolga">LinkedIn page</a> to see my credentials and connect. 

## 1 - Identifying Special Matrices

### Project description
A Python coding exercise from the <a href="https://www.coursera.org/learn/linear-algebra-machine-learning">Mathematics for Machine Learning: Linear Algebra</a> course. In it, the learner is supposed to create a function that will test if a 4×4 matrix is singular, i.e. to determine if an inverse exists, before calculating it.The learner shall use the method of converting a matrix to echelon form, and testing if this fails by leaving zeros that can’t be removed on the leading diagonal.

<b>Relevant mathematics topics:</b> <a href="https://en.wikipedia.org/wiki/Linear_algebra#:~:text=Linear%20algebra%20is%20the%20branch,this%20case%2C%20a%20unique%20point">linear algebra</a>, <a href="https://en.wikipedia.org/wiki/Matrix_(mathematics)">matrices</a>, <a href="https://en.wikipedia.org/wiki/Row_echelon_form">echelon form</a>

### Technologies
- <a href="https://www.python.org/">Python</a>
- <a href="https://numpy.org/">numpy</a>
- <a href="https://jupyter.org/">Jupyter Notebook</a>

## 2 - Gram-Schmidt process

### Project description
A Python coding exercise from the <a href="https://www.coursera.org/learn/linear-algebra-machine-learning">Mathematics for Machine Learning: Linear Algebra</a> course. In it, the learner is supposed to create a function to perform the Gram-Schmidt procedure, which takes a list of vectors and forms an orthonormal basis from this set. As a corollary, the procedure allows us to determine the dimension of the space spanned by the basis vectors, which is equal to or less than the space which the vectors sit. The learner should start by completing a function for 4 basis vectors, before generalising to when an arbitrary number of vectors are given.

<b>Relevant mathematics topics:</b> <a href="https://en.wikipedia.org/wiki/Linear_algebra#:~:text=Linear%20algebra%20is%20the%20branch,this%20case%2C%20a%20unique%20point">linear algebra</a>, <a href="https://en.wikipedia.org/wiki/Matrix_(mathematics)">matrices</a>, <a href="https://en.wikipedia.org/wiki/Orthonormal_basis">orthonormal basis</a>, <a href="https://en.wikipedia.org/wiki/Gram%E2%80%93Schmidt_process">Gram-Schmidt process</a>

### Technologies
- <a href="https://www.python.org/">Python</a>
- <a href="https://numpy.org/">numpy</a>
- <a href="https://jupyter.org/">Jupyter Notebook</a>

## 3 - Reflecting Bear

### Project description
A Python coding exercise from the <a href="https://www.coursera.org/learn/linear-algebra-machine-learning">Mathematics for Machine Learning: Linear Algebra</a> course. In it, the learner is supposed to write a Python function that will produce a transformation matrix for reflecting vectors in an arbitrarily angled mirror. Building on the exercise with Gram-Schmidt procedure, where the learner wrote a code to construct an orthonormal basis that spans a set of input vectors, here the learner will take a matrix which takes simple form in that basis, and transform it into our starting basis.

<b>Relevant mathematics topics:</b> <a href="https://en.wikipedia.org/wiki/Linear_algebra#:~:text=Linear%20algebra%20is%20the%20branch,this%20case%2C%20a%20unique%20point">linear algebra</a>, <a href="https://en.wikipedia.org/wiki/Matrix_(mathematics)">matrices</a>, <a href="https://en.wikipedia.org/wiki/Rotations_and_reflections_in_two_dimensions">reflexion and rotation</a> 

### Technologies
- <a href="https://www.python.org/">Python</a>
- <a href="https://numpy.org/">numpy</a>
- <a href="https://jupyter.org/">Jupyter Notebook</a>

## 4 - Page Rank

### Project description
A Python coding exercise from the <a href="https://www.coursera.org/learn/linear-algebra-machine-learning">Mathematics for Machine Learning: Linear Algebra</a> course. In it, the learner is supposed to build on their knowledge of eigenvectors and  eigenvalues by exploring the PageRank algorithm. The notebook is in two parts, the first is a worksheet to get the learner up to  speed with how the algorithm works - here we will look at a  micro-internet with fewer than 10 websites and see what it does and what  can go wrong. The second is an assessment which will test the learner's application of  eigentheory to this problem by writing code and calculating the page  rank of a large network representing a sub-section of the internet.

<b>Relevant mathematics topics:</b> <a href="https://en.wikipedia.org/wiki/Linear_algebra#:~:text=Linear%20algebra%20is%20the%20branch,this%20case%2C%20a%20unique%20point">linear algebra</a>, <a href="https://en.wikipedia.org/wiki/Matrix_(mathematics)">matrices</a>, <a href="https://en.wikipedia.org/wiki/Characteristic_polynomial">characteristic polynomial</a>, <a href="https://en.wikipedia.org/wiki/Eigenvalues_and_eigenvectors">eigenvalues and eigenvectors</a>

### Technologies
- <a href="https://www.python.org/">Python</a>
- <a href="https://numpy.org/">numpy</a>
- <a href="https://jupyter.org/">Jupyter Notebook</a>

## MIT License

Copyright (c) 2023 Olga Alexeeva

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.