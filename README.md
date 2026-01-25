# OKST56 DB Editor (Beta)

## 🚀 Download (Beta)

👉 **[Download OKST56 DB Editor v0.3.1 (ZIP)](../../releases/latest)**


A desktop database editor for **NCAA Football 14** save files.

This tool is designed to make dynasty and roster editing easier by allowing
direct inspection and modification of PS3 `.MC02` database tables.

---

## ⚠️ Beta Disclaimer

This is a **beta release**.

- Bugs are expected
- Features may change
- **Always back up your save files before editing**
- Use at your own risk

---

## Current Features (Beta 0.3.1)

- Open decrypted PS3 NCAA 14 save files (`.MC02`)
- Browse database tables
- View and edit table fields
- Save changes back to the database
- Basic UI for table navigation
- Conference Realignment

---

## Planned Features

- Year to Year conference realignment memory
- Schedule editing 
- Coach Editor
- Team Editor
- Updated UI that makes it more modern 
- Many more that will not be released to public yet

---

## Requirements

- Windows 10 or newer
- .NET Desktop Runtime (if not bundled)
- Decrypted NCAA Football 14 PS3 save files

---

## Installation / Usage

1. Extract the ZIP file
2. Run `OKST56_DB_Editor.exe`
3. Open a **decrypted** NCAA 14 save file (in .MC02 format)
4. Make changes
5. Save
6. Re-encrypt and test in game

---

## Feedback & Bug Reports

Please report:
- Crashes
- Incorrect data saves
- UI issues
- Feature requests

Use **GitHub Issues** or contact via College Football Revamped Discord Server https://discord.com/invite/cfbr

---

## Credits

Created by **OKST56**  

VERY SPECIAL THANKS TO THE FOLLOWING:
Antdroid (Check out NCAA NEXT MOD for NCAA 06 on PCSX2; https://www.ncaanext.com/)
TheBlueMist
Avilla831
gj2020
Nebrask
oplong80
reezon sports network
Str8 Ca$h Homie
V Neck Posse
JEDiMiNDFLiP
Dr Arlox
Shane54
Knightman

For the NCAA Football 14 modding community

Enjoy this tool, please remember that it is BETA stage, there are bugs and things to fix. We will work those out in good time. I created this tool simply for personal use and decided to share it with the community; it is not perfect by any means. There are certain things that are very tedious and hard to code for; not all situations will be able to be accounted for. I love this game, and this was definitely a labor of love. I welcome feedback but please be patient and realize I'm a simply a self taught vibe coder doing this in my free time; I'm entirely self taught.


🔧 Detailed Usage Guide
🏠 Home Tab (First-Time Setup – REQUIRED)

Go to File → Open
Select your decrypted NCAA 14 dynasty file (.MC02)
Navigate back to the Home tab
Click New Dynasty
Enter a Dynasty Name
Select a Dynasty Folder Color
Save the dynasty

⚠️ Important
You must save both the dynasty folder and the dynasty file
This system allows quick access to multiple dynasties later
If you skip this step, changes may not persist correctly

⚙️ Options Tab
Select your preferred Highlight Color
Select your Mod Type
Supported:
NCAA Football 14
EuroMod

⚠️ Other selections currently default to NCAA 14 behavior



🗄️ DB Editor Tab
This is the core database editor.

Capabilities
View and edit database tables
Export tables to CSV
Import CSV files (⚠️ currently limited)

⚠️ Current Limitations
CSV imports from other editors are not supported yet
This will be addressed in a future update
Editing Tips
Hover over orange-highlighted cells to view field definitions
Edit values carefully — invalid values can corrupt a dynasty
Save frequently


📖 Definitions Tab
Search for table names and field definitions
Intended as a reference while editing the DB
⚠️ This feature is still a work in progress and may not contain all definitions yet.

🏟️ Dynasty Home Tab
🚧 Work in Progress
This tab will be expanded in future versions to serve as a central dynasty dashboard.

🏛️ Conference Realignment Tool
⚠️ VERY IMPORTANT RULES (READ FIRST)
You must run this tool EVERY SEASON to maintain realignment
Conference changes do NOT persist year-to-year yet
Always back up your dynasty before using this tool

Recommended Workflow
Perform as much realignment as possible in-game first
Save and exit the dynasty
Open the dynasty in OKST56 DB Editor
Run the Conference Realignment Tool

✅ Supports:
Conferences of any size (as tested)

❌ Does NOT support:
Changing a conference from:
11 teams or fewer (non-divisional) → to 12+ teams (divisional) OR the reverse

👉 If changing conference structure size:
Use the in-game conference realignment editor first, then do smaller nuances with the conference realignment tool; Then apply final adjustments using this tool

📘 Full Realignment Guide:
https://docs.google.com/document/d/1wX2EJACf_bnchh8FdI398YLMncvU7sjjTE9dePt9pC4/edit

📆 Schedule Generator
⚠️ Backup. Backup. Backup.
Once all teams are aligned as you need...
Dynasty must be in the preseason stage (custom scheduling)
Save your dynasty 
Save a second file
Save a third file of the dynasty. This is in case you inevitably screw something up. I cannot fix your dynasty file once you obliterate it.
Select load teams button, then generate schedule, then write schedule to DB if you wish. The tool does not autosave the db at this point, you will need to save the file once you confirm it is done correctly.

🔍 Schedule Audit Tab
Review generated schedules before committing them
Displays:
Conflicts
Structural issues
Potential logic problems
Use this tab to:
Fix errors
Provide feedback to OKST56

👀 Schedule Viewer Tab
View schedules by:
Team
Week
Conference

⚠️ Important Behavior
The Schedule Viewer only reflects what is currently written to the DB
If you generate a schedule but do not write it to the DB:
The viewer will continue showing the old schedule

🧠 Pro Tips for Beta Testers
Always work on copied dynasties
Make one change at a time
Save often
Test changes in-game before continuing
Report bugs with:
What you were doing
What tab you were on
What season stage you were in
Take screenshots and/or video of issues, have a dynasty save ready to share or csv export


#GoPokes
