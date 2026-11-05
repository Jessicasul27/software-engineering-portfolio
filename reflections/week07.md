&#x20;**Week 7 Research Lab** **- Software Measurement**



**Task 1**

1. **CC = 14 + 1 = 15; 15>10:** This means the code exceeds McCabes threshold and suggests redesign. The code may be harder to test, understand and maintain due to the cyclomatic complexity.

2. **Three destination branches (LOCAL / NATIONAL / international) each repeat the same 'three weight tiers' pattern:** a duplication smell, even though the exact numbers differ (Internal Attribute).

**Unclear variable names:** wt, dest, p, q are all unclear variable names in the parameters list. This contributes to the code complexity in terms of understanding/ maintainability of code (Human judgement).

**No handling for input validation:** There is no input validation for the values entered by the user that is being passed in the parameter list (Internal Attribute).

**No error handling:** As a result of no input validation, there is no user-friendly error message if something goes wrong in terms of input validation for example (Internal Attribute).



&#x09;

**Task 2**

1. **System A: 45/30 = 1.5 defect density; 1.5 < 2** 
2. **System B: 15/6 = 2.5 defect density; 2.5 > 2**



System A may be considered better as it has a defect density of less than 2. 



However defect density has its limitations as: 

* There is no consensus on what constitutes a defect. To make comparisons all parties must count the same way.
* There is no consensus as to how to measure software size.
* Defect density is derived from the process of finding defects. It may therefore tell us more about this process rather than the product quality itself. 



&#x09; 

