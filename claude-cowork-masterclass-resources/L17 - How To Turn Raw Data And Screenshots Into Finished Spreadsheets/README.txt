LESSON 17 — How To Turn Raw Data And Screenshots Into Finished Spreadsheets
============================================================================

WHAT'S IN THIS FOLDER
----------------------
PashunSports/
  Orders/
    Week18/
      orders_mon_tue.csv    5 orders, 36 columns — Mon/Tue
      orders_wed_thu.csv    5 orders, 36 columns — Wed/Thu
      orders_fri_sat.csv    5 orders, 36 columns — Fri/Sat

      Each CSV has 36 columns including billing/shipping addresses,
      VAT breakdowns, warehouse IDs, courier details, picking dates.
      You only need 7 of them.

  Suppliers/
    FabricFirst_pricing_description.txt   Pricing data for the screenshot demo.
                                           See the file for instructions.
    PrintForce_Invoice_PF-26-0112.txt     The PrintForce invoice for Demo 3
                                           (upload directly to Cowork via +).

DEMO 1 — Merge Three CSVs Into One Clean Spreadsheet
------------------------------------------------------
    Read the three CSV files in /PashunSports/Orders/Week18/:
      - orders_mon_tue.csv
      - orders_wed_thu.csv
      - orders_fri_sat.csv

    Create a single spreadsheet: /PashunSports/Reports/WeeklySales_Wk18.xlsx

    Include only these columns:
      Order ID | Date | Product Name | Qty | Price | Status | Customer Email

    Add a summary row at the bottom:
      Total orders | Total revenue | Average order value

    Highlight any orders with Status = 'Cancelled' in red.
    Show plan first.

DEMO 2 — Extract From a Screenshot
------------------------------------
Take a screenshot of the pricing table in FabricFirst_pricing_description.txt
and save it as FabricFirst_pricing.png in your Suppliers/ folder. Then run:

    There is a screenshot called 'FabricFirst_pricing.png' in
    /PashunSports/Suppliers/.
    Extract the pricing table from this image and save it as a
    properly formatted spreadsheet:
    /PashunSports/Suppliers/FabricFirst_Pricing_Apr2026.xlsx

DEMO 3 — Upload a PDF Invoice
-------------------------------
Upload PrintForce_Invoice_PF-26-0112.txt into Cowork via the + button, then:

    I have uploaded a PDF invoice from our supplier PrintForce.
    Extract the following from it:
      - Invoice number
      - Line items with quantities and prices
      - Total amount and payment due date
    Save the extracted data as:
    /PashunSports/Suppliers/PrintForce_Invoice_Extract_Apr2026.xlsx
