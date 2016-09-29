
batclient_triggers
==================
Most of these triggers are in barely working condition, they work for me, but there has been some problems atleast with entity_rep_counter and hit_ranker, maybe they interfere with some other triggers or maybe its bug, dunno.

It would be best if you knew enough about scripting to fix the errors and modify the trigs for your needs.


bm.bcs - Beastmaster, shows when ride underground/through xx was last used and some lites etc.

bph.bcs - Bard play script, read lines from file and send to mud on keypress.

entity_rep_counter.bcs - Turns entity rep symbols to numbers and shows levels in gem entity type.

fn.bcs - Item numbers to pro forges, unneeded since forges got this feature.

hit_ranker.bcs - Ranks melee hits, shows (x/26) after the hit.

kbh_help.bcs - Shows percentages in kbh messages with some lites, bit buggy.

libe_ghost_count.bcs - Shows count of ghosts by power and profession. <a href="https://github.com/celoko/batclient_triggers/blob/master/libe_ghost_count.bcsi"></a>

lite_mineral.bcs - Lites multiple minerals and helps to notice deposits.

mage_analyze.bcs - Reports monster resists, works with mage, folke and channu spells.

mh.bcs - Heel message handler for beastmasters. 

pl.bcs - Gets npc pirate ship names from ship scan and puts them to aliases.

plantlore_book.bcs - Script that shows plant season and location info.

taming.bcs - Shows success/fails etc. when taming animals. Helps figuring out how well you are doing.



How to install scripts
======================
Save file to batclient/scripts directory and restart client or do /scriptreload and /scriptbootup
