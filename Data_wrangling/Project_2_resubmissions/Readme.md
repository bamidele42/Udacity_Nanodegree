## Wrangling and Analyze Data

### Data Gathering, Assessment and Cleaning

The data wrangling process started with gathering the ‘Weratedog’ datasets from three different sources.

The second stage was the Assessment stage. The assessment was done in two phases. The first phase was the visual assessment  which was done using Microsoft excel. Six quality issues were discovered at this stage namely while three tidiness issues were also found, The visual assessment was followed by programmatic assessment where two more quality issues were discovered.

The third stage was the cleaning stage, in this stage the missing values or null values were first handled to avoid cleaning repetition, columns with atleast 70 percent null values i.e columns that have more  than 70 percent missing values will likely not be useful for further analysis. But columns that have not more than 50 percent missing values were either filled with the mean or average of the values in the column or just “Not available for string data type columns”.

Quality issues were solved with the help of various pandas method as well as string methods where appropriate, the lambda function was also used throughout the cleaning process to make codes shorter and legible.
The three cleaned dataframes were later combined into one big dataframe after resolving tidiness and quality issues, at this point I need the original tweets in the dataframe, so all duplicated tweets were dropped before the final combined dataframe was saved.

### Analysis and Insights¶
The first question that was answered from my cleaned dataset was: Which dog stage has the most retweeted count on the average? This gave us insight into what stage people like to post or say something about their dogs, and also show that Puppo stage of the dog is famous in this category.
The second question was which dog stage has the most likes i.e favorite count. The puppo stage was also the most preferred among all the dog stage, has it has the most likes on the average.

The third question was to investigate the dog with the highest rating in the dataset: The dog “Atticus” seems to have the highest rating over 1776 over 10, how true this figure is will be subjected to further analysis.