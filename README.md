For this homework, please use the data given in homework 4 data (SEAS8515_HW4.json).
Please submit one notebook for all the below questions with Markdowns for each of them. Please
make sure you run your code cells to show the output as well to receive credit. Thank you.

Question 1: Load the json file into a dataframe. Display the dataframe and do a dataprofile on it.
Question 2: Save the dataframe as a delta table.
Question 3: reload the save table and the some data into your table. Using the versionof API, read
the current and the prior version of the table and display them.
Question 4: Read the different versions using the option(readChangeData)...etc method. Reflect on
why this did not work.
Question 5: Enable CDC on the same table, do some changes, and read the change data between
the last two versions? Change the configuration of the api to read between version 0 and any of the
other versions? Reflect on why it worked/did not.
