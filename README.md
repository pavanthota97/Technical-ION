# Technical-ION
**Sessions**
Maintain Session	-->	1
Update Session		-->	2
Charts/Pie Session	-->	3
Print Session		-->	4
Display Session		-->	5


**Window Types**  -- **8** Types

	--> List Window
 	--> Dialog Window
  	--> Synchronized Dialog
  	--> Modeless Window with menu
   	--> MOdal Window with menu
    	--> Wizard
     	--> Parameter
      	--> Multi Main Table

**Synchroniztion** 2 Types of synchronization
 			1.Dialog Synchroniztion
    			2.Child Synchronization



**Main Table**              **Session**         **Session Type**      **Standard Commands**           **Window types**
    tctrn900             tctrn9500m000                    5                   44                        List Window   
    tctrn900             tctrn9400m000                    4                   44                        List Window   
    tctrn900             tctrn9200m000                    2                   21                        Dialog Window   
    tctrn900             tctrn9100m000                    1                   21                        Dialog Window   



**tctrn9500m000**    Session Code

**tc**     --- Package
**trn**    --- Module
**9500**   --- Table Code with Session Type


**Form Commands**  If we select a record and click on the action, that is referred to as a "form command."
**Form fiels**    The fields that are not in the table are called form fields.

	Types of synchronization
 			1.Dialog Synchroniztion
    			2.Child Synchronization


**synchronized** Opening of one Session through another session **or** Opening of child session from parent session.

**Syntax for Dialog Synchronization**              before.program:
	set.synchronized.dialog("tctrn9100m000",false,false)

 **Script Types**	**8** Types
		--> UI Script with Database Handling
  		--> UI Script for Print/Processing Session
    		--> 3GL(Without 4GL Engine)
      		--> General Library
		--> Integration DALL
  		--> DAL
    		--> DAL(Version 2)
      		--> Business Object Layer
**To Know how many ENUM/Set in the DOMAIN for the Particular Table Field Enumerated** 
	Select Domains
 	Click on Specific
  	Enum/set Data
   	<img width="552" alt="image" src="https://github.com/pavanthota97/Technical-ION/assets/106645385/13ba41e7-ae95-46f3-951b-9ebc4bf18b16">

 	

 **Program Script**

 	Declaration section
  	program Section
   	field Section
   	group section
    

**Shortcuts BECS**
--> To know the Table information (Ctrl + '0')
--> In BECS Environment to know the programmers mode (Shift '+' 8)
--> (Ctrl'+'B) is for zoom.
--> Spacebar to view the CONTROL	BROWSE	MODIFY	FORM	MISCELLANEOUS	APPLICATOIN in the GTI(General Table Informatoin).
--> To View details of the Properties (Shift + Ctrl + '8')
-->To Search in the Program script (Ctrl + 'F3')

