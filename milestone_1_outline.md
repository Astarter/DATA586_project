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
- Group the events by their blockId, and then label the blocks with either anormally(0) or normal(1).
- Then split the blocks into 2 sets: traning set(80%), testing set(20%)  
- Fit the training set into a logit regression model.(We learnt in the previous class)
- Use LOOCV or K-fold cross validation to cross validate the fitted model.
- Test the model with training set, see how good our model is in determining whether a block is valid or not.