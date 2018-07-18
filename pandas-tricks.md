### 1/ show all dataframe columns
    pd.set_option('display.max_columns', None)
    
### 2/ show n columns from the dataframe
    pd.set_option('display.max_columns', None)
    
### 3/ Delete some columns from a pandas dataframe.
    let's have df as our dataframe, removing series 'series1', 'series2', 'series3' from df means:
    
    df = df.drop(df.columns=['series1', 'series2', 'series3'], axis=1)
    
