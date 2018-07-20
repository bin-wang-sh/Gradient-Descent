## gradient Code for Udacity Data Scientist exercise
From before we saw that one weight update can be calculated as:
Δwi=ηδxi
with the error term  δ as
δ=(y− y^)f′(h)=(y−y^)f′(∑wixi)
Remember, in the above equation  (y−y^) is the output error, and  f′(h) refers to the derivative of the activation function, f(h). We'll call that derivative the output gradient.
Now I'll write this out in code for the case of only one output unit. We'll also be using the sigmoid as the activation function f(h).
