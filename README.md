# IFs-Issues-Tracking
This repository only holds the list of bugs that have been reported for IFs. Anyone may add a bug report, but please look to see if your issue has already been added!

# Adding an Error Report
1. Go to "issues"
2. Confirm your issue has not already been reported. If it has *not* then continue on.
3. For include the following information in the description of the error:
  1)	Error short description/title
  2)	Date found 
  3)	IFs Version (number, VB6/.NET, Install/Development)
  4)	Person found by
  5)	Type of error (see below)
  6)	Description of error
  7)	Steps to replicate the error, if applicable 
  8)	Attempt to recreate error in VB6 or .NET depending on where found and note whether error reproducible
  9)	Screen shot of error message or anything else that is relevant
  10) Specify what branch you were on. If you were not using IFs through one of our GitHub repositories, then enter "Production"
  11)	Discussion (space for follow-up questions and notes)

4. *ALWAYS* add the "New Issue" label
5. Add any other labels as appropriate, based off their description
6. Submit!

# Example of an Approrpiate Error Report

Example:
1.	Short Description: Error Changing Scenario Parameter

1.1.	Date found: 10/13/20

1.2.	IFs Version: 7.56 .NET Install 

1.3.	Found by: Fizz Buzz

1.4.	Error Type: Blowup

1.5.	Description: Clicking ‘Apply’ after modifying multipliers using the scroll bar generates an error message 

1.6.	Steps to Replicate: 
  1)	Select scenario analysis tab
  2)	Then quick scenario analysis with tree
  3)	On left drop tree: Households/Individuals -> demographic/population -> tfrm (I only selected USA)
  4)	Manually set a change not equal to 1
  5)	Click “Apply”
  6)	Error message appears (see screenshot)

1.7.	Reproducible in VB6 (Y/N): No. There is no ‘Apply’ button in VB6. 

1.8.	Screenshot (If possible, paste text directly so that it can be copied or searched within): (Not Shown Here)

1.9.  Developer Branch

1.10  Discussion: [Intentionally left Blank]

