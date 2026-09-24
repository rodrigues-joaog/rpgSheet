# rpgSheet

A **single file RPG sheet** built on **HTML**, **CSS** and **JavaScript** intended for **online and offline use** for a personal vttrpg project called **Projeto Hades**

### Credits
*Still empty, for now*

### Roadmap
###### Legend:
🟢 **Done**

🟣 **Blocked due to another task**

🟡 **Works but not completed**

🟠 **In progress**

🔴 **Pending**
###### Tasks:
🟠 **Styling, Compliance and Offline**
- Convert images into base64 for offline use
- Import bootstrap css & js and google fonts & symbols for offline use
- Check for copyright and replace images: navbar, background, char details and char effects

🟠 **Profile picture**
- Currently static (not changeable)
- Needs base64 converter

🟡 **Char name**
- Font size breaking on specific screen sizes

🟡 **Char basic details**
- Input size is fixed and does not fit empty space

🟠 **Char status**
- Colors and symbols are displayed correctly for Filled, Available and Unavailable
- Using input from number fields on the end of the page
- Only updates on page refresh

🟠 **Char effects**
- Currently building interface
- Needs a list of effects with: icon, description and levels
- Needs a duration field
- Needs a select input

🔴 **Inventory**
- Get bag image - design choice is still under discussion (with myself)
- Needs a text field for miscellaneous items
- Needs a weapon slot with: name, damage and ammunition
- Needs a tool slot with: name, description and uses
- Needs a vest slot with: name, protection and durability

🔴 **Skill tree**
- Standard skills will contain: cost, current level, icon and a description
- A prestige system will lock specific skills, unless player has spent an X amount of point on the atribute tree (inspired on Arc Raiders skill tree)
- There will be four atribute trees: Intelect, Psychology, Physical and Identity
- I'll definitely need a therapist after this

🔴 **Rule book**
- Basic information about the sheet and homebrew system
- Not a priority, players will ignore this anyway

🔴 **Player book**
- A notepad
- Just a notepad, really
- Okay, I may try to make it flippable (NO PROMISES THO!)

🟣 **Save file**
- Button visual already done
- Will save a JSON file
- Awaiting all previous tasks related with input

🟣 **Import file**
- Button visual already done too
- Will import a JSON file
- Awaiting all previous tasks related with input

🔴 **Server sync**
- Button will have visual indication of sync (pressed and symbol spinning)
- Will open a modal screen with: server address, username and password
- After logging in, will prompt a char selection screen from the server
- Will save changes automatically while activated