LESSON 21 — How To Set Up Recurring Workflows And Walk Away
=============================================================

WHAT'S IN THIS FOLDER
----------------------
PashunSports/
  Reports/
    Weekly/
      weekly_sales_wk18.csv         Week 18 sales summary — 7 products,
                                     units sold and revenue per product.
                                     England Tee is the top seller (47 units).

  Products/
    WorldCup2026/
      England_2026_Tee_Specs.txt    Spec for the week's top product
      Brazil_Training_Tee_Specs.txt
      Argentina_Fan_Tee_Specs.txt
      Spain_Classic_Tee_Specs.txt
      Morocco_Away_Tee_Specs.txt

THE DEMO TASK
-------------
Test this manually first before scheduling. Paste into Cowork:

    RECURRING WORKFLOW — runs every Friday at 17:00

    Step 1: Read /PashunSports/Reports/Weekly/ — find this week's
      top product by units sold (from the weekly sales CSV)

    Step 2: Read the spec file for that product from
      /PashunSports/Products/WorldCup2026/

    Step 3: Produce a customer-facing HTML email newsletter:
      - SVG flat-lay of the tee as the hero visual
      - Bold headline: [Product Name] — World Cup 2026
      - 2 lines of fan-first body copy
      - CTA button: 'Shop Now at PashunSports.co.uk'
      - Footer with social links
      Save as: /PashunSports/Marketing/LaunchEmail_YYYY-WW.html

    Step 4: Produce a product launch HTML page:
      - Full product view with tee SVG
      - Name, price, sizes, description, 'Add to Bag' button
      Save as: /PashunSports/Marketing/ProductPage_YYYY-WW.html

    If any step fails, log the error and continue.
    Show me the plan first.

Run it with 'show me the plan first', review the outputs, then
schedule it with 'Do not ask for approval'.
