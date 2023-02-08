# mac-trial-reset
Simple script to automate date/time change and application launch within trial period

Useful if you have an app whose trial period has ended. A quick way to save some time and saves you having to change it back yourself (which you need to do to use alot of processes / browse many websites.

Edit the script with the following:
1. Set the date/time to a period when your trial was active
2. Set the pathname of application
3. Set a longer 'sleep' time if your application takes a long time to open
4. Run $ chmod +x 'filename' to give the file executable permissions
5. Launch in terminal from script's location $ ./'filename'

That's it! You should see your date/time change as the app opens and then revert back to actual date/time after 10 seconds.

This is the first 'useful' script I've written :)
