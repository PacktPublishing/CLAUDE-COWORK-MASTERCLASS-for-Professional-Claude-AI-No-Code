LESSON 20 — How To Schedule Tasks So Claude Runs Work On A Set Cadence
=======================================================================

WHAT'S IN THIS FOLDER
----------------------
PashunSports/
  Orders/
    Daily/
      orders_daily_20260422.csv     Today's order export — 6 orders across
                                     different production statuses:
                                     Awaiting Production, In Production,
                                     Ready to Ship, At Risk

  Suppliers/
    supplier_status_notes.txt       Current supplier status including KitPro
                                     production progress, PrintForce job status,
                                     and the FabricFirst credit hold warning

THE DEMO TASK
-------------
This lesson is about setting up a scheduled task — not running a one-off.
Use these files to test the brief manually first, then schedule it.

Paste this brief into Cowork and run manually once:

    Read the latest files in /PashunSports/Orders/Daily/ and
    /PashunSports/Suppliers/

    Produce a morning production briefing saved to
    /PashunSports/Reports/Daily/
    File name: ProductionBrief_YYYY-MM-DD.txt

    Include:
      - Units ordered but not yet in production
      - Units in production per supplier
      - Units ready to ship
      - Any supplier issues flagged in latest emails or notes
      - Any orders at risk of missing delivery deadline

    Keep it under 200 words. Factual. No padding.

TO SCHEDULE IT
--------------
Scheduled -> New task -> paste the brief -> set cadence: Daily ->
set time: 08:00 -> More options -> select model -> set folder -> Save.
