## L2T05: Datasets and Dataframes 

There are two jupyter notebooks which work through data and dataframes.

## Installation

To run these notebooks, you need to have Jupyter Notebook installed. You can install it using pip:
```
pip install notebook==7.0.3
```
## Running the Notebooks

1. Clone this repository to your local machine using:

```
git clone https://github.com/vswapna3202/L2T05.git 
```
2. Navigate to the directory containing the notebooks:
```
cd <directory-with-notebooks>
cd L2T05
```
3. Start Jupyter notebook
```
jupyter notebook
```
4. Open the notebooks in your browser and execute the code cells as needed.

## Notebooks

### Datasets Compulsory Task
Datasets Compulsory Task notebook performs the following actions:   
    - Selects the 'Limit' and 'Rating' columns of the first five observations  
    - Selects the first five observations with 4 cards  
    - Sorts the observations by 'Education'. Show users with a high
    education value first.  
    - has a short comment about the following code:  
```python
        df.iloc[:,:]
        df.iloc[5:,5:]
        df.iloc[:,0]
        df.iloc[9,:]
```
### Report    
Report notebook performs the following actions:    
    - Creates a DataFrame that contains the data in balance.txt  
    - Provides the following information:  
        ○ Compares the average income based on ethnicity.  
        ○ Finds on average, do married or single people have a higher balance.  
        ○ Calculates highest income in dataset.  
        ○ Calculates lowest income in dataset.  
        ○ Sums number of  cards are recorded in dataset using sum().  
        ○ Counts the number of  females with information vs number of males using count().  

### Dependencies
The notebooks require pandas and numpy libraries to be installed. You can install them using pip:
```
pip install pandas numpy
```