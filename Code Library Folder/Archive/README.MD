In this notebook we have used another approach for data augmentation.
We used the flow_from_dataframe() method to read the images from the specified directory 
and perform image augmentation on-the-fly based on the information provided in the dataframe. 
The DataFrameIterator is an iterator that generates batches of image data and their corresponding target values (labels) from a dataframe.
