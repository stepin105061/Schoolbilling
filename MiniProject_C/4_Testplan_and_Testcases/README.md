TEST PLAN

In the software development project, errors can be injected at any stage during development. There are different techniques for detecting and eliminating errors that originate in that phase. However, no technique is perfect, and it is expected that some of the errors of the earlier phases will finally manifest themselves in the code. This is particularly true because in the earlier phases and most of the verification techniques are manual because no executable code exists. ultimately those remaining errors will be reflected on the code. Hence, the code developed during the coding activity is likely to have some requirement errors and design errors, in addition to errors introduced during the coding activity. Behaviour can be observed, testing is the phase where the errors remaining from all the previous phases must be detected. Hence, testing performs a very critical role for quality assurance and for ensuring the reliability of the software.

 During testing the program to be tested is executed with a set of test cases, and the output of the program for the test case is evaluated to determine. If the programme is performing as expected. Due to its approach, dynamic testing can only ascertain the presence of errors in the programme, the exact nature of the errors is not usually decided by testing. Testing forms the first step in determining the errors in a program. Clearly the success of testing in revealing errors in programs depends critically on the test cases.

 Testing a large system is a very complex activity, and like any complex activity it has to be broken into smaller activities. Due to this, for a project, incremental testing is generally performed, in which components and subsystems of the system are tested separately before integrating them to form the system for system testing. This form of testing, though necessary to ensure quality for a large system, introduces new issues of how to select components for testing and how to combine them to form a subsystem and system 


TEST CASE

Data structures have been used effectively to handle co-related functions and store the record, Data structures required are:
      
 struct dat - to store the date(month and day) of entry of records.  
      
 struct student - to store and organise the record of individual students.
 
 struct teacher - to store and organise the record of individual teachers/staff.
    
 Different functions are used for performing different billing operation in the school billing system.

 NO OF TEST CASES:

 Test case  1

  FUNCTIONS   : start()

  DESCRIPTION : Shows the account selection screen.
         
  STATUS      : Pass.

 TEST CASE  2

  FUNCTIONS   : chkdat()
  
  DESCRIPTION : For checking date.
  
  Status      : Pass.
  
 TEST CASE  3

  FUNCTIONS   : addrec()
  
  DESCRIPTION : For adding records.
  
  STATUS      : Pass.
 
 TEST CASE  4

  FUNCTIONS   : modrec()

  DESCRIPTION : For modifying records.

  STATUS      : Pass.

 TEST CASE  5

  FUNCTIONS   : searchrec()

  DESCRIPTION : For searching records.

  STATUS      : Pass.

 TEST CASE 6

  FUNCTIONS   : delrec()

  DESCRIPTION : For deleting records.

  STATUS      : Pass.

 TEST CASE  7

  FUNCTIONS   : fee()

  DESCRIPTION : For recording the fee paid and displaying fine, due,total and advance.

  STATUS      : Pass.

 TEST CASE  8

  FUNCTIONS   : salary()

  DESCRIPTION : For calculating the salary of teachers and staff.

  STATUS      : Pass.

