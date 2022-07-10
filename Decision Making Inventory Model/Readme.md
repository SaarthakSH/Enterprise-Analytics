# How to access and execute RMD file

Installing and loading the necessary libraries and loading the associated data set are prerequisites for running the RMD R file. My recommendation is to make a folder to hold both the dataset and the RMD file when you download both, then inside that folder, make another folder called "DataSets" and put the excel file containing the data set inside of that. All of the work is done in a R Markdown file when you open the RMD file, and you must import the dataset in order to execute it. You can access the data set in the "DataSets" folder or any other name you like from the files tab. The route link for the imported data set must be copied after the data set has been imported since it must run with the installed libraries in order for the code to run. All codes should now run and function correctly after completing that. The codes can be knitted into PDF or HTML files, as desired.

# Decision Making Inventory Model

Making decisions about inventory using Excel and R to get the best solution. The best total cost and order quantity were determined using Excel Solver in the first section. The same optimization procedure was then carried out in R, where the optimized value was obtained by first creating a function and then using that function. To get at the ultimate conclusion, a sensitivity analysis was conducted utilizing the what-if approach. To verify for the best fit distribution, a triangular probability distribution was also created at the conclusion, and the Shapiro test was run for each of the minimal total cost, order amount, and yearly number of orders.

## Skill used – 

R, Excel, Hypothesis Testing, Decision Making model, Optimization, Triangular Probability Distribution. 

## Output-

A report on the Decision-Making Inventory Model that is objective and well-organized. We were able to use this to get the best price for our goods, and we even cross-checked the value we had determined by optimizing the same inventory in R. Finally, a triangular probability distribution was created in R, and the Shapiro test was used to confirm that the best fit.
