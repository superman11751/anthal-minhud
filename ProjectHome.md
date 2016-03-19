<h1>Anthal's minHUD</h1>

After 4 years of using the default HUD, I finally decided it was time to create my own. While influenced by other HUDs out there, I have done all of the work myself, and have not used any one else's work.

It is designed as an incredibly minimalistic HUD, with everything closer to where your eyes are.

<h2>Features</h2>

-Player Ammo and Health indicators have been made smaller, and moved closer to the center of the screen.<br>
-All class 'charge' bars have been centered in the HUD.<br>
-Classes with multiple charge bars have varying positions.<br>
-(Medic) Uber meter is centered and lengthened to be the width between the ammo/health counters. The uber % replaces the ammo counter as needed.<br>
-(Demoman) The number of stickies out for the demoman is now right below the crosshair, and is the value only. It is hidden when there are 0 stickies out.<br>
-(Demoman) Heads collected for the demoman are below the ammo counter.<br>
-(Engineer) Metal display is above the ammo counter, and much smaller.<br>
-(Engineer) Revenge crit count is below the ammo counter, and much smaller.<br>
-(Spy) Crit counter for the diamondback is below the ammo counter.<br>
-(Sniper) The Huntsman charge bar is above the Jarate bar, dead center.<br>
-Kill stream now shows the last 8 kills, and is much smaller<br>
-Outgoing damage is 'stickied' to the right, and just above the crosshair.<br>
-Incoming health, and self damage (Boston Basher, GRU, etc) are displayed to the right and above the health cross.<br>
-TargetID frames have been reduced and stylized, as well as lowered.<br>
-A 6's and Highlander scoreboard have been included, along with a default pub (32 player) scoreboard.<br>

<h2>To Do</h2>
-Detail everything. Some things need slight pixel adjustments.<br>
-Rework the Tournament spectator HUD, and add health values.<br>
-Rework the class and team selection pages.<br>
-Rework the weapon select.<br>
-Rework the Engineer building frames.<br>
-Check out the control point/cart indicators.<br>

<h2>Changelog</h2>

<h3>Beta 7.5</h3>
<br>
This updates fixes the MVM Scoreboard, and adds support for the new Killstreak feature. The MVM Scoreboard needs some work, but it no longer crashes when you hit tab!<br><br>

Previous versions also added the 3d Model Preview on the HUD.<br><br>

<h3>Beta 7.3</h3>
<br>
Everything is now updated for the 2012 Smismass Update! The Loose Cannon and The Vaccinator are now working, and the HUD no longer crashes TF2!<br>
<br>
-Added support for The Loose Cannon and The Vaccinator.<br>
-Modified the Shield Charge meters for Demo to be more in line with the new weapon.<br><br>

<h3>Beta 7.2</h3>
<br>
The HUD is now Halloween 2012 updated! Some things may need to be fixed. Also included is a beta for the Spectator Hud!<br>
<br>
-Updated HudPlayerHealth.res to be compatible with the update.<br>
-Removed the black bars form the spectator HUD.<br>
-New Tournament HUD in BETA!<br><br>

<h3>Beta 7.1</h3>
<br>
As far as I can tell, the HUD is now fully usable both in and outside of MVM. More changes to make the MVM HUD look better will come in the future.<br>
<br>
-Moved the icon for the MVM TargetID's ammo. Still haven't found where the value is stored.<br>
-Moved the Canteen icon and value to just under the Health cross. This was also made smaller, and the help text was removed.<br>
-Modified the Wave panel to be more in line with the rest of the HUD. <br>
-Modified the MVM Scoreboard to be not so ugly. The 9's and 6's scoreboards are still broken in MVM (but fine outside of it).<br>
-Updated the Animations file with the MVM changes.<br>
<br>
<h3>Beta 7</h3>
<br>
Expect a beta 7.1 today or tomorrow (8/16 or 8/17) with more fixes. This just brought the HUD into "usable" mode. Some stuff may still be a little wonky. Beta 8+ will deal with more of the MVM HUD, which is atrocious. Shame on you, Valve!<br>

