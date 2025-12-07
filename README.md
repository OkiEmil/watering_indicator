# Watering Indicator for houseplants
The project is called "Watering indicator for houseplants" and the team members who worked on this are Kristjan Saar, Kevin Noormets and Emil Henri Rooste. The coordinator of this project was the company Click & Grow

The goal of this project is to provide valuable insight into how a plant's weight could be used to predict when to water it. Another result of this project is a model, which is capable of predicting when a plant should be watered. We chose this project for our "Introduction to data science" course, since it sounded like an interesting and actually quite useful task.

We organized our data analysis methods into the notebook called `Data_Analysis.ipynb`. To get a better understanding of the dataset and the aspects we focused on most, refer to the `Data_Analysis.ipynb` notebook.
The notebook `Models_and_Evaluation.ipynb` is the notebook, where we gathered all of our models and evaluation tactics. We also kept a copy of all of our notebooks, which we used during different phases of the project and placed them in the folder `Testing_Notebooks`. This means that we ended up leaving most of the unproductive code into those notebooks. The original dataset is called `feeds.csv`, and we split it into two datasets called `feeds_5.csv` and `feeds_30.csv`. For more information regarding the goals of the project, you can refer to the report in the file `H2_report.pdf`. You can also find a poster displaying our methods and discoveries in this repository.

The python modules, which one would definitely need are:
* Pandas
* Matplotlib
* Seaborn
* Statsmodels

Additionally some optional parts of the code require Astral and Piecewise-regression


You can reproduce our results by executing the code contained in the accompanying GitHub repository together with the provided dataset. One should first start by getting an understanding of our data from the `Data_Analysis.ipynb` dataset, after which one could execute our code contained in the `Models_and_Evaluation.ipynb` notebook. Additionally, the value of the variable “field” and the upper/lower bounds of our data may be modified to generate outputs that correspond to a specific subset of data. Some tinkering with the hyperparameters would also be required to gather such a deep understanding of the data, as we have.
