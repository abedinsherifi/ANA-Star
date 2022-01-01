![Your Repository's Stats](https://github-readme-stats.vercel.app/api?username=prespafree1&show_icons=true)
![Your Repository's Stats](https://github-readme-stats.vercel.app/api/top-langs/?username=prespafree1&theme=blue-green)
![](https://komarev.com/ghpvc/?username=prespafree1)

<p align="center">
  <a href="https://github.com/prespafree1/ANA-Star">
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/prespafree1/ANA-Star.svg">
  </a>
  <a href="https://github.com/prespafree1/ANA-Star">
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/prespafree1/ANA-Star.svg">
  </a>
    <a href="https://github.com/prespafree1/ANA-Star/graphs/contributors" alt="Contributors">
        <img src="https://img.shields.io/github/contributors/prespafree1/ANA-Star" /></a>
</p>

# Anytime Nonparametric A* (ANA) Algorithm
## Introduction
The Anytime Nonparametric A* (ANA*) algorithm is an A* variant resembling closest to the ARA* algorithm. The ANA* algorithm expands the open state s based on the following: <br>
<p align="center">

    e(s) = (G – g(s)) / h(s)

</p>
This is exactly what makes ANA* different from ARA*. ARA* uses the following equation for the expansion of the open state s: <br>
<p align="center">

    f(s) = g(s) + epsilon * h(s)

</p>

The epsilon parameter above gets set by the user and it usually increments in fixed amounts. The fine tuning of this parameter usually requires trial and error. This is the motivation behind the ANA* algorithm which removes the dependency of the algorithm based on user set parameters. In this experiment, two searching algorithms are compared. ANA* is compared against the Breadth-First-Search (BFS). Results are posted in the next section below.<br>

## Results
### BFS

Image below summarizes the cost function for each grid(maze) problem. The BFS algorithm per the data below indicates that the cost function decrease as maze size increases. It can be observed that the maze size of 500x500 has the lowest cost function from the rest of the maze sizes. <br>
![](images/Data.png) <br>

### Maze 10x10
The solved path provided by the algorithm is provided in the image below as an array. The “S” start
position is always (0,0). The path values are also plotted as shown below. <br>
![](images/10_10.png) <br>

### Maze 50x50
The solved path provided by the algorithm is provided in the image below as an array. The “S” start
position is always (0,0). The path values are also plotted as shown below. <br>
![](images/50_50.png) <br>

### Maze 100x100
The solved path provided by the algorithm is provided in the image below as an array. The “S” start
position is always (0,0). The path values are also plotted as shown below. <br>
![](images/100_100.png) <br>

### Maze 500x500
The solved path provided by the algorithm is provided in the image below as an array. The “S” start
position is always (0,0). The path values are also plotted as shown below. <br>
![](images/500_500.png) <br>

https://prespafree1.github.io/BFS-Algorithm/

