# Processing-data-in-chunks-and-Optimizing-Dataframes



In this project we will be working to extract and load data with the proposed minimal memory usage possible( assuming that we only have 10 megabytes of memory available). In order to do so, we will utilize the capability of chunking rows of data from a dataset into memory.

The first step will involve analyzing the quality of the data and the max number of chunks or rows to process at a time. We will identify the the columns within each chunk that takes ups the most memory of the time and determine the possible number of chunks that will only utilize 5 megabytes at a time.


The dataset provides information of financial lending data from the Lending Club.

We will be working with their 2007 Loans Dataset provided by Dataquest.io

Site: 
https://www.lendingclub.com/investing/peer-to-peer
