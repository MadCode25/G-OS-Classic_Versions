How to Reset Your G-OS Password (If Forgotten)

If you’ve forgotten your G-OS password, follow these steps to regain access without entering it:

1. Press Ctrl + Shift + C to open Developer Tools.
(Right-clicking is disabled in G-OS.)

2. Switch to the Console tab.

3. Press Ctrl + U to open the Page Source.

4. Locate the function named showMainApp(); (usually around line 211).

5. Copy the function’s name.

6. Return to the Console tab.

7. Paste the copied name there.

  * Bonus tip (Firefox users): If pasting is blocked, type allow pasting in the console first.

8. Press Enter to run the function.

9. Once G-OS opens, click Settings.

10. Move the settings window by dragging its title bar (the dark green top area).

11. Go to the Security section.

12. Change your password and click Change Password to confirm.

13. Test your new password. If it doesn’t work, please report the issue on GitHub to @MadCode_25.
