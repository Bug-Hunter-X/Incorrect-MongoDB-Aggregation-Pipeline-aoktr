# Incorrect MongoDB Aggregation Pipeline
This repository demonstrates a common error in MongoDB aggregation pipelines and shows how to fix it. The original pipeline produces inaccurate results due to an incorrect ordering of stages. The solution provides a corrected pipeline that produces the expected results. 

## Problem
The original script uses an aggregation pipeline to find the top 10 most frequent values in a field. However, due to the order of operations, it does not return the correct results. 

## Solution
The solution fixes the order of aggregation stages to correctly perform the aggregation. 
