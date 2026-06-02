LESSON 18 — How To Generate Reports And Documents From Your Files
=================================================================

WHAT'S IN THIS FOLDER
----------------------
PashunSports/
  Suppliers/           9 files across 3 suppliers:
                         KitPro:       2 invoices + 1 delivery note + pricing agreement
                         PrintForce:   2 invoices + 1 delivery note
                         FabricFirst:  1 invoice (OVERDUE) + 1 delivery note

                         Status expected from the dashboard:
                         FabricFirst -> RED (overdue)
                         PrintForce  -> AMBER (PF-26-0112 due 22 Apr)
                         KitPro      -> AMBER (KP-2026-0211 due 2 May)

  Reports/
    April/             4 source files for the monthly report demo:
                         april_sales.csv              20 orders across April
                         customer_feedback_april.txt  Feedback with sizing
                                                      complaint theme and NPS
                         supplier_invoices_summary.xlsx  Q1 costs summary
                         my_notes_april.txt           Paul's notes including
                                                      recommended May action

SETUP
-----
Copy the PashunSports/ folder to your computer.
If following the course, add these folders to your existing PashunSports/.

DEMO 1 — Supplier Status Dashboard
------------------------------------
    Read all files in /PashunSports/Suppliers/:
      - Invoice files (KitPro, PrintForce, FabricFirst)
      - Pricing agreements
      - Delivery notes

    Produce an HTML supplier status dashboard.
    For each supplier show:
      - Status card (Red = overdue | Amber = due within 7 days | Green = clear)
      - Outstanding invoice total
      - Most recent delivery note summary
      - Lead time and next expected delivery
    Save as: /PashunSports/Reports/SupplierDashboard.html
    Show plan first.

DEMO 2 — Monthly Performance Report
--------------------------------------
    Using the following files in /PashunSports/Reports/April/:
      - april_sales.csv
      - customer_feedback_april.txt
      - supplier_invoices_summary.xlsx
      - my_notes_april.txt

    Write a monthly performance report for Pashun Sports.
    Structure:
      1. Sales Overview (from CSV)
      2. Top Products (focus on World Cup range)
      3. Customer Feedback Summary
      4. Supplier Costs
      5. Key Observations (from my notes)
      6. One Recommended Action for May

    Tone: clear, direct, business-appropriate. Max 600 words.
    Save as: /PashunSports/Reports/April/PashunSports_April_Report.docx
    Show plan first.
