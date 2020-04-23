# Description
This project implements two different one dimensional optimization methods, Newton's Method and gradient descent. 

# Newtons Method
Newtons method is a root finding algorithm which produces successively better approximations to the roots (or zeroes) of a real-valued function.
In this project I implement Newton's method on the first derivative of the input function to identify potential minuma and maxima of the input function. Newtons method is defined recursivly by the function below.
![Newtons Method](https://static2.mbtfiles.co.uk/media/docs/newdocs/as_and_a_level/maths/core_and_pure_mathematics/908942/html/images/image05.png)

# Gradient Descent
![Gradient Descent Visual](https://miro.medium.com/max/1200/1*iNPHcCxIvcm7RwkRaMTx1g.jpeg)

Newtons method works well when the second derivate is positive, however it sometimes fails to converge when the second derivative is negavie. Gradient descent is a more efficent optimization algoritm that takes steps in the direction of greatest decrease until it converges at a minimum. The step size is based the learning rate which is found using a one dimensional optimization fuction imported from the python package scipy.  

# Testing
I test my code for Newton's method and gradient descent on a few different functions. One of the functions I test on is the Rosenbrock function of which I have included a plot below.
![Plot of Rosenbrock Function](https://upload.wikimedia.org/wikipedia/commons/3/32/Rosenbrock_function.svg)
