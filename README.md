# Problem Statement
>You have a function that generate a number between 0 to 1 randomly which is uniformly distributed. Now calculate the number pi.

# Solution Explaination

So the basic idea is to randomly draw a point in a 1 to 1 square, since you can call the ```random.uniform(0, 1)``` function twice *(Done in the Python/CalculatePi.py on line number : 9 and 10)*, it will generate 2 number between 0 to 1. Let's use them one from the x axis and one for y axis. 

Let take an example of **x = 0.2** and **y = 0.6**, then we are gonna get somewhere the point like here.

![imge1](https://github.com/Rajat-Dabade/Best-Coding-Question/blob/master/RepoEssentials/img1.png)

>So, let me randomly draw some more point then it will be look like

![imge2](https://github.com/Rajat-Dabade/Best-Coding-Question/blob/master/RepoEssentials/img2.png)

>Now let me draw a sqaure and circle through it.

![imge3](https://github.com/Rajat-Dabade/Best-Coding-Question/blob/master/RepoEssentials/img4.png)

As you can see now, the goal hear is to calculate all the point inside the circle

![img5](https://github.com/Rajat-Dabade/Best-Coding-Question/blob/master/RepoEssentials/img6.png)

and calculate all the point inside the sqaure.

![img6](https://github.com/Rajat-Dabade/Best-Coding-Question/blob/master/RepoEssentials/img7.png)

The ratio between the number of points inside the circle and number of points inside the square will be preety closed to ratio between the total area of circle and total area of this sqaure.