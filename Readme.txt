~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~Playwright~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
1. Install python and restart your system

2. Open the given project in Vscode or PyCharm.

3. Open the terminal and execute the below commands.
	*pip install playwright
	*playwright install
 	*pip install pyinstaller

4. Once the playwright is installed, make sure to replace the firefox driver from this location:
   "C:/Users/USERNAME/AppData/Local/ms-playwright/firefox-1429/firefox/firefox.exe"

5. Replace the URL to the one you want.

6. Replace the username, password, login button, mark attendance button, and logout button with your system's selectors;
   make sure to get all the IDs of the selectors and place them after the #.

7. Now execute the script through the terminal "python script.py."

8. Once the script runs successfully, then erase the parameters "headless=False" and "slow_mo=500."

9. Now write the command in the terminal: "pyinstaller --onefile script.py." It will create the executable file in the dist folder.

10. Boom! Now you just need to run the executable file every time.


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~Selenium~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
1. Install python and restart your system

2. Open the given project in Vscode or PyCharm.

3. Open the terminal and execute the below commands.
	*pip install selenium
 	*pip install pyinstaller

4. Replace the url, username, and password with the ones you want.

5. Replace the username, password, login button, mark attendance button, and logout button with your system's selectors;
   make sure to get all the IDs of the selectors and place them. (here you don't need to use #)

6. Now execute the script through the terminal "python script.py."

7. Once the script runs successfully, write the command in the terminal: "pyinstaller --onefile script.py." It will create the executable
   file in the dist folder.

8. Boom! Now you just need to run the executable file every time.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~Enjoy & Thanks~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~