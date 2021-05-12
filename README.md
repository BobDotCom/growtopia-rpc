# growtopia-rpc

Growtopia Discord Rich Presence by GrowStocks.


# Instructions
- Download the .exe from the "Releases" tab
- Open the .exe file (the presence will only show if Growtopia and Discord are open at the same time) 

# Expected Result

![Presence](https://i.imgur.com/5dYcvV1.png)

# Running on startup
If you would like to permanently run the script so that it automatically detects when you open the game and sets your presence without having to open it everytime, read on.
- Search for "Task Scheduler" via the start menu
- Click on "Task Scheduler (Local)", then on "Actions" (in the top-bar), then "Create Task.."
- Fill in the fields as follows:
+ Name: Growtopia Discord Rich Presence
+ Configure for: (your version of Windows)
- In the top-bar, click on "Triggers", then "New..."
- Select "Begin the task:" -> "At log on", then click on "OK"
- In the top-bar, click on "Actions", then "New..."
- Fill in the fields as follows:
+ Program/script: click on "Browse..." and select the .exe you downloaded previously
- Click on "OK", and "OK" once again
- You're done. Restart your computer for the changed to take effect

# Additional Notes

This script makes use of the data found in the `save.dat` file on your computer to be able to parse your GrowID as well as the world you're in.
This script does not use the `save.dat` file for purposes other than the ones mentioned above. The code has been made open-source for you to check for yourself.