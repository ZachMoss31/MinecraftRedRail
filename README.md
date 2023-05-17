# MinecraftRedRail
Python project built to quickly create, deploy, update, and remove servers for Minecraft. Targeting both version of Minecraft, as well as setting up local-hostable (non-single-player), Azure, and AWS servers.

## Desired Functionality
* As a user, I want to launch a program that opens window to select which platform to host the server on (maybe allow drag and drop of existing server file)
* As a user, I want to know the status of my server I'm connecting to and how many other players are on
* As a user, I want an intuitive and easy setup process to get the server up and running
* As a user, I may want to add mods or a modding engine (i.e., forge) to the game

## Projected Tasking
* The Project will need Main to launch the actual application, as well as handle the I/O button logic displayed, config drop down, etc.
* Project will need to pull in libraries for both AWS (Boto3) and Azure (Azure SDK). These will likely have their own config details, such as whether to use EC2 or Lightsail in AWS.
* Project will need to have linking out to accounts (billing setup, launching) as well as safe information saving of this info.
* Project needs a GUI that includes name of server, status, version, current usage (player count), and timestap of last check / last backup.