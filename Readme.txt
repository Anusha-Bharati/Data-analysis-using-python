The prototype was developed in Figma and the link to the software is https://www.figma.com/file/sT5S9QQQf9CC17atiqmYxJ/Prototype1?node-id=211\%3A12

Python Assessment tool:
The submission zip folder includes a folder called 'Code'. 
Open Anaconda Navigator, and select Jupyter Notebook. Launch ‘Python OCD-Sleep Tool.ipynb’ from the ‘Code’ folder. Make sure you have the required libraries installed, including:
• numpy: conda install numpy
• pandas: conda install pandas
• ipyplot: pip install ipyplot
• matplotlib: conda install matplotlib
• scipy: conda install scipy
• seaborn: conda install seaborn
• plotly: conda install -c plotly plotly
• statistics: conda install -c conda-forge condastats
• pdfkit: conda install -c conda-forge python-pdfkit

Select ‘Cell‘, ‘Run All‘ to run the file. The model is documented in comments throughout the
file. Change the excel file with new data, to change the outputs.
The next step is to load the survey inputs from the excel file (here 'OCDrawdata.csv', can be found in data folder) using pandas dataframe. 
Then mapping using dictionary values. Following that there is logic for calculation of elements such
as PSQI, MEQ, OCD and PANAS. Now that we have the calculation, the data is loaded in the
excel. Then the element specific functions are run to find the output. The output is published
in a PDF and the sample can be seen after the code screenshots.

Regression Analysis:
The submission zip folder includes a folder called 'Code'. 
Open Anaconda Navigator, and select Jupyter Notebook. Launch ‘regression_analysis.ipynb’ from the ‘Code’ folder. Make sure you have the required libraries installed, including:
• numpy: conda install numpy
• pandas: conda install pandas
• ipyplot: pip install ipyplot
• matplotlib: conda install matplotlib
• scipy: conda install scipy
• seaborn: conda install seaborn
• plotly: conda install -c plotly plotly
• statistics: conda install -c conda-forge condastats

Select ‘Cell‘, ‘Run All‘ to run the file. The model is documented in comments throughout the
file. Change the excel file with new data, to change the outputs.
The next step is to load the survey inputs from the excel file (here 'data_pred.csv', can be found in data folder) using pandas dataframe. 
The regression analysis is performed on the 11 elements of the OCD and Sleep components. The output is displayed in visualised graphs, histograms and plots.

2nd Study analysis:
The submission zip folder includes a folder called 'Code'. 
Open Anaconda Navigator, and select Jupyter Notebook. Launch ‘Study2.ipynb’ from the ‘Code’ folder. Make sure you have the required libraries installed, including:
• numpy: conda install numpy
• pandas: conda install pandas
• seaborn: conda install seaborn
Select ‘Cell‘, ‘Run All‘ to run the file. The model is documented in comments throughout the
file. Change the excel file with new data, to change the outputs.
The next step is to load the survey inputs from the excel file (here 'excel.csv', can be found in data folder) using pandas dataframe. 
The output is displayed in visualised histograms indicating the preference of the participants.