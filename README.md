# first-mobile-app-project
An e wallet mobile application exclusively for TIP staffs and students only.
To view the actual code navigate to App.js file..

Issues: 
-No proper backend for login page which restricts users to access the home page if they entered an invalid account. 
-Balance data of the user does not persists. In other words, no database for balances. {Our goal should be whenever the user log in their account, they were still able to see their current balance.}
-Add balance and Withdraw bug. For add balance, the current balance returns null if the user doesn't specify the amount they want to add. For withdraw, the current balance returns negative number so even if the current balance is less than the amount they want to withdraw, the current balance will still update. {I tried to implement a conditional statement for that but it doesn't work}
-No database for report problem which actually save the records for the user who submitted a report.
