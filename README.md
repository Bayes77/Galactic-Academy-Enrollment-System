🚀 Galactic Academy Enrollment System
🎯 Goals

The goal of this project is to practice building a dynamic frontend application using vanilla JavaScript. You will manage recruits entering a space academy, assign them to factions, and handle expulsion to a separate group.

Focus on MVP first (functionality over styling). Use Bootstrap for layout and styling after functionality works.

📌 Instructions

You are in charge of building an enrollment system for the Galactic Academy.

Core Features:
A welcome “Commander Console” card introduces the system.
A button starts the enrollment process.
A form appears where users enter:
Recruit name
Image URL
On submission:
Recruit is assigned a random faction
Recruit is added to the Academy roster
🌌 Factions (like houses)

Randomly assign each recruit to:

Nova Corps
Orion Syndicate
Vega Order
Solaris Guard
🧾 Display Requirements

You must have two main sections:

🟦 Academy Roster
Shows all active recruits
Each recruit appears as a card with:
Name
Image
Faction
“Exile” button
🟥 Rogue Fleet
Shows expelled recruits
Styled differently from active recruits
🚫 Exile Feature

When a recruit is exiled:

They are removed from the Academy array
They are added to the Rogue Fleet array
The DOM re-renders with updated state
🔍 Filtering System

Add buttons to filter Academy recruits by faction:

All Recruits
Nova Corps
Orion Syndicate
Vega Order
Solaris Guard

Filtering should NOT affect Rogue Fleet.

🧠 Technical Requirements
You MUST create a structured data model (arrays of objects)
You MUST use functions for all logic
No DOM manipulation outside functions (except initial start function)
You MUST use a loop other than a simple for loop at least once
You MUST use event delegation for exile buttons
You MUST use Bootstrap for styling
You MUST maintain clean indentation
🧩 Suggested Data Structure

Each recruit object should include:

id
name
faction
imageUrl
⚙️ Suggested Functions

You should create functions similar to:

createRecruit()
assignFaction()
renderRoster()
renderFleet()
filterRecruits()
exileRecruit()
renderToDom()
🧨 Bonus Features (optional)
Highlight factions with different card colors
Add search bar for recruit names
Add “restore recruit” from Rogue Fleet
Sort recruits alphabetically
🧱 Definition of Done
Recruit system works end-to-end
Exile moves recruits correctly
Filtering works without breaking state
Clean render functions
No duplicated DOM logic
🎤 Presentation Requirement

Be ready to explain:

how your state is structured
how exile works
how filtering works
your favorite function you wrote
