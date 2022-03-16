# School_District_Analysis
An analysis of school district information regarding preparing all standardized tests for analysis, reporting and presentations to provide information about performance trends and patterns. 

**Overview**

The purpose of this analysis is to assist Maria and her supervisors because they have been notified from the school board of academic dishonesty, specifically reading and match grades for Thomas High School ninth graders. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for assistance. Maria has in turn askeded to replace the match and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once the math and reading scores are replaced, Maria has also requested for the process to be repeated for the school district analysis. 

**Results**
  
_How is the District Summary Affected?_

The district summary is affected when comparing the two data frames from before data management and after data management, there appears to be changes in Percent Passing Math.

  **Before Data Management**
    
*   Average Math Score: 79.0
*   Average Reading Score: 81.9
*   Percent Passing Math: 75
*   Percent Passing Reading: 86
*   Percent of Overall Passing: 65
       
<img width="473" alt="Before Data Management" src="https://user-images.githubusercontent.com/99268646/158287758-9db25dd2-386c-455f-8914-44e07dbca7bb.png">
                         
  **After Data Management**
    
*   Average Math Score: 78.9
*   Average Reading Score: 81.9
*   Percent Passing Math: 74.8
*   Percent Passing Reading: 85.7 
*   Percent of Overall Passing: 64.9
*   For the three counties the results are as follows: 
                
<img width="473" alt="After Data Management" src="https://user-images.githubusercontent.com/99268646/158287809-67f79a74-fa24-4183-badf-1b323fc355c2.png">
 
_How is the School Summary Affected?_

The school summary is affected when comparing the two data frames from before and after data management, there appears to be changes where Thomas High School is ranked based on overall passing. Before data management, Thomas High School is ranked second with a Percent of Overall Passing at 91. After data management, Thomas High School is ranked eighth with a Percent of OVerall Passing at 65. 

<img width="758" alt="School Summary Before Data Management" src="https://user-images.githubusercontent.com/99268646/158649442-ef45d11a-165d-44db-b0a0-cde674c46843.png">

<img width="721" alt="School Summary After Data Management" src="https://user-images.githubusercontent.com/99268646/158649461-708cfefe-7542-4d1f-9048-6f7f52742360.png">


_How Does Replacing the Ninth Graders' Math and Reading Scores Affect Thomas High School's Performance Relative to the Other Schools?_

As stated previously, when the ninth grade math and reading scores are corrected for Thomas High School, when compared to other schools, the school drops in ranking from second to eigth. 

_How Does Replacing the Ninth-Grade Scores Affect the Following:_
    
*   Math and reading scores by grade:
    *    Math and reading scores from Thomas High School 9th grade are set to NaN and equivalent to 0
    *    When removing ninth-grade scores from Thomas High School, Percent Passing Math, Percent Passing Reading and Percent Overall Passing all decreased giving evidence of academic dishonesty
*   Scores by school spending:
    *    Thomas High School fell into a smaller bin of spending between "$630-644"

<img width="653" alt="School Budget" src="https://user-images.githubusercontent.com/99268646/158658388-e3b5ff67-f8c1-48bb-b531-65bdad67c4d7.png">


*   Scores by school size:
    *    The student count for Thomas High School changed drastically with the count being 1635 before data management and 1174 after data managment. A change in count of "-461"  

<img width="260" alt="Student Count Before Data Management" src="https://user-images.githubusercontent.com/99268646/158657675-f7653eae-f32b-4738-8ad3-5ac12c54214a.png">

<img width="721" alt="School Summary After Data Management" src="https://user-images.githubusercontent.com/99268646/158657700-a3f2be67-219a-47e9-b86e-c739d8ebcdd1.png">
 
*   Scores by school type:
    *    Thomas High School is a "Charter" type school. While removing the ninth-grade scores does not affect the type of school Thomas High School is, it does impact the school by being a charter school and most likely receiving a secondary funding source, criteria must be met and these decreases in scores is likely to impact grant opportunities. Because of the decrease in Percent Passing Math, Percent Passing Reading, and Percent Overall Passing it dropped the school in rankings compared to other charter schools and may impact secondary funding opportunities. 

<img width="116" alt="School Type" src="https://user-images.githubusercontent.com/99268646/158657962-5e5b6da1-e884-435e-9eff-f180406303cf.png">


**Summary**


