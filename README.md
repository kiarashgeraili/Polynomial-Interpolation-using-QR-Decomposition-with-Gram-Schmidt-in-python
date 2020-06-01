# Polynomial Interpolation using QR Decomposition with Gram-Schmidt in python
#Kiarash Geraili, Computer Science student at Amirkabir University of Technology

implementing QR Decomposition with Gram-Schmidt in python (without using the built-in function)

This is an academic project for Numerical Analysis Course by Prof. Saeed Kazem in spring 2020. We aimed to implement QR Decomposition (also called the QR factorization) using Gram-Schmidt. 
You can find the approach using this link: https://www.math.ucla.edu/~yanovsky/Teaching/Math151B/handouts/GramSchmidt.pdf even though I have uploaded this pdf file in this repository.

Notice that: If it does not matter for you that how does this approach work, you can use Numpy built-in function (See: https://numpy.org/doc/stable/reference/generated/numpy.linalg.qr.html) to do the same, but in this project, working with matrixes and defining functions in python was important for our supervisor. Therefore, he did not want us to use built-in functions.

We separate our code into two sections: Code section and Evaluating section
in the code section, we implement the approach, and in the evaluating section, we used a built-in function to find out that our code is working properly or not.
