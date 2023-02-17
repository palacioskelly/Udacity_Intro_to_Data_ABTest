# Udacity_Intro_to_Data_ABTest
## Analyze A/B Test Results

For this project, you will be working to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. Your goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.


## Software and Libraries
- Python
- Jupyter Notebook
- NumPy
- pandas
- Matplotlib
- Statsmodels

## Data 
There are two csv datasets, ab_data.csv and countries.csv, provided by Udacity with the e-commerce website A/B test information.

### Features
#### ab_data.csv
- `user_id`
- `timestamp`
- `group`: control or treatment
- `landing_page`: old_page or new_page
- `converted`: True or False
#### countries.csv
- `user_id`
- `country`
