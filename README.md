# palosebo
Source code for the Gamified Codelabs. Built using Firebase.

##Setting up you gamified codelabs

1. Fork gdgphilippine's repository, `palosebo`
	```
	git fork https://github.com/gdgphilippines/palosebo.git
	```

2. Create a new Firebase app project. 
  1. Go to `https://console.firebase.google.com/` 
  2. Click `Create New Project` 
  3. Fill the details and click `Create Project` 

3. Configure your project. 
  1. Upon opening your new project, click `Add Firebase to your web app` 
  2. Copy the code from the line `var config = {` until `firebase.initializeApp(config);` 
  3. Paste the code in `includes/scripts/config.js` 
  4. Save! 

4. Configure your Firebase app project. 
  1. Authentication 
    1. Go to `Authentication` section on your Firebase console. 
    2. Click the `Set up Sign-in method`. 
    3. Enable Google as a sign-in provider. 
    4. Save! 

  2. Database 
    1. Go to `Database` section on your Firebase module. 
    2. Under `Data` tab, click the three vertical dots icon and select `Import JSON`. 
    3. Upload the `database-data.json`. 
    4. Click `Import`. 

  3. Rules 
    1. Go to `Database` section on your Firebase module. 
    2. Go to the `Rules` tab. 
    3. Copy the contents of `database-rules.json`. 
    4. Paste it to the text editor in Firebase. 
    5. Click `Publish`. 

5. Deploy the app to your website! 

6. Done! 


##Adding a new codelab session