-Fixed the Ammo/Health being out of position due to the update.<br>
-Fixed the 32 player Scoreboard. Currently the HL and 6's scoreboard will NOT work in MVM mode.<br>
-Fixed the TargetID and freezecam frames. There are new elements that need to be adjusted/worked on.<br>
<br>

<h3>Beta 6</h3>
-The Player Class resource file was missing and has been included again (sorry!).<br>
-Fixed the Spy image not being minmode 0 compatible, and modified the spy targetID frame.<br>
-The scoreboard will now cap at 16 players instead of bleeding down into the stats. A future fix for VSH/FF2 may be worked on.<br>
-Players waiting (for VSH/FF2 and Arena) has been moved accordingly.<br>
-The Cleaver (scout secondary) charge bar is now where the Mad Milk bar usually sits.<br>
-Modified the scoreboards to fit the dueling pane. This works for all 3 scoreboard variants.<br>

<h3>Beta 5</h3>
-Moved the focus charge bar for the Sniper's new primary to the center (above the Jarate, like the Huntsman).<br>
-Normalized the differences between normal and minmode. This will eventually be used to switch between the competitive and 32 man scoreboards.<br>
-Slightly moved the chat, made the fonts smaller, and made it taller/wider. Personal pet peeve. Exclude basechat.res if you don't want to use this.<br>
-Added a red pulse for ammo counts when you run low. This is primitive, for now.<br>

<h3>Beta 4</h3>
-Fixed for the Pyromania Update.<br>

<h3>Beta 3</h3>
-Finally found a health placement on the TargetID and FreezePanel frames that I liked.<br>

<h3>Beta 2</h3>
-Added a 6's, Highlander, and pub (32 player) scoreboard.<br>
-Slightly modified the freezecam (killed by) frame. I still don't like the health color/placement, though.<br>

<h3>Beta 1</h3>
-Moved the 'heads' counter for the demoman wielding the Eyelander and it's variants. This puts it out of the way of the TargetID panels.<br>
-Moved the Huntsman's charge meter to just above the Jarate meter (may be moved in the future).<br>
-The Spycicle meter is to the right of the cloak meter.<br>
-When disguised, the spy class icon shows behind and to the left of the health cross. This will always show the spy as red, regardless of who he is disguised as. This is the same for the default HUD, as well. It may change/be removed in the future.<br>
-The 'disguised as' panel is now above the cloak charge bar, and below the 'being healed by' TargetID frame.<br>
-All 'charge' items should now be in place.<br>

Known Bugs:<br>
-The engineer TargetID frame goes bananas when you move in range to pick up a building. Every custom HUD seems to have this problem, not sure what to do about it.<br>
-The spy disguise animation isn't centered on the spy icon.<br>
-Some of the charge labels are off center. I need to standarize these.<br>
-The killerframe name isn't in line with the targetid name.<br>
-The dueling panel is all sorts of busted.<br>

<h3>Alpha 2</h3>
-Added custom TargetID frames, cutting down on used real estate. They have been lowered to be out the middle of the screen. This works for both spectator and in game.<br>
-The demoman 'charge' meter (sticky bombs) was set to be far too wide, resulting in the meter being full at around 10% power. This has been fixed.<br>
<br>
<h3>Pre-Alpha</h3>
-Lots and lots of changes.<br>
<br>
<h2>Installation and removal</h2>

Download the latest file, and extract it into c:\Program Files(x86)\steam\steamapps\<b>youraccountname</b>\team fortress 2\tf\<br>
<br>
To remove: Delete the resource and script folders. Then start TF2, and close it cleanly. This will rebuild the HUD to it's default state.<br>
<br>
<h2>Known Issues</h2>

-The overheal/health low indicator is off by a pixel or two.<br>
-The ubercharge% on targetID frames are close to the demoman's head counter.<br>
-The Vaccinator resist icons kind of suck.