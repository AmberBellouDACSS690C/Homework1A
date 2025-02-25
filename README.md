## Final Map

[Click here to see the best countries map](https://amberbelloudacss690c.github.io/Homework1A/)






# Homework1A Prompt and Guidelines
Homework 1 A
For this homework:

1) Prepare a repository on GitHub (in the organization created for the course): you can name the repo as HW1_repo. Clone the repo to your computer.

2) You will use Python to prepare the data for this homework. Start a new Jupyter notebook  and work from the  HW1_repo.

You do not need to do merging, all the data is in this link: "https://github.com/DACSS-CSSmeths/Spatial-Exploring/raw/refs/heads/main/maps/countriesCIA.gpkg". 
Start by reading the data using  Python. As it is a geopackage file look for the right layers. (check the piece of code 8 in my tutorial Links to an external site. to explore the layers available in this kind of files). 
3) You may use either Python or R to prepare the plots. 

4)  The "prepare the data" stage in Python consists of:

1. Finding the best scheme to get 5 bins of the variable obesity.Remember the best is the one with the lowest ADCM. (In my tutorial pay attention to codes 29, 30 and 31.
2. Use the scheme you found in the previous step to bin the  columns on alcohol and tobacco. You already have those variables binned using FisherJenks, if the previous step recommends this same scheme, you do not need to redo the code for these variables, just use them. But if the previous step recommends a different one, you need to create new variables (lines 36 and 46 are useful for that).
3. Find the countries that are doing the best in all three variables (I used line 48 in my tutorial to compute the worst countries in those two columns, use that as a reference now that you have three).
4. The code for these first three steps has to be in one file named code_hw1.
5. This code will create a new file, as some variables have been binned. Just rewrite the layer (see line 57). This time this map file will be in your local repo HW1_repo; then commit and push it to GitHub cloud.
5). In R or Python: Prepare a plot. If you are in RStudio, go to the repository (folder) for this homework, and start a new R Notebook (or Quarto).

1. Read the map file you just pushed to your GitHub repo. Prepare the code to plot the countries you found in the last step: the countries that are doing the best in all three variables. See codes 54,and  55 in my tutorial.
2. YOU ONLY PLOT the NON-interactive version (change codes 54,and  55 in my tutorial.)
3. The code to plot the countries has to be in another file. All the data has to be read from the PATH from GitHub. For this part, you create a file named index, and you make sure that you create an html version with the same name. The result of this code will be published as a web page from GitHub.
THE CODE IN R for the plots in the tutorial is HERE Download HERE.
7) SUBMIT: Send me the link to your REPOSITORY, the README should include the link to the webpage with the plot (index.html)

8) THE RUBRIC:

I will explain in terms of negative points:

A. (-4) points if you do not create a webpage and write the link in the README of the repository.
B. (-4) points if you do not create two codes to produce the final result.
C. (-5) points if your code does not address the problem, that is, you include more code than needed.
D. (-2) points if your do not use Python for the first part.
E. (-1) points for every day you take to submit after the deadline.
