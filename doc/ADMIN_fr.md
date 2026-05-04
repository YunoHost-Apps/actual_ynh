## FAQ
### Réinitialiser le mot de passe
Si vous avez perdu le mot de passe de actual, on peut changer le mot de passe sans perdre les données. La fonction de réinitialisation est disponible depuis la version 23.4.2.

En SSH avec un compte admin:
* Ouvrir un shell avec le compte Actual -> `sudo yunohost app shell actual`
* Lancer le script de réinitialisation -> `node ./node_modules/@actual-app/sync-server/build/src/scripts/reset-password.js`

Le script vous demande un nouveau mot de passe et de le confirmer. Une fois fait, vous pouvez vous identifier avec le nouveau mot de passe.
