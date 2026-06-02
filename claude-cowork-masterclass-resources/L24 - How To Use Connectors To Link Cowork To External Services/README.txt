LESSON 24 — How To Use Connectors To Link Cowork To External Services
=======================================================================

FOLDER STRUCTURE
----------------
PashunSports/                   <- Copy this to your computer (local files)
  Products/WorldCup2026/
    England_2026_Tee_Specs.txt
    Brazil_Training_Tee_Specs.txt
    Argentina_Fan_Tee_Specs.txt

CloudInputs/                    <- Set these up in the relevant cloud services before the lesson
  GoogleCalendar/
    WorldCup2026_Fixtures.ics   <- Import this into Google Calendar (see below)
  Gmail/
    email_01 to email_07.eml    <- Get these into your Gmail inbox (see below)
  GoogleDrive/
    PashunSports/
      PashunSports_Inventory_2026.xlsx  <- Upload to Google Drive (see below)

═══════════════════════════════════════════════════════
GOOGLE CALENDAR — HOW TO IMPORT THE FIXTURES
═══════════════════════════════════════════════════════
1. Go to calendar.google.com
2. Click the gear icon (top right) -> Settings
3. In the left sidebar, click Import & export
4. Under Import, click Select file from your computer
5. Choose CloudInputs/GoogleCalendar/WorldCup2026_Fixtures.ics
6. Select which calendar to import into (your main calendar works fine,
   or create a new one called 'World Cup 2026')
7. Click Import

All 7 fixtures will appear immediately — 3 England, 2 Brazil, 2 Argentina.
Note: times are in UTC and will be converted to your local timezone automatically.

═══════════════════════════════════════════════════════
GMAIL — HOW TO GET THE SAMPLE EMAILS INTO YOUR INBOX
═══════════════════════════════════════════════════════
Gmail does not support direct .eml import. Use one of these two options:

OPTION A — Send them to yourself (simplest)
  1. Open each .eml file in a text editor (Notepad, TextEdit, etc.)
  2. Copy the email body text
  3. Send yourself an email from a different address (a second Gmail,
     a friend's address, or any other account) to your main Gmail
  4. Use the Subject line shown in the .eml file
  5. Do this for all 7 emails — they'll appear in your Gmail inbox
     and Cowork will find them when you run Workflow 2

OPTION B — Use Thunderbird (more realistic)
  1. Download Mozilla Thunderbird (free) — thunderbird.net
  2. Connect it to your Gmail account (File -> New -> Existing Account)
  3. Drag and drop the .eml files into your Inbox in Thunderbird
  4. They will sync to Gmail within a few seconds

The 7 emails cover:
  - 2 positive reviews (England tee, Brazil tee)
  - 2 sizing complaints (runs small)
  - 1 shipping query (where is my order?)
  - 1 refund request (Argentina tee wrong colour)
  - 1 international shipping query (Germany)

This gives Cowork enough material to produce a realistic feedback digest.

═══════════════════════════════════════════════════════
GOOGLE DRIVE — HOW TO UPLOAD THE INVENTORY FILE
═══════════════════════════════════════════════════════
1. Go to drive.google.com
2. Create a new folder called exactly: Pashun Sports
   (the name must match exactly — Cowork references this folder by name)
3. Open that folder and upload:
   CloudInputs/GoogleDrive/PashunSports/PashunSports_Inventory_2026.xlsx

═══════════════════════════════════════════════════════
CONNECT THE APPS IN COWORK
═══════════════════════════════════════════════════════
Settings -> Connectors -> connect Gmail, Google Calendar, Google Drive
(Do this before running any of the three workflows)

═══════════════════════════════════════════════════════
THE THREE DEMO TASKS
═══════════════════════════════════════════════════════

WORKFLOW 1 — Google Calendar -> Match-Day Social Posts
    Read my Google Calendar for all World Cup 2026 match events
    involving England, Brazil, or Argentina.
    For each match:
      - Identify the relevant Pashun Sports tee (from /PashunSports/Products/)
      - Draft a match-day social post for Instagram and X
      - Time it for 2 hours before kick-off
      - Include the correct hashtags for the territory
    Save all posts to: /PashunSports/Marketing/MatchDaySocialPosts.txt

WORKFLOW 2 — Gmail -> Customer Feedback Digest
    Check my Gmail for any customer emails received in the last 7 days.
    Look for: complaints, refund requests, sizing questions,
      shipping problems, positive feedback about World Cup tees.
    Summarise the key themes into a weekly digest.
    Send the digest as an email to team@pashunSports.co.uk with
    subject: 'Customer Feedback Digest - w/e [date]'
    Wait for my approval before sending.

WORKFLOW 3 — Google Drive -> Local Report
    Read the file 'PashunSports_Inventory_2026.xlsx' from my Google Drive
    in the folder 'Pashun Sports'.
    Identify any products where stock is below 20 units.
    Save a restock alert as /PashunSports/Reports/RestockAlert_Apr2026.txt
