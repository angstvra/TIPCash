#TIPCash
An e wallet mobile application exclusively for TIP staffs and students only.
To view the actual code navigate to App.js file..

**Issues: **
1. No proper backend for login page which allows to access the home page even without entering their account data. 
2. Balance data is not saving. No database to hold the balance.
3. Add balance and withdraw is not functioning properly. For add balance, the current balance returns null if the user didn't specify any amount. For withdraw, the current balance returns negative number. I tried implementing a conditional checking whenever user tries to withdraw an amount that is greater than the balance but it is not working. 
4. Report problem doesn't really have functionality.


**Goals: **
1. Program should have database to holds user acocunts
2. Balance data should also connected to the database based on the specific user. 
3. Implements checking whether if the user tries to add null amount or withdraw amount that is greater than the balance. 
4. Report problem must notify admin whenever user sends an issue regards in the app. 

