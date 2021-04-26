# BankingSearch

This is a Maven project. 

Tools used: Intellij IDE

Language: Java

Pre - requisits to execute this project: Install Java 8 and above and Maven

How to execute this project?

Method1: 
  1. Download or Clone project from Git HUb.
      git clone git@github.com:bharathmalladi7/BankingSearch.git
      
  2. If you have any IDEs like IntelliJ, Eclipse or VisualStudioCode, open this project and Setup JDK on this project
  
  3. Open file in this path and click on run.
     src/main/java/com/tch/banking/Main.java
     
  4. You will be asked to provide file path for csv.
      Enter CSV file path: 
      
  5. After providing file path, you will be asked to choose filter choice.
      PLEASE SELECT FILTER 
 
     Enter 
      1 for ZIP CODE 
      2 for STATE 
      3 for CITY 
      4 for TYPE 
      5 for BANK NAME 
      6 for  CITY & STATE 
      
   6. Enter your choice. Then you will get the respective filter data after giving filter value. 
      For eg:
      Enter CITY 
      New York
      
      
      ID                    Bank Name             Type                  City                  State                 Zip Code              
      1                     Amazing Bank          Branch                New York              NY                    10018                 
      2                     Neighborhood Bank     Branch                New York              NY                    10020                 
      3                     Friendly Bank         ATM                   New York              NY                    10020                 
      4                     Awesome Bank          Branch                New York              NY                    10021                 
      5                     Amazing Bank          ATM                   New York              NY                    10018 
      
      
      
 Method2: (Command Prompt)
 1. Download this Project.
 2. From Command Prompt or Terminal - go to the directory path which have this jar file. (BankingSearch-1.0-SNAPSHOT.jar). It will be in BankingSearch directory.
 3. Execute below command
    java -jar BankingSearch-1.0-SNAPSHOT.jar
 4. Follow step 4 to 6 in Method1 to get output.
 
