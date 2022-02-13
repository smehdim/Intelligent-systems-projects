this home work consist of 3 main parts 

### opimizing in convex functions

p1 notebook will optimize the convex function  <img src="https://latex.codecogs.com/png.image?\dpi{110}&space;\bg_white&space;\inline&space;3x_1^2&space;&plus;&space;12x_1&space;&plus;8x_2^2&space;&plus;&space;8x_2&space;&plus;6x_1x_2" />  .

in this note book i tried to find proper alpha rates using backtracking line search.

### optimizing in non convex functions

in p2 notebooks i will try to optimize function <img src="https://latex.codecogs.com/png.image?\dpi{110}&space;\bg_white&space;\inline&space;x_1^2-10x_2cos(0.2\pi&space;x_1)&space;&plus;&space;x_2^2&space;-15x_1cos(0.4\pi&space;x_2)" />    in restricted space [-15,15]
p2_a tries to minimize this function using gradient decent and problem is solved for 2 starting point examples. as result can be seen the answer is dependent on initial condition.

in p2_b step size will not be static anymore and two different methods are used to obtain proper step sizes.

in p2_c we will do optimization using a different approach from gradient decent named simulated annealing which is a metaheuristic approch for optimization.

### SVMs from scratch and using sklearn library
in last notebook i tried to classify iris data using sepal length and sepal width using svm. accuracy difference of of two models is mainly due to different definitions of accuracy however final seperating lines shows used algprithms to apply svm was not the same
