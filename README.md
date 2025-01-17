# Introduction to the Gaussian process regression

Georgios Karagiannis, Department of Mathematics, Purdue

SURF 2016

July 8, 2016


## Description

The main topic of ths lecture is Gaussian Process regression: how to specify the statistical model, how to train it, how to asses it, and how to perform model choice. 

### Readings
- [Rasmussen, Carl Edward. "Gaussian processes in machine learning." In Advanced lectures on machine learning, pp. 63-71. Springer Berlin Heidelberg, 2004.](http://www.GaussianProcess.org/gpml)
    + Chapters: [2](http://www.gaussianprocess.org/gpml/chapters/RW2.pdf), [4](http://www.gaussianprocess.org/gpml/chapters/RW4.pdf), [5.1, & 5.4.2](http://www.gaussianprocess.org/gpml/chapters/RW5.pdf)
- [Roustant, Olivier, David Ginsbourger, and Yves Deville. "DiceKriging, DiceOptim: Two R packages for the analysis of computer experiments by kriging-based metamodeling and optimization." (2012).](https://www.jstatsoft.org/article/view/v051i01/v51i01.pdf)

## Installation of Required Software

You are required to install R.
- Install R by following the instructions [here](https://cran.r-project.org/)
- Install the required R packages: 
	+ open R and copy/paste:
		+ install.packages('DiceKriging', repos = "http://cran.us.r-project.org")
		+ install.packages('lhs', repos = "http://cran.us.r-project.org")

You are required to install git.
- Install git which is available from [here](https://git-scm.com/downloads)
	+ Windows users: make sure you select that you want to use it from the Windows command prompt.

You can download all the teaching and practice material, by:
- running: git clone https://github.com/georgios-stats/Intro_GPR_SURF_2016.git
- cd Intro_GPR_SURF_2016

## Slides and running example

The slides of the lecture are available [here](./slides.pdf)

Running examples:
- [Numerical example](./Numerical_example.ipynb)
- [The Piston Simulation function model in 2D](./Practice_2D.ipynb)


## Handouts

After the lecture there will be a practice session. 

Practice (You can use the R package [DiceKriging](https://cran.r-project.org/web/packages/DiceKriging/index.html))
- [Practice Catalytic Reaction 5D](./Practice_CatalyticReaction_5D.ipynb)
- [Practice Piston 7D](./Practice_Piston_7D.ipynb)
- [Practice Robot Arm 8D](./Practice_Robot_Arm_8D.ipynb)

Solutions (if you need to still some code):
- [Practice Catalytic Reaction 5D](./Practice_CatalyticReaction_5D_solution.ipynb)
- [Practice Piston 7D](./Practice_Piston_7D_solution.ipynb)
- [Practice Robot Arm 8D](./Practice_Robot_Arm_8D_solution.ipynb)





