# School District Analysis
## Overview
Maria was tasked by the school board to analyze student test results and look for trends based on student grade, school budget, school size, and school type to help the board make decisions on the school's budgets. After we created the analysis model the school board informed us that there was evidence of academic dishonesty in one of the school's 9th grade class. Until more information could be gathered on the possible academic dishonesty the board asked us to emit all test scores for these students and rerun the results. Below we will discuss results and how the results were affected by the emitted scores.

## Results

### How is the district summary affected?
Overall, the averages of the student grades and the percentage passing did not change much after the Thomas High School ninth grade scores were removed:

  - average math score is 0.1 lower
  - % passing math is 0.2% lower
  - % passing reading is .03% lower
  - % overall passing is 0.1% lower

#### Table 1. District Outcomes Original
![district summary 1](https://user-images.githubusercontent.com/57120024/159135792-0cbe855b-b9d6-4971-a402-1b9893f5e142.png)

#### Table 2. District Outcomes Updated
![district summary 2](https://user-images.githubusercontent.com/57120024/159135798-bbb783a8-d6f9-42c0-a15e-88e2c0291960.png)

### How is the school summary affected?
The school summary only changed for Thomas High School increasing the average grades and percentage passing

#### Table 3. School Summary Original
![school summary 1](https://user-images.githubusercontent.com/57120024/159135874-592b0fc6-01de-41bb-92d3-69cb6963431e.png)

#### Table 4. School Summary Updated
![school summary 2](https://user-images.githubusercontent.com/57120024/159135878-3475e13a-61bd-442c-b225-693af1f701a9.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Thomas High School went from being the 2nd ranked school to the top performing school in the district

#### Table 5. Top Performing Schools Original
![top school 1](https://user-images.githubusercontent.com/57120024/159135931-044eb844-676c-4a26-a028-96cedddfcced.png)

#### Table 6. Top Performing Schools Updated
![top school 2](https://user-images.githubusercontent.com/57120024/159135934-92831829-74c0-486b-a0af-fede66c8a160.png)


The emiting of the Thomas High school ninth grade scores and affected the following:
  - Math and reading scores by grade
      - Thomas High School ninth grade results now show "nan"
      #### Table 7. Math Scores by Grade Original 
      ![math scores by grade 1](https://user-images.githubusercontent.com/57120024/159136002-a0ebdfdd-f048-42f5-9647-99576deab999.png)
      #### Table 8. Math Scores by Grade Updated
      ![math scores by grade 2](https://user-images.githubusercontent.com/57120024/159136008-478eeef7-18f1-4cda-8301-6e3705623451.png)
      #### Table 9. Reading Scores by Grade Original 
      ![reading scores by grade 1](https://user-images.githubusercontent.com/57120024/159136012-5ca728a4-d410-457f-b356-c9962dccdd32.png)
      #### Table 10. Reading Scores by Grade Updated
      ![reading scores by grade 2](https://user-images.githubusercontent.com/57120024/159136015-1b004eb9-bc69-4732-84cb-68ebf8c87b6d.png)

  - Scores by school spending
      - No changes were seen after rounding
      #### Table 11. Scores by School Spending per Student Original
      ![scores by school spending 1](https://user-images.githubusercontent.com/57120024/159136110-3a19bed6-6246-44b4-b64e-19c8bff37e04.png)
      #### Table 12. Scores by School Spending per Student Updated
      ![scores by school spending 2](https://user-images.githubusercontent.com/57120024/159136114-75302897-2303-4f2f-93ca-ba22222e93dd.png)

  - Scores by school size
       - No changes were seen after rounding
      #### Table 13. Scores by School Size Original
      ![scores by school size 1](https://user-images.githubusercontent.com/57120024/159136125-27300db2-340a-4a34-aef5-9007802a2e25.png)
      #### Table 14. Scores by School Size Updated
      ![scores by school size 2](https://user-images.githubusercontent.com/57120024/159136128-635667bf-6d25-4cbc-a034-84e8d3bf051e.png)


  - Scores by school type
       - No changes were seen after rounding
      #### Table 14. Scores by School Type Original 
      ![scores by school type 1](https://user-images.githubusercontent.com/57120024/159136130-c9e92dd2-7436-4532-961e-cd343b1fe0cb.png)
      #### Table 15. Scores by School Type Updated
      ![scores by school type 2](https://user-images.githubusercontent.com/57120024/159136141-0a6be767-60b6-46bd-ad25-fea21f0cb5a5.png)

## Summary

The major changes seen from replacing the Thomas High School ninth grade scores with NaNs are, decrease in overall district scores, Thomas High School overall all scores increasing, Thomas High Sshool becoming the highest ranked school in terms of overall passing percentage, and minimal changes not really seen in other metrics due to rounding. 

