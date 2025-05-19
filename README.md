===============================
SMART AUTO FISHER BOT SETUP
===============================

This bot will automatically fish and fix your rod every 50 and 100 catches.
It will log progress to a Discord webhook and scan your inventory.

-------------------------------
🔧 SETUP INSTRUCTIONS
-------------------------------

1. ✅ REQUIREMENTS:
   - Windows PC
   - Python 3.x installed (https://www.python.org)
   - All `.png` files and the script in the same folder

2. 📦 INSTALL DEPENDENCIES:
   - Open Command Prompt in this folder
   - Run this command:

     pip install -r requirements.txt

3. ▶️ RUN THE BOT:
   - Double-click `launch_bot.bat` 
     (or run from terminal: python smart_auto_fisher.py)

-------------------------------
📁 FOLDER CONTENTS
-------------------------------
- smart_auto_fisher.py       → Main script
- loot_templates/            → Folder with item images (fish, etc.)
- fish_caught_prompt.png     → Prompt screenshot to detect when a fish is caught
- death_prompt.png           → Death screen template
- requirements.txt           → Libraries needed
- launch_bot.bat             → Double-click launcher (optional)
- README.txt                 → This file

-------------------------------
💡 TIPS
-------------------------------
- Keep Minecraft focused and fullscreen or windowed (no alt-tabbing).
- Keep your inventory clean to avoid cluttering scans.
- Make sure Discord webhook is valid and allows messages.

Enjoy your automated fishing!
