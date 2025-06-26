# THIRD UPGRADE MOD(TUM) ENCHANTED 2.7.2
**MULTIPLAYER OVER NETWORK (TCP/IP) IS SUPPORTED!**  
Now you can enjoy playing TUM Enchanted with your friends far away!  
  
**TUM ENCHANTED NOW FEATURES ADVENTURE AI IMPROVEMENTS!**  
This will cause AI to make *smarter* choices and to be more aggressive without cheating! And is also *faster*!  
For a complete and detailed list of all AI improvements refer to [AI Improvements.txt](https://github.com/SadnessPower/TUM-Enchanted/blob/main/AI%20Improvements.txt)    

> [!NOTE]  
> - For bug reports you can post on the TUM Enchanted Discord Channel (see Section "Feedback") or write an email to [SadnessPower](mailto:fallenstar268@icqmail.com)


## LATEST CHANGELOGS  
**GENERAL**  
- Configurable max AI Heroes for difficulty level (see Lang/AI.json).
  
**ADVENTURE AI**  
- Treasure Chest choice: Now AI will always choose XP for the strongest hero until level 10, then gold (see AI Improvements.txt for other cases).
  
**BATTLE AI** 
- PROTECTION FROM FIRE/EARTH/AIR/WATER: Score is now divided by the number of useful spells enemy hero can cast. This will result in AI casting this spell much rarely.
- SUMMON FIRE/EARTH/AIR/WATER: No more suboptimal summoning of elementals with ACM! If ACM is enabled, AI will evaluate it by using ACM summoning calculation.

<-------- 2.7.1 -------->   
  
**GENERAL**  
- Added mod incompatibility for the new Mod Manager.  
  
**ADVENTURE AI**  
- AI is smarter and FASTER now! Implemented an optimization mechanism which speeds up AI turn while maintaining the same quality!  
- Implemented separate thinking radius for heroes in explore mode and normal mode.  
  
**BATTLE AI** 
- DISPEL: Fixed vanilla bug which prevented AI to calculate benefits for dispelling friendly units. Now AI will use dispel more often!  
- Implemented AI code for correctly evaluating removing Blind and Hypnotize.  
  
<-------- 2.7 -------->  
  
**IMPROVEMENTS**  
- Now TUM Enchanted is compatible with WoG Graphics Fix!  
- WOG Option support for "Capitol can be built in every town".  
- If both TUM Enchanted and Third Upgrade Mod are both enabled, a pop-up message will be shown upon game start warning about incompatibity (thanks to Yuji Sakai).  
- Enabled again Soul Eater Animate Dead fix for cast requirement to match skill description (levels 1-5), instead of target stack HP.  
  
**AI IMPROVEMENTS**  
  
*ADVENTURE AI*  
- Now AI will go straight capturing towns he think he can beat if they are reachable in current turn, no matter what. No more distraction along the way, no more ignoring capturable towns!  
- AI will capture enemy towns even if there are stronger enemy heroes nearby, if he can safely run afterwards without being caught.  
- AI heroes now have +2 scouting radius to match human players' one. Vanilla AI scouting radius doesn't let AI seeing enemy towns which a human player could.  
- Now AI will always use max search distance set by UN:J4. WOG implemention for that trigger was incomplete, leading to rarely using max search distance.  
- Fixed vanilla AI behaviour sometimes leading to pass turn on heroes which still have movement points left (this occured a lot when entering monoliths, but not only that).  
- Now AI will not pass turn with full movement points when he cannot find a path for escaping a stronger enemy hero. Instead (this is experimental) will run instead, and if he cannot, will act normally.  
- (Experimental) Now AI will defend his towns taking in consideration also adventure spells which can be cast by enemy (Fly, Dimension Door, Town Portal, Water Walk, etc)  
  
*BATTLE AI*  
- HYPNOTIZE casting value reworked. It will result in AI casting or dispelling Hypnotize more often (see AI Improvements.txt for more details).   
  
**BUG FIXES**  
- Increased mod priority to fix drawing errors and wrong graphic when HD Remastered Edition Mod is enabled.  
- Fixed unupgraded creatures cannot be hired from towns sometimes when you have the corresponding TUM upgrade building built.  
- Fixed left click on small portraits in town shows wrong creatures to be hired.  
- Fixed Conflux dwelling didn't require a Fort to be built (thanks to Mmmihkel for reporting).  
- Fixed pop-up message in town upon granting +1 primary skill didn't show the picture of the granted skill.  
 
 
-----------------------------------------------------------------------------------------------------------------------
MAIN FEATURES
------------------------------------------------------------------------------------------------------------------------ 
![](https://raw.githubusercontent.com/SadnessPower/TUM-Enchanted/main/Assets/attr_attack.webp) All dwelling can be upgraded a second time! AI will do that as well  
![](https://raw.githubusercontent.com/SadnessPower/TUM-Enchanted/main/Assets/logo_homm3_sod.webp) Every faction has a theme and unique strategy  
![](https://raw.githubusercontent.com/SadnessPower/TUM-Enchanted/main/Assets/logo_homm3_wog.webp) Rebalanced nearly all units (low level units are now useful!)   
![](https://raw.githubusercontent.com/SadnessPower/TUM-Enchanted/main/Assets/AI_Combat.webp) Combat AI has been improved (you can Quick Combat most of the time!)  
![](https://raw.githubusercontent.com/SadnessPower/TUM-Enchanted/main/Assets/AI_Adventure.webp) Adventure AI is smarter and more aggressive!  
![](https://raw.githubusercontent.com/SadnessPower/TUM-Enchanted/main/Assets/art_holy_grail.webp) Buildings dependencies and costs are changed (Cyclops Cave do not cost 1 kidney anymore)  
![](https://raw.githubusercontent.com/SadnessPower/TUM-Enchanted/main/Assets//art_angel_wings.webp) Now hero movements points are based on the fastest stack (yes, now you can carry zombies with you)  
![](https://raw.githubusercontent.com/SadnessPower/TUM-Enchanted/main/Assets/art_spellbinders_hat.webp) Factions without Mage Guild Level 5 have other bonus  
![](https://raw.githubusercontent.com/SadnessPower/TUM-Enchanted/main/Assets/logo_homm3_era.webp) Over 100 new unique skills for creatures (see Skills Overview.pdf for a complete description)  
![](https://raw.githubusercontent.com/SadnessPower/TUM-Enchanted/main/Assets/attr_defence.webp) Neutral Towns are well defended and challenging  
![](https://raw.githubusercontent.com/SadnessPower/TUM-Enchanted/main/Assets/art_endless_sack_of_gold.webp) Towns produce more golds  
..and many more!  
  
-----------------------------------------------------------------------------------------------------------------------
FEEDBACK
-----------------------------------------------------------------------------------------------------------------------
For general feedback, balance suggestions and bug report you can join the HoMM 3.5 ERA Mods discord server:  
[Discord Server](https://discord.gg/hCTMfVq6w5)  
and contact us in the following channel:  
[TUM Enchanted Channel](https://discord.com/channels/665742159307341827/1232146926078787644)  


-----------------------------------------------------------------------------------------------------------------------
CREDITS
-----------------------------------------------------------------------------------------------------------------------
Diozia - *Balance Designer*  
SadnessPower - *Bugfix and Scripting*  

Special thanks to:  
FirePaladin, FanofHeroes, Aphra, Toriko and Максэ1379 - *Graphics*  
Majaczek - *Plugins (Amethyst & New Towns)*  
Archer30 - *ERM author and scripting*  
Maiko - *TUM Lite Creator*    

-----------------------------------------------------------------------------------------------------------------------
NEW SKILLS
-----------------------------------------------------------------------------------------------------------------------

[Comprehensive Skill List](https://github.com/SadnessPower/TUM-Enchanted/blob/84857b018696bc23325dba1aedc1bd02d11a3746/Skills%20Overview.pdf)
