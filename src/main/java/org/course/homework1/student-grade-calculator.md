# Build a Simple Student Grade Calculator 
## Objective:
Create a console-based program that takes student data as input and calculates their average grade, final letter grade, and determines if the student has passed or failed.

### Requirements:

The program should take input for the student's name and grades for 5 subjects.
Grades should be integers between 0 and 100.
Output:

Display the student's name.
Display the average grade for the 5 subjects.
Display the final letter grade based on the following scale:
- `A: 90-100`
- `B: 80-89`
- `C: 70-79`
- `D: 60-69`
- `F: below 60`

Determine if the student has passed or failed:
Pass if average grade is 60 or above.
Fail if average grade is below 60.
##### Program Structure:

Write separate functions (methods) for:
Input collection `(getStudentGrades)`: Use a loop to read grades for 5 subjects and return them in an array.
Calculate average grade `(calculateAverage)`: Takes the array of grades and returns the average.
Determine final letter grade `(getLetterGrade)`: Based on the average grade, return the corresponding letter.
Determine pass/fail status `(isPassed)`: Return `"Pass"` if the average is 60 or above, else `"Fail"`.
Use if-else or switch-case statements for decision-making.
Store the grades in an array.
Use loops to calculate the total and average grades.
##### Constraints:
Ensure that the grades are integers between 0 and 100. Add input validation for this.

#### Excample
- `Enter student's name: Alice`
- `Enter grade for subject 1: 90`
- `Enter grade for subject 2: 85`
- `Enter grade for subject 3: 75`
- `Enter grade for subject 4: 80`
- `Enter grade for subject 5: 95`
 ---------------------
Student: Alice

Average grade: 85.0

Final letter grade: B

Status: Pass
