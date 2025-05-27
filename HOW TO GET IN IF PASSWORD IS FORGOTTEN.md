if G-OS password is forgotten, here's how to change and get inside without entering a password:
1. Press Ctrl + Shift + C (Since G-OS does not allow you to right-click)
2. Go to console
3. Press Ctrl + U to view page source
4. Find the function showMainApp(); in line 211 in the page source tab
5. Copy the function
6. Go back to console
7. Paste the function
BONUS: If your browser's console doesn't let you paste text, in Firefox, type "allow pasting"
8. Press run
9. After opening G-OS, click "Settings" and move the window by dragging the top of the window (the darker green part of the window)
10. Click security
11. Change the password, and click change password
12. Test it, if it doesn't work, please report the bug in GitHub to MadCode_25 
