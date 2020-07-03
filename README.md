# Google-Job-Analysis

## Overview
This project focuses on analyzing job data collected from Google's job board in order to analyze which types of jobs are more prominent, 
what skills are most typically sought after with regards to program language and which locations are most frequently hiring. More specifically, 
the goal of this analysis is to visualize these aspects in order to inform future investigation.

![Google_Job_Dataframe]()

## Technologies
The dependencies used are as follows,
import matplotlib.pyplot as plt
import pandas as pd
import numpy as np
import re
import matplotlib.pyplot as plt
import cufflinks as cf

Python 3.7.6 and Plotly 4.8.2 are being used in this notebook.
If you have an earlier version of plotly(~3.10.0), there is provisional code 
commented out on line 23 that should assist in viewing the visualizations.

## Results
### Programming Languages
Overall it is noticeable that minimum and preferred qualifications are similar in terms of what languages are present in each category.
Google Jobs more often require a language at a minimum than calling it preferred. Tbere were three programming langugages in particular that stood out
in contrast to this trend: Perl, D, and Swift. The two most required by far were python and java. 

![MinPref Comparison]()

### Job Category
TBC
The results for this analysis were very interesting. More soon.

![Category Frequency]()

### Location
With regards to job location, the data showed what one would most likely have suspected. Google's primary place of hiring 
tends to be Mountainview, CA. When considering locations outside of the United States and on the east coast of the United States,
job hiring frequency plummets significantly. Images to come. 

![Location Frequency]()

### Potential
This project could be taken in a number of directions. I forsee one visualization wise in which The programming languages and Job categories possibly
among other features in the data, are plotted on an interactive world map so the reach of google and the importance it places on which positions and skills
are even more evident.
