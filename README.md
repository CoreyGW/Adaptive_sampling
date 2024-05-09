This is repository contains work for my master's project, the project is currently in process so available code and results are not final. The project aims to explore adaptive cluster sampling under a number of slight alterations.

The bulk of work is contained in "Creating the framework.rmd" and can be viewed as compiled html in the corresponding html file.

Key features:
	- Simulates adaptive cluster sampling on a set of points clustered on a grid. grid cells are used as the sampling unit and the average number of points per grid cell is what is estimated.
	- Make sure to run all cells if you are running the code, there are quite a number of specific defined functions.
		- The main workhorse functions are simulate_m() which simulates m samples from a population of points on the grid and modified_HH as well as modified_HT.
	- Simulation results are available at the end of the file or in the alternate file: results_only.html (NOT CREATED YET!)