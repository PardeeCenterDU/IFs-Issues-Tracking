# IFs-Issues-Tracking
This repository only holds the list of bugs that have been reported for IFs. Anyone may add a bug report, but please look to see if your issue has already been added!

# Adding an Error Report
1. Go to "issues"
2. Confirm your issue has not already been reported. If it has *not* then continue on.
3. Click on "New Issue"
4. Please include the following information in the description of the error (Filled Out Example is Below):
    1)	Short Description of the Error / Restate of the title
    2)	Date found 
    3)	IFs Version (number, VB6/.NET, Install/Development)
    4)	Person found by
    5)	Type of error (see below) [This should also be an attached label]
    6)	Description of error - Long form and additional details beyond what is in the title
    7)	Steps to replicate the error, if applicable 
    8)	Attempt to recreate error in VB6 or .NET depending on where found and note whether error reproducible
    9)	Screen shot of error message or anything else that is relevant
    10) Specify what branch you were on. If you were not using IFs through one of our GitHub repositories, then enter "Production"
    11)	Discussion (space for follow-up questions and notes)

4. *ALWAYS* add the "New Issue" label
5. *ALWAYS* add Coryv221 and Solox1 as "Assignees"
6. Add any other labels as appropriate, based off their description
7. Submit!

# Example of an Appropriate Error Report

Example:
1.	Short Description: Error Changing Scenario Parameter

2.	Date found: 10/13/20

3.	IFs Version: 7.56 .NET Install 

4.	Found by: Fizz Buzz

5.	Error Type: Blowup

6.	Description: Clicking ‘Apply’ after modifying multipliers using the scroll bar generates an error message 

7.	Steps to Replicate: 
      1)	Select scenario analysis tab
      2)	Then quick scenario analysis with tree
      3)	On left drop tree: Households/Individuals -> demographic/population -> tfrm (I only selected USA)
      4)	Manually set a change not equal to 1
      5)	Click “Apply”
      6)	Error message appears (see screenshot)

8.	Reproducible in VB6 (Y/N): No. There is no ‘Apply’ button in VB6. 

9.	Screenshot (If possible, paste text directly so that it can be copied or searched within): (Not Shown Here)

10.  Developer Branch for Model, SQLite Branch for GUI

11.  Discussion: [Intentionally left Blank]

