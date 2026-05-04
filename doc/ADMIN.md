## FAQ
### Reset Actual Password
If you have forgotten your actual-server login password - not all is lost, as the password can be reset without losing any of your files / data. A password reset feature is available from version 23.4.2.

In SSH with an admin account try this command:
* open shell for app actual -> `sudo yunohost app shell actual`
* Reset password -> `node ./node_modules/@actual-app/sync-server/build/src/scripts/reset-password.js`

The script will prompt through requesting a new password and confirming it. Once set - you can login with the new password.
