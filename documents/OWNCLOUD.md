### SSO Setup for OwnCloud.

In order for Single Sign On to work in owncloud, you must install the plugin (which the installer does) and you must login

Navigate to OwnCloud (ex: https://owncloud.test.lan). Log in as 'localadmin' with the password you set during install.

![Login Screen](../assets/owncloud/owncloud1.png)

In the top right of the webpage, click the localadmin name. A drop down menu should pop up. Choose 'settings'.

![Login Screen](../assets/owncloud/owncloud2.png)

On the left middle, select 'User Authentication'.

![Login Screen](../assets/owncloud/owncloud3.png)

While not required, I hit 'Test Base DN' button. If you get a green light, click Continue.

![Login Screen](../assets/owncloud/owncloud4.png)

Click the 'Verify settings and count users'. It should say 2 (admin and your user) unless you've created additional users.

![Login Screen](../assets/owncloud/owncloud5.png)

Finally, type in your username that you created during install and click 'Verify settings'. The LDAP configuration is now ready to go.

![Login Screen](../assets/owncloud/owncloud6.png)

Once you have verified your user, you can log out.
