# School_District_Analysis

## Analysis Overview

Due to alleged academic dishonesty at Thomas High School, our previous analysis of the school district reading and math scores needed to be redone. Specifically, the reading and math scores of the Thomas High School 9th graders was factored out, and the required reports recalculated. The following analysis will examine how the exclusion of these grades affected the reports, and summarize these changes. 

## Results 

* **District Summary Changes**

  **Original Analysis**
  ![District Summary](https://user-images.githubusercontent.com/81761879/118407907-e6c15180-b650-11eb-8e02-c5b5f9dce0e8.PNG)
  
  **Reanalysis**
  ![District Summary THS Out](https://user-images.githubusercontent.com/81761879/118407926-fb9de500-b650-11eb-8de5-331723ec043a.PNG)
 
  *  As evident in the images above, factoring out THS 9th graders very slightly reduced all score and passing % calculations with the exception of Average Reading Score which remained unchanged 

* **School Summary Changes

  **Original Analysis
  ![School Summary](https://user-images.githubusercontent.com/81761879/118408486-d78fd300-b653-11eb-8a29-75640d2905c1.PNG)
  
  **Reanalysis
  ![School Summary THS Out](https://user-images.githubusercontent.com/81761879/118408519-f4c4a180-b653-11eb-9c34-dcde43c139d9.PNG)

  * Overall, the elimination of THS 9th graders scores did not drastically affect the school summary output, as shown above. Thomas High School remained in 3rd place in terms of Overall Passing %. 
  * However, they did drop from 2nd to 3rd place in terms of Passing Reading %, even though their Average Reading Score went up very slightly after recalculating.  

* **Scores by grade 

  * The output of average reading and math scores by grade was virtually unchanged from the initial run, with the exception that THS 9th graders scores for math and reading were replaced with "nan" to indicating a null value. No data was changed other than that representing THS 9th graders scores. Therefore this summary remains otherwise unchanged. 

* **Scores by school spending

  **Original Analysis
  ![SPending](https://user-images.githubusercontent.com/81761879/118410000-4290d800-b65b-11eb-9f1d-b76ad12e69e5.PNG)
  
  **Reanalysis 
  ![spending THS Out](https://user-images.githubusercontent.com/81761879/118410007-4ae91300-b65b-11eb-9059-e3640bb8424f.PNG)

  * As we can see above, factoring out the THS 9th graders scores resulted in a significant drop in the % passing math (-6%), % Passing Reading (-7%), and % Overall Passing (-7%) for the spending bracket of $630-644, of which Thomas High School is a member. 

* **Scores by School Size 

  **Original Analysis
  ![School size](https://user-images.githubusercontent.com/81761879/118410109-d2368680-b65b-11eb-9001-f937b4a40457.PNG)

  **Reanalysis 
  ![School size THS out](https://user-images.githubusercontent.com/81761879/118410112-d4004a00-b65b-11eb-879d-10aef445ac3d.PNG)

  * Unsurprisingly  and as predicted, the "Medium" school size bracket saw significant reductions in % Passing math (-6%), % Passing Reading (-6%), and % Overall Passing (-6%) when THS 9th grader scores were factored out. 

* **Scores by School Type

  **Original Analysis
  ![school type](https://user-images.githubusercontent.com/81761879/118410242-77e9f580-b65c-11eb-956f-cd9e523eee81.PNG)

  **Reanalysis 
  ![school type THS out](https://user-images.githubusercontent.com/81761879/118410249-80423080-b65c-11eb-99a1-0f18e38beaa4.PNG)

  * In line with previous results, "Charter" type schools saw reductions in % Passing math (-4%), % Passing Reading (-4%), and % Overall Passing (-3%) as a result of removal of the THS 9th graders' scores. 

## Summary

In summation, the removal of Thomas High School 9th graders' math and reading scores had an invariable affect across the board. Specifically, for the district summary, score averages and passing %'s were reduced but very minimally as the amount of data removed was not significant compared to the overall amount of data originally in the set. More telling, we saw Thomas High School rankings drop in the school summary report in terms of % passing Math. In addition, for any grouping of schools that included Thomas High School in their bins, we saw a reduction in % passing scores commensurate with the overall influence of Thomas High School as a function of its relative size within that grouping. 
  
