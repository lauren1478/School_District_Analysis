# School_District_Analysis

### Overview of the school district analysis
The purpose of this analysis was to investigate the math and readings scores at Thomas High School and compare them to the district to see if there is any evidence of academic dishonesty. By replacing the math and reading data for Thomas High School students and running with non-values, this created a comparative set of data against the district, which allows us to describe our findings in detail below.

### How is the district summary affected?

The district summary data showed a quite small decrease in scores with the overall passing only decreasing by 0.3%.

Inclusive of All Students Scores:
![Alt text](https://github.com/lauren1478/School_District_Analysis/blob/main/All_district_summary_use%20this.png)

Exclusive of 9th Grade Math and Reading Scores:
![Alt text](https://github.com/lauren1478/School_District_Analysis/blob/main/No_9th_graders_district_summary.png)

#### How is the school summary affected?

After excluding the 9th grade math and reading scores, the school summary showed much greater impact on the data. The math passing percentage dropped by 26.3%, the reading passing percentage dropped by 27.7%, and the overall passing percentage dropped by 25.8%.

Inclusive of All Students Scores:
![Alt text](https://github.com/lauren1478/School_District_Analysis/blob/main/THS_Original.png)

Exclusive of 9th Grade Math and Reading Scores:
![Alt text](https://github.com/lauren1478/School_District_Analysis/blob/main/THS_no%209th%20graders.png)

#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Originally, the data showed that Thomas High School was very much in line with other charter schools. Once the 9th grade scores were replaced, the school became the worst performing charter school by almost 25% overall passing rate.

Inclusive of All Students Scores:
![Alt text](https://github.com/lauren1478/School_District_Analysis/blob/main/all%20schools%20original.png)

Exclusive of 9th Grade Math and Reading Scores:
![Alt text](https://github.com/lauren1478/School_District_Analysis/blob/main/all%20schools%20no%209th%20grade.png)

### How does replacing the ninth-grade scores affect the following:

##### Math and reading scores by grade
Replacing the 9th grade scores inserted a NaN where the number should be. Unfortunately that is not being reflected on my reading scores graph.

Math
![Alt text](https://github.com/lauren1478/School_District_Analysis/blob/main/grades%20math%20scores.png)

Reading
![Alt text](https://github.com/lauren1478/School_District_Analysis/blob/main/grades%20reading%20scores.png)

##### Scores by school spending
There is very minimal difference in school spending, and no difference if rounding to the whole number.

Original
![Alt text](https://github.com/lauren1478/School_District_Analysis/blob/main/spending%20original.png)

![Alt text](https://github.com/lauren1478/School_District_Analysis/blob/main/spending%20no%209th%20grade.png)

##### Scores by school size
Again, very small difference and no difference when rounding to the whole number.

![Alt text](https://github.com/lauren1478/School_District_Analysis/blob/main/size%20original.png)

![Alt text](https://github.com/lauren1478/School_District_Analysis/blob/main/size%20no%209th.png)

##### Scores by school type

Though THS is a charter school and we saw that it had a large descrepency against other schools when looking at each individual school. However, the data set may be so large that replacing 9th grade scores does not have an incremental affect on the all charter schools as an aggregate.

![Alt text](https://github.com/lauren1478/School_District_Analysis/blob/main/type%20original.png)

![Alt text](https://github.com/lauren1478/School_District_Analysis/blob/main/type%20no%209th.png)

Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
