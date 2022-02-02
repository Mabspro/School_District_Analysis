# School_District_Analysis
Analyzing School Districts Student Test Scores to show trends and school performance based on schools in the region.

# Challenge and Approach:
- This is a very high level view of the districts key datapoints
- It contains data in table format showing:
  - Top 5 performing schools
  - The average reading scores
  - The average math scores
  - Performance based on school size
  - Performance based on type of school, etc.

- The Challenge:
  - Ninth graders' grades at at Thomas High School have been changed. I was tasked with  understanding the full extent of the cheating scandal.
  
- Approach taken:
  - Removed the nith grade match and reading scores from Thomas High while keeping all other data the same.
  - Filtered the dataframes with logical operators.
  - Replaced incorrect values with NaN.
  - Replace reading and match scores for 9th graders at Thomas High with NaN.
  - Merge datasets (clean data with the school datasets).
  
# Results
- How is the district summary affected?
  - The impact of removing the bad scores from Thomas had minimal impact, though a negative imapct. The math and reading scores dropped a bit from about 79 to 78, and 82 to 81 respectively.
- How is the school summary affected?
  - The school summary was adversely affected (as expected) with the sort of drastic approach taken in the analysis by dropping macth and reading scores. The average math and reading scores went from 83.41 to 59.85 and 83.84 to 60.24, respectively. Passing Math and reading scored for the school went from 93.27 to 66.9 and 93.31 to 69.66, although the overall passing did not change. 
- How does removing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
  - The 9th graders were significantly affected, going all the way to 0 on the math and reading. All other grades remained unaffected. 

# Summary
All scores by (school spending, school size, school type) were all impacted. They dropped due to the removal of the Thomas High School's 9th grade math and reading scores. The changes made after reading math and reading scores have been replaced with NaN:
- Slightly dropped district specific scores
- Significantly dropped school specific scores in macth and reading
- Change in the year over year scores
 
