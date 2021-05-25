# Python <-> R interactions and collaborations

Dimitri Marinelli  
25/5/2021 -  #DataForGood - CorrelAid Rhein-Main


There are scenarios when selecting one of the two is a loss. The two languages 
and the two ecosystems are quite different and have different strengths. How can
we benefit from the best of the two languages? When working on collaborative 
data science projects, often teams prefer to stick to one of the two languages
losing possible talents that would otherwise shine if another choice was taken.
Can we avoid it?  
We will see what tools we have to overcome these limitations: from "rpy2" and 
"reticulate" to "arrow" in Jupyter and RStudio.


# Tools: 

![tools](<assets/Python - R interactions and collaborations.png>)

# Notebooks

- Example on how to use Python in an R environment - [`RToPython.Rmd`](RToPython.Rmd)
- Example on how to use R in a Python enviroment - [`PythonToR.ipynb`](PythonToR.ipynb)
- Example on how to exchange data frames between R and Python with Apache Arrow.
  In this case, from Python [`Arrow.ipynb`](Arrow.ipynb) -> [`Arrow.Rmd`](Arrow.Rmd)
  by using feather files. 
