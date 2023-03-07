# ResilioSyncUserInstall
Resilio Sync as User on Ubuntu or Debian based
This is a script i came up with to automate the configuration of installing Resilio-Sync as a user on ubuntu based systems, should also work on debian. It asks for the User name and Group you would like Resilio to Run as so you don't have to have all files synced as the rslync user and group. Creates folder /etc/Resilio to store the new config.json and automates the systemd overide needed to run resliosync as a user.
