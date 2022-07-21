# pandas-challenge
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.
(Instructions assisted in jupyter notebook)
District Summary
Create a high-level snapshot of the district's key metrics in a DataFrame, including the following:

Highest-Performing Schools (by % Overall Passing)
Create a DataFrame that highlights the top-5 performing schools based on % Overall Passing. Include the following metrics:

Lowest-Performing Schools (by % Overall Passing)
Create a DataFrame that highlights the bottom-5 performing schools based on % Overall Passing. Include the following metrics:

Math Scores by Grade
Create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student). Use your judgment to create four bins with reasonable cutoff values to group school spending. Include the following metrics in the table:

Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)

Scores by School Size
Create a table that breaks down school performance based on school size (small, medium, or large).

Scores by School Type
Create a table that breaks down school performance based on school type (district or charter).

Conclusion analysis:
------------------------------------------------------------------------------------------------------------------------------------------
After looking through the school summary data, there is an obvious trend in the top performing schools. The school type that is in the top 5 are all Charter schools, and the bottom 5 are all district schools with an alarming difference of 40% overall passing rate. Also  District schools have more students than the charter schools. The more students within a school could result in lack of attention to academic needs which could explain the possibility of the low passing rate for districts. 
Another obvious trend is Charter schools spend less money per each student compared to District school students. Moreover, typically a higher budget significantly affects students success. We would need more information on the location, possibly teachers pay to provide clarity of the Districs alarming pass rate of 50%. 
