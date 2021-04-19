# Potential outline for milestone #1 video

### Discuss the data wrangling that has been completed:
- Explain the structure of a log event (use the image)
- Discuss the important parts of the event (INFO/WARN, 9 types of events)
- Explain that each event only references one single block

### Discuss the planned data wrangling that still needs to be done:
- Splitting the data into train/validation/test sets using the instructions provided in out course notebooks. 
- Making 9 separate dataframes (one for each type of events) with unique blocks as the rows of the dataframes (primary keys).
    - Combine all dataframes into one dataframe with block ID as first column and block attributes as other columns and block label as one column. 
- Convert non-numerical variables to numeric with onehot encoding. 

### Discuss model development plans:
- Ben fill in this part?