# palosebo
Source code for the Gamified Codelabs. Built using Firebase.

##Setting up you gamified codelabs

1. Fork gdgphilippine's repository, `palosebo`
	```
	git fork https://github.com/gdgphilippines/palosebo.git
	```

2. Create a new Firebase app project. 
..a. Go to `https://console.firebase.google.com/` 
..b. Click `Create New Project` 
..c. Fill the details and click `Create Project` 

3. Configure your project. 
..a. Upon opening your new project, click `Add Firebase to your web app` 
..b. Copy the code from the line `var config = {` until `firebase.initializeApp(config);` 
..c. Paste the code in `includes/scripts/config.js` 
..d. Save! 

4. Configure your Firebase app project. 
..a. Authentication 
....i. Go to `Authentication` section on your Firebase console. 
....ii. Click the `Set up Sign-in method`. 
....iii. Enable Google as a sign-in provider. 
....iv. Save! 

..b. Database 
....i. Go to `Database` section on your Firebase module. 
....ii. Under `Data` tab, click the three vertical dots icon and select `Import JSON`. 
....iii. Upload the `database-data.json`. 
....iv. Click `Import`. 

..c. Rules 
....i. Go to `Database` section on your Firebase module. 
....ii. Go to the `Rules` tab. 
....iii. Copy the contents of `database-rules.json`. 
....iv. Paste it to the text editor in Firebase. 
....v. Click `Publish`. 

5. Deploy the app to your website! 

6. Done! 


##Adding a new codelab session