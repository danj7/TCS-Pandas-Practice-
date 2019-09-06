# TCS Pandas Practice
Practicing cleaning data in pandas using the Teacher Compensation Survey from https://nces.ed.gov/ccd/tcssurv.asp. I loaded the files, which were tab-separated files, and fixed the data types of some of the columns. Also changed the column names to be more readable and added a column with the state of each school in the data.

I grouped the data for each state and graphed a histogram of average salaries for each, but only for the first dataset because the other one had too many states to be useful. The image generated is still a little busy but it was just meant to figure out how to graph them, since the data types were cast as `object` after grouping them, so I had to recast them as `float`.

![Histogram of Mean Base Salaries in various schools](https://user-images.githubusercontent.com/13749006/63202587-6a9f7180-c058-11e9-98f5-47d5c8d2cafd.png)
