# Project Goal
The year is 2019 and some schools in California are struggling with performance. The state wants to create a program to benefit 10% of students selecting the largest underperforming schools. This project aims to identify schools for the state to optimize the state resources' allocation to improve performance metrics, based on their scores in standardized tests.

# Summary
Standardized tests have the purpose of evaluating students equally. SAT and ACT are the standardized tests largely applied in the United States. These tests are designed to assess college readiness, while grade 12 is the culmination of a student's high school education. For this reason, this project uses standardized reported scores of students in grade 12 to evaluate a schools' performance.

The datasets used in this project have data from school-level to state-level. To retain most information, school-level data were first filtered and agreggated from that as necessary. Overall in the state, SAT is predominant over ACT, but this pattern changes in some schools. Both datasets add to 1990 rows representing schools' data, where SAT was predominant in 1783 and ACT was predominant in 207.

To evaluate performance, I considered the composite scores of both tests, not discriminating between different sections of the tests. The composite score for each school was represented by the percentage of students who achieved the benchmark set for each test. Some schools did not present score, they were minority and were also smaller in enrollment size. 

Performance of the school was compared to the median of the state to define which were underperforming and which were not. After selecting the underperforming schools, they were sorted by enrollment size and selected until the group reached 10% of students in the state.



# Conclusions
In the end, there were 65 schools selected, accounting for approximately 42 thousand students, located in 12 counties and 38 districts. Los Angeles was by far the largest county in terms of enrollment, followed by San Bernardino, which was almost 3x smaller, followed by Riverside, Orange, Ventura, Kern, San Diego, Fresno, Contra Costa, Monterey, Sacramento and Madera.

# Next Steps
- Check the ratio of ACT and SAT benchmark achievement, to check if students achieve the benchmarks at similar rates. If so, these two benchmarks are comparable in the way shown in this project.
- Have a closer look at schools that were not considered in this project due to score absence, but that could have a reasonable amount of students.
- If a more specific approach is desired for resources' allocation, on suggestion is to discriminate between scores in different sections of these tests.
