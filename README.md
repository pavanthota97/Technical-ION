# Technical-ION
**Window Types**  -- **8** Types

	--> List Window
 	--> Dialog Window
  	--> Synchronized Dialog
  	--> Modeless Window with menu
   	--> MOdal Window with menu
    	--> Wizard
     	--> Parameter
      	--> Multi Main Table
       


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

 

**Shortcuts BECS**
--> To know the Table information (Ctrl + '0')
--> In BECS Environment to know the programmers mode (Shift '+' 8)
--> (Ctrl'+'B) is for zoom.
--> Spacebar to view the CONTROL	BROWSE	MODIFY	FORM	MISCELLANEOUS	APPLICATOIN in the GTI(General Table Informatoin).
