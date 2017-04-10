# E-Polling-System

Description:
An E-Polling system built based on the national elections of Bangladesh.
Technologies used:
1. Programming Language: C#
2. Database: Oracle 10g Express Edition
3. Architecture: N-Tier


Instructions:
1. Install Oracle Database before using. Version 10g is preferred as we developed the system with 10g Express Edition.
2. See the SQL COMMANDS.txt file to create the tables as required.
3. In EPollingSystem.DAL project, goto DatabaseHandler class and change the connection string as required.
4. Set EPollingSystem.UI as the starting project after opening the solution with EPollingSystem.sln
5. Default UserId: "admin", Password: "admin" (without quotes, for admin account)
6. Once you enter centers, the CenterId becomes the UserId for that center.
