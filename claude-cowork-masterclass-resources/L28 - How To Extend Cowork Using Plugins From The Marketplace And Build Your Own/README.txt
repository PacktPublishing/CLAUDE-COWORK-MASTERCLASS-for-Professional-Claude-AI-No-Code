LESSON 28 — How To Extend Cowork Using Plugins From The Marketplace — And Build Your Own
==========================================================================================

FOLDER STRUCTURE
----------------
PashunSports/                               <- Copy to your computer (local files)
  Products/WorldCup2026/
    GoldenBoot_Specs.txt                    Input for the Part 1 demo (Marketing plugin)

PluginFiles/                                <- The complete plugin to package and upload
  pashun-worldcup-plugin/
    .claude-plugin/
      plugin.json                           Required manifest — the only mandatory file
    skills/
      social-post.md                        Reused from Lesson 27
      product-description.md               New Skill created in this lesson
    commands/
      README.txt                            Placeholder — add slash commands here later
    agents/
      README.txt                            Placeholder — add sub-agents here later

HOW TO PACKAGE AND UPLOAD YOUR PLUGIN
--------------------------------------
The complete plugin folder is already built. You just need to zip and upload it.

  On Mac:
    1. Open PluginFiles/ in Finder
    2. Right-click pashun-worldcup-plugin/ then Compress
    3. Rename from pashun-worldcup-plugin.zip to pashun-worldcup-plugin.plugin

  On Windows:
    1. Open PluginFiles/ in File Explorer
    2. Right-click pashun-worldcup-plugin/ then Send to -> Compressed folder
    3. Rename from .zip to .plugin

  Then in Cowork:
    Customize -> Plugins -> + -> Upload plugin file -> select pashun-worldcup-plugin.plugin

  Your plugin will appear in Customize -> Plugins.
  Type / in any Cowork task to see your plugin's skills listed.

WHAT'S IN THE PLUGIN
--------------------
plugin.json              The manifest. Tells Cowork the plugin name, description,
                         version. This is the only required file.

skills/social-post.md         The social post skill from Lesson 27, copied here so
                              the plugin bundles it without a separate upload.

skills/product-description.md A new skill for writing product descriptions.
                              This is the second skill created in this lesson.

commands/                Optional folder for slash commands. Empty for now.
                         Add .md files here when you want shortcut commands.

agents/                  Optional folder for sub-agents. Empty for now.
                         See Lesson 29 for how sub-agents work.

DEMO PART 1 — Using the Marketing Plugin
-----------------------------------------
Install: Cowork -> Customize -> Plugins -> Marketing -> Add plugin

    Using the Marketing plugin:
    Create a product launch brief for our 'Golden Boot 2026' England tee.
    Source file: /PashunSports/Products/WorldCup2026/GoldenBoot_Specs.txt
    Output:
      - 3 social media caption options (Instagram, X, TikTok)
      - 1 email subject line and preview text
      - 1 hashtag set for the World Cup campaign
    Save to: /PashunSports/Marketing/GoldenBoot_Launch_Brief.docx
