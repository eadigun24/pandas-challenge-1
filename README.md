# pandas-challenge-1
## Challenge Notes
* The main requirements for this challenge was from the module challenge details in bootcamp.
* Part 1:
    * This section was straight forward with regards to the code necessary to generate the desired output.
* Part 2:
    * In keeping with the output from the starter files, i decided to display the "selected" columns as shown. I was more inclined to display all the columns within the dataframe (top 5 using the head method).
    * using a custom method to provide logic for the apply method in this section.
* Part 3: 
    * Printed the receipt values based on the client ids from part 1.
* Part 4:
    * Ummm yeah, somthing interesting to note here ...
    * while creating the summary dataframe, I decided to take the following approach:
        * Use the isin() method (API reference) on the dataframe to extract the top 5 client data.
        * Use the groupby() method to coallesce the data (as supposed to iterating through the subset from above).
        * Then finally, I aligned the data with order of the client id list from part 1.
* Summary:
    * As required, providing a brief synopsis on the sorted summary client dataset.