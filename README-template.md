# California Education in Different Counties

The objective of this work is to identify underperforming counties in California, considering metrics such as students' standardized tests scores, and central tendencies of the states, to better allocate education resources.



# Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|CCode|float|sat_ca|County code| 
|SCode|float|sat_ca|School code| 
|RType|object|sat_ca|'S' if school 'C' if county| 
|CName|object|sat_ca|County name| 
|SName|object|sat_ca|School name| 
|Enroll12|float|sat_ca|Number of students enrolled in 12th grade| 
|NumTSTTakr12|float|sat_ca|Numbers of students who took the test| 
|PctBothBenchmark12|object|sat_ca|Percentage of students that met or exceeded both benchmarks| 
|PctTakr|float|sat_ca|Percentage of enrolled students that took the test| 
|CCode|float|act_ca|County code| 
|RType|object|act_ca|'S' if school 'C' if county| 
|CName|object|act_ca|County name| 
|Enroll12|float|act_ca|Students enrolled in 12th grade| 
|NumTstTakr|float|act_ca|Number of students that took the test| 
|CCode|float|sat_counties|County code| 
|SCode|float|sat_counties|School code| 
|RType|object|sat_counties|'S' if school 'C' if county| 
|SName|object|sat_counties|School name| 
|CName|object|sat_counties|County name| 
|Enroll12|float|sat_counties|Number of students enrolled in 12th grade| 
|NumTSTTakr12|float|sat_counties|Numbers of students who took the test| 
|PctBothBenchmark12|object|sat_counties|Percentage of students that met or exceeded both benchmarks| 
|PctTakr|float|sat_counties|Percentage of enrolled students that took the test| 
|NumTstTakr|float|act_counties|Number of students that took the test| 
|CCode|float|act_counties|County code| 
|RType|object|act_counties|'S' if school 'C' if county| 
|Enroll12|float|act_counties|Number of students enrolled in 12th grade| 
|CName|object|act_counties|County name| 
|test_takers|float|sat_test_takers|Number of test takers| 
|test|object|sat_test_takers|Which test| 
|test_takers|float|act_test_takers|Number of test takers| 
|test|object|act_test_takers|Which test| 
|test_takers|float|test_takers_df|Number of test takers| 
|test|object|test_takers_df|Which test| 
|CName|object|test_takers_df|County name| 
|CCode|float|sat_schools|County code| 
|SCode|float|sat_schools|School code| 
|RType|object|sat_schools|'S' if school 'C' if county| 
|CName|object|sat_schools|County name| 
|SName|object|sat_schools|School name| 
|Enroll12|float|sat_schools|Number of students enrolled in 12th grade| 
|NumTSTTakr12|float|sat_schools|Numbers of students who took the test| 
|PctBothBenchmark12|float|sat_schools|Percentage of students that met or exceeded both benchmarks| 
|PctTakr|float|sat_schools|Percentage of enrolled students that took the test| 
|CCode|float|sat_reported|County code| 
|SCode|float|sat_reported|School code| 
|RType|object|sat_reported|'S' if school 'C' if county| 
|CName|object|sat_reported|County name| 
|SName|object|sat_reported|School name| 
|Enroll12|float|sat_reported|Number of students enrolled in 12th grade| 
|NumTSTTakr12|float|sat_reported|Numbers of students who took the test| 
|PctBothBenchmark12|float|sat_reported|Percentage of students that met or exceeded both benchmarks| 
|PctTakr|float|sat_reported|Percentage of enrolled students that took the test| 
|CCode|float|sat_reported_counties|County code| 
|SCode|float|sat_reported_counties|School code| 
|RType|object|sat_reported_counties|'S' if school 'C' if county| 
|CName|object|sat_reported_counties|County name| 
|SName|object|sat_reported_counties|School name| 
|Enroll12|float|sat_reported_counties|Number of students enrolled in 12th grade| 
|NumTSTTakr12|float|sat_reported_counties|Numbers of students who took the test| 
|PctBothBenchmark12|float|sat_reported_counties|Percentage of students that met or exceeded both benchmarks| 
|PctTakr|float|sat_reported_counties|Percentage of enrolled students that took the test|
|CCode|float|first_quad|County code| 
|SCode|float|first_quad|School code| 
|RType|object|first_quad|'S' if school 'C' if county| 
|CName|object|first_quad|County name| 
|SName|object|first_quad|School name| 
|Enroll12|float|first_quad|Number of students enrolled in 12th grade| 
|NumTSTTakr12|float|first_quad|Numbers of students who took the test| 
|PctBothBenchmark12|float|first_quad|Percentage of students that met or exceeded both benchmarks| 
|PctTakr|float|first_quad|Percentage of enrolled students that took the test|
|CCode|float|fourth_quad|County code| 
|SCode|float|fourth_quad|School code| 
|RType|object|fourth_quad|'S' if school 'C' if county| 
|CName|object|fourth_quad|County name| 
|SName|object|fourth_quad|School name| 
|Enroll12|float|fourth_quad|Number of students enrolled in 12th grade| 
|NumTSTTakr12|float|fourth_quad|Numbers of students who took the test| 
|PctBothBenchmark12|float|fourth_quad|Percentage of students that met or exceeded both benchmarks| 
|PctTakr|float|fourth_quad|Percentage of enrolled students that took the test|


# Executive Summary

For students' performance, SAT data was chosen because of the students' coverage. SAT is more used in California than ACT.
No significant relationship between the variables available and students' performance were seen.
Schools were divided in 4 quadrants, having more or less than enrollment median and/or more or less than the percentage of both benchmarks met or exceeded.
The quadrant underperforming and with more enrollment students than the median was analyzed in county level.
Then, the quadrant underperforming and with less enrollment students than the meadian was also analyzed in a county level.
The suggestion is to invest more in Los Angeles, Riverside, San Bernardino, Orange, Kern, San Diego, Fresno, Sacramento, Monterey and Ventura, and then the other ones that are smaller but equally underperforming, that is, Contra Costa, Alameda, Tulare and Santa Clara
