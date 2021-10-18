# https-github.com-new
1. Transportation problem:
Cities 1 and 2 have 100K and 200K passengers per year, respectively. Airports 1 and 2 can accept a demand of 150K and 150K passengers per year, respectively. The city-to-airport driving times are listed at right.
Given: 
a(i): the demand of city i, i∈{1,2}
b(j): the capacity of airport j, j∈{1,2}
c(i,j): the driving time from city i to airport j

To find:
x(i,j): the passengers traveling from city i to airport j
z: the total travel cost

Model:
min⁡∑_(i,j)〖{x(i,j)×c(i,j)}〗
Subject to
∑_j〖x(i,j)=a(i),∀i〗
∑_i〖x(i,j)=b(j),∀i〗
x(i,j)≥0
Sample solutions from GAMS: x(1,1)=100,x(2,1)=50,x(2,2)=150,and z=500

Please formulate the linear programming problem and solve it using GAMS Solver.


2. Shortest path problem
(you can assume the link length as 1 as a default value and try different values as a sensitivity test)
![image](https://user-images.githubusercontent.com/89508514/137692466-8f809bbd-ff5f-486b-85af-2d53c45fbce8.png)
![image](https://user-images.githubusercontent.com/89508514/137692752-145d2da1-0e49-4b58-a7d6-750da13752a4.png)
