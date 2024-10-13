# *Automatic EDA with ydata_profiling* 🤖 #DataScience #EDA

## Importing Libraries 📚
We start by importing necessary libraries: pandas for data manipulation, seaborn for data visualization, and ydata_profiling for automatic EDA.

### Loading Sample Data 🚣‍♀
We load the Titanic dataset from seaborn to demonstrate the ydata_profiling library.

#### Generating Profile Report 📊
We create a profile report using yd.ProfileReport(df) and save it as an HTML file.

##### Using Own Dataset 📈
We load our own dataset from an Excel file (random_data.xlsx) and generate another profile report.

###### Displaying Profile Report 📊
We display the profile report directly in the notebook using display(profile).

###### What's in the Report? 🤔
The report includes:

- Data summary (counts, means, std)
- Data distribution (histograms, box plots)
- Correlation analysis
- Missing value analysis

*Benefits of ydata_profiling* 💡
This library saves time and effort in EDA, providing valuable insights into data quality and structure.

Getting Started 🚀
Install ydata_profiling using pip install ydata_profiling and start exploring your data with ease! #DataAnalysis #MachineLearning
