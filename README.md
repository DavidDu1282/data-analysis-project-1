# CMPT353 Final Project
All work were done in Python notebooks, as the process was iterative and we had to frequently change and test only pieces of code in each file. However, simply selecting open the notebooks in order and running all cells should provide the same results as us (along with additional output that was not used in the report). To ensure all codes run appropriately, please download the entire respository into a folder.

Begin with the 'find_attractions.ipynb' notebook, which filters the provided 'amenities-vancouver.json.gz', the JSON File of OSM Data for the tourist attractions. This notebook should output the file a copy of the file 'part-00000-cc1292d9-e874-42fa-aa7d-fa5ecffae4ae-c000.json', albeit presumably with a different name. Our code in the next step will use 'part-00000-cc1292d9-e874-42fa-aa7d-fa5ecffae4ae-c000.json'.

Our analysis in the next is done in 'Project_pt.1and2_final.ipynb', which as it suggests, contains the output for our analysis in part 1 and 2 (refer to the report). The reason we put these two together is that we use the outputs of part 1 in part 2, as well as sharing the distance function. The machine learning models will output slightly different scores from the report due to random nature.

Finally, 'Airbnb.ipynb' contains our analysis for part 3 of the report, with the various graphics as well as the model to predict price.

The libraries we used during the exercises:
    sys, pandas, numpy, math(default python library), matplotlib.pyplot, datetime(default python library), scipy, sklearn, re

The libraries we used that were not in the exercises, so you might need to install them:
    folium, mip, itertools(default python library), nltk, seaborn

