## This file includes some information about USER INTERFACE SPECIFICATION 

>YOU CAN FIND RELATIVE INFORMATION ABOUT 2 SECTIONS OF REGISTER PAGE BELOW 



### **1) USER REGISTER TABLE**

>All information will be pulled from the user databases

>ID section will be specified as **Primary Key**

>Allignments starts from **left** to **right**



  A) ID SECTION
  
  - Type: Integer
  - Requirement: Required
  - Specified Form: 
  - Obtaining Way: Will be automatically added when new user added
  
  
   B) USER NAME SECTION
  
  - Type: String / Text
  - Requirement: Required
  - Specified Form: 
  - Obtaining Way: Will be pulled from the user database


   C) EMAIL SECTION
  
  - Type: String / Text
  - Requirement: Required
  - Specified Form: must be in the mail form
  - Obtaining Way: Will be pulled from the user database


   D) EMAIL SECTION
  
  - Type: Boolean
  - Requirement: Required
  - Specified Form: True/False
  - Obtaining Way: Will be pulled from the user database







### **2) USER REGISTER INFORMATION PANEL**

>All information will be taken directly from user

>Allignments starts from **top** to **bottom**



  A) USERNAME SECTION
  
  - Type: String/Text
  - Requirement: Required
  - Specified Form:  
  - Obtaining Way: Will be pulled from the user


  B) DISPLAY NAME SECTION
  
  >> This information will be added to **REGISTER TABLE**
  
  - Type: String/Text
  - Requirement: Required
  - Specified Form: 
  - Obtaining Way: Will be pulled from the user

  
   C) PHONE SECTION
  
  - Type: Integer
  - Requirement: Not Required
  - Specified Form:  
  - Obtaining Way: Will be pulled from the user


   D) EMAIL SECTION
  
  >> This information will be added to **REGISTER TABLE**
  
  - Type: String / Text
  - Requirement: Required
  - Specified Form: Must be in the mail form 
  - Obtaining Way: Will be pulled from the user


    E) USER ROLE SECTION
  
  - Type: String / Text
  - Requirement: Required
  - Specified Form: 
  - Obtaining Way: Selection (Guest, Admin, Süperadmin) 

    F) ENABLED SECTION
  
  - Type: Boolean
  - Requirement: Required
  - Specified Form: True / False
  - Obtaining Way: Clicking (Filled: True / Not Filled: False) 
   


