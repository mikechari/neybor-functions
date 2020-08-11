# neybor-functions
Neybor app firebase functions

### Install firebase tools:

`npm install -g firebase-tools`

### Firebase login:

`firebase login`

### Firebase init:

`firebase init`

### Update to latest

`npm install firebase-admin@latest firebase-functions@latest`

### For custom functions:
`firebase functions:config:get > .runtimeconfig.json`

### Testing functions
Adding Credentials: 
#### BAD
`set GOOGLE_APPLICATION_CREDENTIALS=`
#### GOOD
`gcloud auth application-default login`

Check for possible errors:
`npm run-script lint`
Compile the script:
`npm run-script build`

Run the emulator:
`firebase emulators:start`

Test the function: **OLD use emulator**
`firebase serve --only functions`

### Deploy functions

`firebase deploy`



