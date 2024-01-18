## To run the application, follow these steps: 
<ul>
  <li>Open your command prompt or terminal.</li>
  <li>In the terminal, navigate to the directory path of the TIPCash folder on your local machine using the "cd" command followed by the location path.</li>
  <li>Once you've located the folder, ensure that npm is already installed. If not, type <b>"npm install"</b> in the terminal. Additionally, install the Expo CLI globally by running " <b>npm install --global expo-cli".</b></li>
  <li>Finally, choose the platform on which you want to run the application. If you prefer to run it on the web, type "npm run web" in the terminal. If you want to run it on a mobile device, type "npm run android".</li>
</ul>

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


Run it using android studio code.. 
