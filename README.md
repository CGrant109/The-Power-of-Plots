## The-Power-of-Plots:
## A Deep-Dive on Pharmaceutical Drugs with Mice using Pandas and MatPlotLib

[![scientists.jpg](https://i.postimg.cc/rww5rs5b/scientists.jpg)](https://postimg.cc/nCNs8HRY)

Analazying four different drugs and their effectiveness towards lowering tumor sizes on mice.

## Methods Used  

Dataframes, summary statistics, bar and pie charts, line plots, scatter plots, correlation and regression


## Technologies

Jupyter notebook, Pandas, MatPlotLib.pyplot, scipy.stats, numpy


## Data Source

Data found in Pymaceuticals/data/mouse_metadava.csv,Study_results.csv

## Installation

Code was tested using Jupyter notebook.  The environment also needs the ##Technologies listed above. The environment was setup as follows:

```bash
source activate PythonData38
jupyter notebook
```

## Additional Analysis

#1.
[![linearregression.png](https://i.postimg.cc/W1xt1180/linearregression.png)](https://postimg.cc/9DtcxVvf)


Demonstrated within the Correlation and Regression model, There is strong relation between having higher tumor volume for a mouse with a higher weight count. This means in basic sense that, a mouse that gains weight, will have a larger tumor volume.

#2. 
[![barchart.jpg](https://i.postimg.cc/q7fMdZBL/barchart.jpg)](https://postimg.cc/Hr2Cwzyc)


Evidenced in the bar chart and summarty statistics chart, Ramicane and Capomulin seem to be the most effective in that they have the lowest mean and medians for tumor volume count. They also have more tests done than other drug options.

#3. 
[![linechart.png](https://i.postimg.cc/HxzpXYwZ/linechart.png)](https://postimg.cc/Fdf5QQn3)


Evidenced by the line chart, Capomulin eliminated tumor volume by nearly 7mm3 between 20 and 35 days of use. This once again shows that Capomulin is a very effective drug among the choices available in our data.




Written by Connor Grant
