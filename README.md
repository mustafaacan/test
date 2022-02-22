## This file includes some information about USER INTERFACE SPECIFICATION 

>YOU CAN FIND RELATIVE INFORMATION ABOUT 2 SECTIONS OF THE REGISTER PAGE, 2 BUTTON AND 1 CLICK SCENARIOS BELOW 




### **1) NEW USER BUTTON**

  - Type: Button
  - Requirement: Before New User Register
  - Dependencies: USER REGISTER INFORMATION PANEL
  - Role: Creating Empty USER REGISTER INFORMATION PANEL



### **2) HIDE DISABLED USER CLICK**

  - Type: Click / Boolean (Filled: True / Not Filled: False)
  - Requirement: Required 
  - Dependencies: USER REGISTER TABLE 
  - Role: To hide the disabled users on the USER REGISTER TABLE  


### **3) SAVE USER BUTTON**

  - Type: Button
  - Requirement: Filling Required Section on USER REGISTER INFORMATION PANEL
  - Dependencies: USER REGISTER INFORMATION PANEL
  - Role: Saving User Information to the Database



### **4) USER REGISTER TABLE**

>ID section will be specified as **Primary Key**

>Allignments starts from **left** to **right**



  A) ID SECTION
  
  - Type: Integer
  - Requirement: Required
  - Specified Form: 
  - Dependencies: HIDE DISABLED USER CLICK
  - Obtaining Way: Will be automatically added when new user added
  
  
   B) USER NAME SECTION
  
  - Type: String / Text
  - Requirement: Required
  - Specified Form: 
  - Dependencies: HIDE DISABLED USER CLICK
  - Obtaining Way: Will be pulled from the user database


   C) EMAIL SECTION
  
  - Type: String / Text
  - Requirement: Required
  - Specified Form: Must be in the mail form
  - Dependencies: HIDE DISABLED USER CLICK
  - Obtaining Way: Will be pulled from the user database


   D) ENABLED SECTION
  
  - Type: Boolean
  - Requirement: Required
  - Specified Form: True / False
  - Dependencies: HIDE DISABLED USER CLICK
  - Obtaining Way: HIDE DISABLED USER CLICK





### **5) USER REGISTER INFORMATION PANEL**

>All information will be taken directly from user

>Allignments starts from **top** to **bottom**



  A) USERNAME SECTION
  
  - Type: String / Text
  - Requirement: Required
  - Specified Form:  
  - Dependencies: NEW USER BUTTON / SAVE USER BUTTON
  - Obtaining Way: Will be pulled from the user


  B) DISPLAY NAME SECTION
  
  >> This information will be added to **REGISTER TABLE**
  
  - Type: String / Text
  - Requirement: Required
  - Specified Form: 
  - Dependencies: NEW USER BUTTON / SAVE USER BUTTON
  - Obtaining Way: Will be pulled from the user

  
   C) PHONE SECTION
  
  - Type: Integer
  - Requirement: Not Required
  - Specified Form:  
  - Dependencies: NEW USER BUTTON / SAVE USER BUTTON
  - Obtaining Way: Will be pulled from the user


   D) EMAIL SECTION
  
  >> This information will be added to **REGISTER TABLE**
  
  - Type: String / Text
  - Requirement: Required
  - Specified Form: Must be in the mail form 
  - Dependencies: NEW USER BUTTON / SAVE USER BUTTON
  - Obtaining Way: Will be pulled from the user


   E) USER ROLE SECTION
  
  - Type: String / Text
  - Requirement: Required
  - Specified Form: 
  - Dependencies: NEW USER BUTTON / SAVE USER BUTTON
  - Obtaining Way: Selection (Guest, Admin, Superadmin) 



   F) ENABLED SECTION
   
   >> This information will be added to **REGISTER TABLE**
  
  - Type: Boolean
  - Requirement: Required
  - Specified Form: True / False
  - Dependencies: NEW USER BUTTON / SAVE USER BUTTON
  - Obtaining Way: Clicking (Filled: True / Not Filled: False) 
   


