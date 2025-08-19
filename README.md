# Football-Analysis-Red-Cards-and-Goals
We wanted to answer the following question: based on the dataset, do red cards in games lead to more goals in general?

# Explanation of files
The analysis.ipynb file is a notebook containing all the code used in this task. It is where all graphs and analysis are generated. The report.pdf contains all our findings in a coherent document. The report is written for anybody from an academic background to understand. We have also included the data sources events.csv and games.csv.

# Explanation of approach
My logic for approaching this question was to ask the most obvious questions first and to incrementally introduce granularity and complexity to analysis, thereby hopefully increasing the precision and robustness of our answers in return. For instance, our first analysis below asks the very basic question of whether games in which at least one red card occurs have more goals in general than games without, while our final mode of analysis applies a more complex survival analysis method to take account for the time red cards occur in games. In this way the analysis tells a story, which is coherent and easy to follow. 

# Overall Conclusion
My overall conclusion is that we have sufficiently shown that red cards do increase total goals scored. Across multiple modes of analysis we showed that goal scoring rates increased in general and across the leagues. We strengthened this argument with our survival analysis by showing goals occurred more quickly after red cards, also accounting for the exact timing of the red cards.
