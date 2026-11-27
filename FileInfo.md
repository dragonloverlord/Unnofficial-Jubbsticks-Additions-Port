Unofficial Jubbsticks Additions Port
Thank you for downloading!
---

NOTE: Before you do anything, please make a backup of your game, just to be safe. Also, keep in mind that removing or disabling the mod will *permanently* delete any added items you may have obtained (items from the mod), so you should definitely backup your island if you plan to disable the mod and you want to be able to recover your items.

---
Common-Conflicts:

Bcsv
 - FgMainParam.bcsv - This file is necessary for new trees to work.
 - ItemKind.bcsv - This file is necessary for items to stack to 99, and for manila clams to stack.
 - ItemOutfitInfo.bcsv - This file is necessary for the new tool types to be unbreakable.
 - ItemParam.bcsv - This file is VERY important, it includes item data for every new item.
 - ItemRemake.bcsv - This file allows for all the added customization options.  

EventFlow
 - Ftr_Working.bfevfl - This file is necessary for Bulk Crafting fish bait.
 - SNPC_rcm_11_BuyDIYbook.bfevfl - This file is necessary for the Super Smoothies Recipes to be purchasable in the nook's cabinet.  
 - The mod also replaces these vanilla flows, so they conflict with any other mod that ships the same file:
   AI_NPC_Doc_CommuneIsland, AI_NPC_Poo_Commune, AI_NPC_Slo_Visit, AI_NPC_Spn_Commune, Demo_Common_Commune, Demo_PublicAnnouncement, Ftr_Bromide, NNPC_Select_Creature, NNPC_Talk_General, Obj_RcoMachine_MileExchange, Player_GetDemo, Player_GetDemo_Once, Player_GetDemo_Recipe_DIY, Player_ToolBreak, SNPC_bpt_03_Commune_TodaysFortune, SNPC_doc_52_CommuneIsland, SNPC_fox_11_Commune_Lorrery, SNPC_hgc_01_NowQuest, SNPC_pck, SNPC_pge, SNPC_pge_02_Takeout, SNPC_rcm_21_MaterialCollecting, SNPC_rcm_24_MaterialGiveProcess, SNPC_slo_00_Peddling, SNPC_slo_02_Commune, SNPC_spn_12_Commune_ShopOpen, System_GrowUp_WeatherControl, Tutorials_Prologue_Tkk (all .bfevfl).  

Model
 - None of the files which may conflict with other mods in the Model folder are necessary for the mod to function. Feel free to replace the default models with whatever you like.  

System
 - ResourceSizeTable.srsizetable - PLEASE READ THE BELOW INFO
---

**IMPORTANT** RSTB Patch Info (ResourceSizeTable.srsizetable)  

The mod comes with an RSTB file (in the System folder) that is required to load it's model / texture changes. If you want to use any mod that adds or changes textures / models then you'll have to generate a new ResourceSizeTable.srsizetable to avoid crashing. This can be done with Heavens Tool amongst other tools.

---
