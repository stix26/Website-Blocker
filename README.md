# Website-Blocker
Website blocker made with the instruction of a Udemy course. A python script that blocks websites during working hours.

Step 1: (Download Zip)

Step 2: Go to your downloads folder and select Website-Blocker-master

Step 3: Open your (terminal or command line) and at the (bash$ line) or (cmd) type cd Downloads and press enter

Step 4: Type ls and press enter

Step 5: Press command F (Mac users) and type website. Highlight and copy Website-Blocker-master download.

Step 7: Type cd and paste(Website-Blocker-master) and press enter (i.e. cd Website-Blocker-master)

Step 8: Type sudo nano /etc/hosts (To check the status of your host file) and press control x to exit 

Step 9: Type sudo python3 website_blocker.py and press enter (This is to give your script administrative priviledges)

Step 10: Exit or reload your current browser

If you want to run the script in the background after a shutdown or restart (Mac Users)

Step 1: Open your terminal and type cd Downloads and press enter

Step 2: Type cd website-blocker-master and press enter

Step 3: Type sudo crontab -e and press enter

Step 4: Enter admin password and press enter

Step 5: Scroll to the bottom of the screen and type @reboot python 3 directory path (i.e. /Users/generic 2/Downloads/Website-Blocker-master/website_blocker.py)

Step 6: Press control x and control y then press enter to save the changes

Tip: To add different websites to the website blocker application on line 7 of the website_blocker.py script enter the site within the brackets adjacent to website_list variable. For example: website_list=["espn.com", "twitter.com"]

Also if the script doesn't automatically block the intended site try restarting your browser. 
