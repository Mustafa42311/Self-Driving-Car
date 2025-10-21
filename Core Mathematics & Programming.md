# Linear Algebra
## 1-The Geometry of Lineear Equations

First lets start with a simple introduction to linear algebra.
The fundamental problem of linear algebra,is to solve a system of linear equations. :arrow_right: n linear equations, n unkowns.

The methods I am going to tackle here are:
- Row Picture
- Column Picture
- Matrix form

The best way to explain any mathematics concept is with an example so lets explain withexampkes.

### Row Picture
 ![WhatsApp Image 2025-10-21 at 6 43 43 PM](https://github.com/user-attachments/assets/b585f042-663f-4c00-8c8e-2863ad7670bc)
Here we have an example, we have two equations with two unkowns. First, lets write in matrix form The matrix with the coefficent of our unkowns will be called A from now on and the matrix of our unkowns will be called X and the RHS of our equation will be b.
The row picture is very simple you draw each equation and because it is in a 2d form both lines will intersect on a certain point in the case ithe intersection point is x=1 & y=2.

### Coloumn Picture


![WhatsApp Image 2025-10-21 at 6 52 04 PM](https://github.com/user-attachments/assets/d691a0af-4982-4e92-9370-08a8d1c8900f)
In the coloumn picture we multiply each coloumn from the A matrix with its unkown then we add them together. Then we draw both coloumn graphically and we ask ourselves what isthe combination, or how many times will I have to draw Col. 1 and Col. 2 to reach to matrix b. 

---------------------


Everything is good and all when there is only two unkowns but what if there is three unkowns then drawing wll not make it clear to see the intersection point, cause the intersect in a plane and the more unkowns you add the more difficult it gets to detect the solution.

![WhatsApp Image 2025-10-21 at 7 02 44 PM](https://github.com/user-attachments/assets/64c25c63-f714-417a-b159-eebffd4136a9)

Let me ask an important question.
Can I solve Ax=b for every b? or Do the linear Combinations of the columns fill 3-D space?

Yes, if matricies are non-singular, invertible.
Each coloumn contributes a new plane, the answer would be no if 2 coloumns are in the same plane.
