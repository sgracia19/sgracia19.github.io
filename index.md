## Projects
---
### Regression

#### [House Price Prediction Intervals](https://nbviewer.org/github/sgracia19/sgracia19.github.io/blob/main/projects/Kaggle_Competitions/House_Price_Intervals/Price_Interval_Prediction.ipynb)

In this project, I tackled a Kaggle competition focused on predicting house sale prices with the narrowest possible prediction intervals, rather than just point estimates. I engineered features from raw sale and property data, handled missing values, and encoded categorical variables to prepare the dataset for modeling. My core approach used a pytorch to build a neural network that outputs lower and upper bounds for each prediction, trained with the Winkler loss to directly optimize interval quality and coverage. The model achieved 89.8% empirical coverage, closely matching the nominal 90% target. To further improve performance, I experimented with architectural changes, regularization, and feature engineering. 

<img src="/images/Prediction_Interval.png" alt= "Housing Price Interval" width="80%">
---
### Clustering

#### [The Ultimate Statistical Fighter: UFC Fighter Segmentation](https://nbviewer.org/urls/sgracia19.github.io/projects/ufc-fighter-style-segmentation.ipynb)

Developed a data-driven clustering model to analyze fighter characteristics, fight outcomes, and fight metrics to identify
distinct fighting styles. Conducted feature engineering, correlation analysis, and visualization to refine insights. Evaluated
segmentation quality using Silhouette scores and within-cluster variance. Conducted matchup analysis to quantify stylistic
advantages, revealing trends in performance across fight styles and weight classes. Future work aims to expand dataset for
more robust classifications and to leverage cluster labels in predictive modeling.

<img src="/images/Fighter_Clustering.png" alt= "UFC Fighter Segmentation" width="80%">

---

### Reinforcement Learning
#### [Master's Research Project: Policy Gradient Methods in Deep Reinforcement Learning](projects\Sebastian_Gracia_MS_project.pdf)

My master's research project gives an overview of the mathematical theory behind certain policy based methods in reinforcement learning. The project covers the basics of Reinforcement Learning, including MDPs, the agent-environment framework, and value functions. My research project goes on to cover the Policy Gradient Theorem and how it allows is Policy Gradient algorithms for reinforcement learning. My project then discuss a few selected algorithms and implementations on selected environments. For a condensed, slightly less technical outline of my project, see my [project defense slides](projects\MS_Defense_Slides.pdf).

<div style="display: flex; justify-content: space-between; align-items: flex-start; gap: 20px;">
    <video style="width: 48%; max-width: 100%; height: auto;" controls autoplay>
        <source src="/images/HalfCheetah_Trained.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <video style="width: 48%; max-width: 100%; height: auto;" controls autoplay>
        <source src="/images/Pong_Trained_Agent.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

#### [Rainbow Road: Autonomous Driving using DQN Variants](projects\RainbowRoad.pdf). [Code Here](https://nbviewer.org/urls/sgracia19.github.io/projects/RainbowRoad.ipynb)

The reinforcement learning algorithm DQN introduced by Minh et. al has many different variants which
improve performance. This project implements the ideas presented by Matteo Hessel et al. showing that combinging many of the variants yields superior performance across different benchmarks than any single variant. The aim of this project was
to implement Rainbow DQN in a simple autonomous driving environment
and compare results obtained to results obtained to the paper.

<img src="/images/highway.gif" alt="Highway Environment" width="80%">


---
### Optimization
#### [Online Optimization using Greedy Projection Algorithm](projects\Online_Optimization.pdf)

Online convex programming is a form of convex programming in which a convex
set is known ahead of time. At each iteration a point is selected from the convex
set then a repeated minimization problem is solved at the point. At each step
a corresponding cost function is evaluated. The cost function however is not
known ahead of time. This project explores an algorithm to minimize possible
costs incurred in an online convex problem. It is called the Greedy Projection
Algorithm. In this project, we introduce the background and properties of this
algorithm, then apply it by hand and numerically via MATLAB code to a set
of Online optimization problems, then discuss the results of each.

<img src="/images/Optimization_Thumbnail.jpg" alt="Optimization of Nonlinear Function" width="50%">

#### [Sudoku Solver Using Linear Programming](projects\Sudoku.pdf)

Sudoku problems can be modeled as a sparse linear system of equations. We can formu-
late the Sudoku ruleset as an underdetermined linear system and the objective as an $l_{0}$ norm
minimization problem. For it is hard to solve an $l_{0}$ norm minimization problem in general, we
relax the objective function to a $l_{1}$ norm minimization problem.
In this project, we built a linear programming model and use this model to solve sudoku puzzles at differing difficulty levels and discuss results.

<img src="/images/Sudoku_Thumbnail.jpg" alt="Example of Sudoku Puzzle" width="30%" >


<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
