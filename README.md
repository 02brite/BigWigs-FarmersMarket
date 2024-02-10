# BigWigs for Farmers Market
BigWigs is a World of Warcraft AddOn to predict certain AI behaviour to improve the players performance.<br>
This Modification is built for Patch 1.12.1 and its content for use on the <b>Turtle WoW</b> private Server.<br>
This Modification is built for Farmers Market and Templarios. The SEXXXOOOOOOOest guilds on <b>Turtle WoW</b>.<br>
<br>
The reason this exists is that some interactions did not anticipate a player being named "You".<br>
The following events have potential interactions with the name "You" and notes for reference<br>
- Jindo - Shades - checks playername - should function
- Mandokir - Gaze - could check for "you" at end of gaze - minimal effect
- Buru - Follow - Checks for "You" and players with assist mark themselves as skull - <b>MODIFIED FILE</b> changed to check for "you" and "are"
- Anubisath Guardians - Plague - checks for "you" and "are" - model for aq40 guardian changes
- Baron Geddon - Living Bomb - checks for "you" and "are" - should be fine
- Vaelastrasz - Burning Adrenaline - checks for only "are" - possible model for all "you" + "are" checks
- Anubisath Defenders - Plague - checks for "You" - <b>MODIFIED FILE</b> changed to check for "you" and "are" as is done in Anubisath Guardians.
- C'Thun - various - Does not check for "you" - should function
- Thaddius - Charge - Defines a "you" and "are" but never calls for them later. I think they were hold overs from a copy paste - should function
- Kel'Thuzad - Affliction/Detonate trigger - checks for both "you" and "are" in both events. - should function
<br>
This was purposefully not properly forked because no one really needs this except our raiders.<br>
I have no formal training, feel free to help me out with advice!<br>

## KNOWN ISSUE
The Buru event will not work with Spanish or German game clients.<br>
<b>Only players using an English Turtle WoW client should use this AddOn.</b><br>
If you have a Spanish or German client, you have no need for this until someone gets the name "Tu" or "Euch".<br>


## How to install
- Download manually via github (click on Clone or Download -> Download ZIP.
- Delete old Bigwigs or !BigWigs folder
- Place "BigWigs" folder in gamefolder>Interface>AddOns
- Place "Fonts" folder in [original gamefolder directory](https://github.com/balakethelock/BigWigs/assets/111737968/2cddcb31-b318-4e6a-9203-413195a34c8d)

## Contributing
If you would like to contribute, just open a pull request.

## Language support
Currently, only english clients are supported. In general, the Addon can work with other languages, but this support is only provided on a best-effort basis. It is much effort to support those languages. Feel free to contribute if you would like to have support for other languages.

## License
The adjustments were originally made by <a href="https://github.com/MOUZU"><b>LYQ</b></a> and <a href="https://github.com/xorann/BigWigs"><b>Dorann</b></a><br>
Adjustments for Elysium made by <b>Hosq</b>.<br>
Adjustments for Turtle-WoW made by <b><a href="https://github.com/CosminPOP/BigWigs">CosminPOP</a></b>.<br>
Expanded for Turtle-WoW  by <b><a href="https://github.com/balakethelock/BigWigs">Balake</a></b>.<br>
Credit to <b><a href="https://github.com/madScripting/BigWigs-TurtleWoW">Relar/MadScripting</a></b> for some features.<br>
Adjustments for Meme names made by <b>YOU</b>... no wait <b>Noctre</b>
