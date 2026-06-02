LESSON 11.5 — How To Use Projects To Organise Your Work And Build Persistent Workspaces
========================================================================================

WHAT'S IN THIS FOLDER
----------------------
PashunSports/                   <- Copy to your computer (the folder you'll wrap in a project)
  Orders/                       All empty — Cowork fills these as you run tasks
  Products/
  Suppliers/
  Reports/
  Marketing/
  WorldCup2026/

ProjectInstructions_Template.txt  <- Ready-to-use instructions block for the demo.
                                     Copy the text inside and paste it into the
                                     Instructions field when creating your project.

HOW TO CREATE THE PROJECT
--------------------------
1. Copy PashunSports/ to your computer if you haven't already
2. Open Claude Desktop -> Cowork tab -> Projects in the left sidebar
3. Click +
4. Choose: Use an existing folder
5. Select your PashunSports/ folder
6. Name the project: Pashun Sports World Cup 2026
7. Paste the instructions from ProjectInstructions_Template.txt
8. Click Create

THE FIRST TASK (run this inside the project)
--------------------------------------------
    Read everything in this folder.
    Summarise what you know about this workspace:
    what's here, what I probably use it for,
    and what instructions you'll follow.
    If anything is unclear, ask before proceeding.

This "onboarding task" lets Claude build initial context on day one.
After this, every subsequent task in the project benefits from that context.

KEY DIFFERENCES FROM A STANDALONE FOLDER SESSION
--------------------------------------------------
Without a project:
  - Claude has no memory of previous sessions
  - No standing instructions
  - Scheduled tasks have no project context

With a project:
  - Memory persists across every session automatically
  - Instructions apply to every task without re-stating them
  - Scheduled tasks run with full project context

LIMITATIONS TO BE AWARE OF
---------------------------
- Projects are stored locally — no cloud sync
- Only available in Cowork (not Claude Code yet)
- Archiving removes the project from the UI but does NOT delete your files
