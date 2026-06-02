LESSON 27 — How To Use Skills To Give Claude Domain Knowledge And Best Practices
==================================================================================

FOLDER STRUCTURE
----------------
PashunSports/                   <- Copy this to your computer (local files)
  Products/WorldCup2026/
    England_2026_Tee_Specs.txt  Input for the demo task

SkillFile/                      <- Upload this to Cowork (not to your PashunSports folder)
  SKILL.md                      The ready-made social post skill — upload via
                                 Cowork sidebar -> Customize -> Skills -> upload

HOW TO UPLOAD THE SKILL
------------------------
1. Open Claude Desktop -> Cowork tab
2. Click Customize in the left sidebar
3. Click Skills
4. Click the upload button and select SkillFile/SKILL.md
5. The skill 'pashun-social-post' will now appear in your Skills list

THE DEMO TASK
-------------
Once the skill is uploaded, run this in Cowork:

    Using the pashun-social-post skill:

    Create social post preview cards for our England 2026 World Cup Tee.
    Tee details in: /PashunSports/Products/WorldCup2026/England_2026_Tee_Specs.txt
    Produce cards for Instagram, X, and TikTok.

WHAT THE SKILL DOES
--------------------
Cowork loads the skill automatically and produces three HTML social post preview
cards — one per platform — with the England tee SVG, platform-specific caption,
and hashtag set. Consistent brand output every time without re-explaining the rules.
