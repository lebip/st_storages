# List of complete main storages

This is a list of the complete main storages that have been published in the Storage Tech Discord server. As a list, it's meant to be complete and informative, providing enough data to allow you to choose what storages try out or eventually build in your survival world. Storages posted outside this server, deemed outdated by the creators, completely broken or requested not to be posted here won't be part of this list. If a working and finished system is missing, info is incomplete or outdated, let us know.

For the end user, a storage is often (but not always) a combination of *multi item sorting* (multiple item types in the same chests, often called "MIS"), *chest halls* (a single item type in limited capacity for each chest) and *Bulk* (a single item type stored in shulker boxes for each pile of chests, ensuring high capacity and density. Bulk often - but not always - means *box sorting*, as the boxes are sorted in the correct slices without being unloaded first). A storage may have all three of them, only some of them, or even take advantage of a hybrid of the functionality of the mentioned above.  

# Notes / FAQ

- **If you're a complete redsone beginner or simply overwhelmed by the amount of options, pick something from the multi item sorting section, such as the compact categorizer.** 
- All storages accept any item even if not capable of sorting it, *only the renamed items used when building should never be put in the input*. 
- **Assume that every redstone machine breaks when "unloaded" during operation. This means you should never leave the area without a chunkloader active, or close the world in single player. Once the storage is done sorting, it's safe to log off.**
- All storage systems require some inventories to be correctly filled. When using litematica, you can press "i" to see what the content of a storage block is supposed to look like. Familiarize with the system you chose in the world download before building it in survival mode. Unless you're extremely careful and used to build redstone machines, expect to make mistakes when building. Use the schematic verifier function, triple check the inventories, don't pick a storage you won't be comfortable troubleshooting, and, before asking in the help threads, use the search function as your question was likely answered before.
- Many storages must be aligned with chunk borders, which you can see by pressing f3+g.
- As storages are usually chunkloaded and work in the meantime you do other stuff, the speed they sort at isn't the only metric to take into account. 1x hopper speed means a full shulker box takes ~12 minutes; 8x hopper speed is more than enough speed for everyone. Consider your inputs and the projects you do in your world (how many shulker boxes do you sort when coming back from a project? 1? 20? 100?) then choose accordingly.
- None of these storage systems is guaranteed to work on paper/spigot/folia/whatever modified server. If you're playing on a public server that doesn't allow chunkloaders or periodically clears item entities, then said server is also very likely to disrupt normal redstone behaviour in the disingenuous attempt of reducing lag, and there's nothing we can do about that.
- Lithium and Enhanced Block Entities are two very useful mods for fabric that reduce the lag storage systems cause, without altering game mechanics. The first optimizes the server side, reducing, for instance, static hopper lag. The latter improves the fps when there are a lot of chests to render.
- A safe way of using stacked shulker boxes is carpet mod with the rule /carpet stackableShulkerBoxes=true and, since 1.21, the additional mod StackableShulkersFix. Other ways, such as using the function included in tweakeroo, can break storage systems.

# Multi Item Sorting

## [1.19+] Compact Categorizer

By Inspector Talon and metamilo

A barebones multi item sorter that sacrifices speed and advanced features for simplicity. Targeted to beginners.

- **What does it sort?** Sorts only stackable items (no shulker box unloader) into columns of chests; each column or category (1-wide) can hold up to 23 or 50 item types depending on the version chosen.
- **Sorting speed:** up to ~2/3 hopper speed - 6000 items/hour - speed depends on how many slices are built.
- **Size:** 17x18x27 - 2236 blocks (smaller version) 
- **Extra features:** none, it just sorts.
- **testing and known issues:** the world download has [some artifacts](https://discord.com/channels/748542142347083868/1151464188787576853/1353796836342632579) . Tested by the creators. No chunkloading included.
- [**Original post (13/09/2023)**](https://discord.com/channels/748542142347083868/749137424684285992/1151464188787576853)
- [**Download link (latest update)**](https://discord.com/channels/748542142347083868/1151464188787576853/1342278082383581245)
- [**Youtube video**](https://www.youtube.com/watch?v=DnrAoKd8ZOc)
- [**Help thread:**](https://discord.com/channels/748542142347083868/1291785785707856026/1291785785707856026)

## [1.16+] Simple multi-item sorter

By UnnervingS

A full system using MIS v4.2.

- **What does it sort?** Sorts stackable items and unloads the contents of shulker boxes; each column or category (2-wide) can sort up to 54 item types. 24 categories.
- **Sorting speed:** ~hopper speed - almost 9000 items/hour.
- **Size:** 34x32x31 - 4639 blocks
- **Extra features:** Chunkloader included.
- **testing and known issues:** No known issues. Tested by the creator. The unsorted/overflow slice should be cleared before it fills up completely as it lacks protection. The multi item sorter used isn't the most recent version.
- [**Original post (11/06/2022)**](https://discord.com/channels/748542142347083868/985217000232087593/985218457463316510)
- [**Download link (latest update)**](https://discord.com/channels/748542142347083868/985217000232087593/988473035294117888)

## [1.19+] Scorpio MIS

by Scorpio

A barebones multi item sorter using hopper carts.

- **What does it sort?** Sorts only stackable items and unloads the content of shulker boxes. each MIS category (1-wide) can hold up to 50 item types.
- **Sorting speed:** up to 2.4x hopper speed.
- **Size:** 25x24x31 - 5083 blocks (undecorated version) 
- **Extra features:** chunkloader and small restock station included.
- **testing and known issues:** [broke during testing]( https://discord.com/channels/748542142347083868/1379029443733094513/1388670755813982292). The unsorted/overflow slice should be cleared before it fills up completely as it lacks protection. 
- [**Original post (02/06/2025), download link and youtube video**](https://discord.com/channels/748542142347083868/749137424684285992/1379029443733094513)



# Multi Item Sorting + Bulk

This section contains storage systems that, alongside MIS, are capable of sorting a given number of single item types densely inside shulker boxes.


## [1.16+] J-MIS v3

By JayRoi

A full system pairing MIS v5.1 and hybrid shulker box loaders (which start loading the assigned item into boxes only after filling a chest).

- **What does it sort?** Sorts stackable items and unloads the contents of shulker boxes; each column or category (1-wide) can sort up to 54 item types. 32 categories; also sorts up to 32 item types into chests and shulker boxes.
- **Sorting speed:** ~hopper speed - almost 9000 items/hour.
- **Size:** 29x33x29 - 11499 blocks
- **Extra features:** Chunkloader included. The shulker boxes partially filled can be called from the UI. There is a small restock station, a pause lever and a function to flush items stuck in the inaccessible MIS droppers (useful for debug). Safety features such as automatic pausing in case of overflow full.
- **testing and known issues:** No known issues. Tested by the creator.
- [**Original post (08/12/2023)**](https://discord.com/channels/748542142347083868/749137424684285992/1182780067164717197)
- [**Download link (latest update)**](https://cdn.discordapp.com/attachments/1182780067164717197/1234329599165337621/J-M-IS_V3.01.zip?ex=68f99205&is=68f84085&hm=26dd35967eb1be2c801b6f631a844cec571115502df369a511204f06b779e3f0&)
- [**Help thread**](https://discord.com/channels/748542142347083868/1182775318830907412)

## [1.19+] YAMIS

By Etikle and skyzy

A full system pairing NoisyMIS and shulker box loaders.

- **What does it sort?** Sorts stackable items and unloads the contents of shulker boxes; each column or category (2-wide) can sort up to 54 item types. 32 categories; also sorts up to 64 item types into shulker boxes.
- **Sorting speed:** ~hopper speed - almost 9000 items/hour.
- **Size:** 29x21x49 - 17610 blocks.
- **Extra features:** Chunkloader included. The shulker boxes partially filled can be called from the UI. There is a nether portal for player use and a pause lever.
- **testing and known issues:** No known issues. Tested by the creators. Noisy and laggy on low end hardware due to clocking pistons. The unsorted/overflow/unstackable slice should be cleared before it fills up completely as it lacks protection. The box calling function should be clicked only once and never when the system is active, as it can easily break if spammed or spit out loose items if the the slice is currently loading items.
- [**Original post (16/04/2025)**](https://discord.com/channels/748542142347083868/749137424684285992/1361920281634930718)
- [**Download link (latest update)**](https://discord.com/channels/748542142347083868/1361920281634930718/1402919604078116884)
- [**Help thread**](https://discord.com/channels/748542142347083868/1275462763791126558)

## [1.19+] G-MIS v2.1

by GanglesXIII

A full storage system combining MIS v4.2 and single item type box sorting.

- **What does it sort?** Sorts stackable items and unloads the contents of shulker boxes; each column or category (1-wide) can sort up to 54 item types; also sorts up to 54 item types into shulker boxes; if a secondary input is added, can sort full boxes without unloading them. Sorts also some non-stackable items.
- **Sorting speed:** up to 9x hopper speed under optimal conditions, ~1x hopper speed on average.
- **Size:** 57x86x84 - 34515 blocks (decorated version).
- **Extra features:** Chunkloaders and unstackable sorter included. Safety features
- **testing and known issues:** Unreliable unstackable sorter. A high number of MIS 4.2 slices in use can be laggy on low end hardware due to clocked dust lines. The bulk section stores partially filled boxes, as chosen by the creator to not make any item inaccessible. If the overflow section for unstackables fills up completely, items are dropped into lava. The pleasure of doing so is left to the user in case of overflow from bulk/MIS. No protection if the unsorted items section completely fills up.
- [**Original post (28/01/2023)**](https://discord.com/channels/748542142347083868/749137424684285992/1068739913178157076)
- [**Download link (latest update)**](https://discord.com/channels/748542142347083868/833152072618606652/1080307180076544020). The post includes a link to a youtube video and a help thread.

## [1.21+] XianyuMIS v2

By siderXD, Capybruh

A full storage system combining single item type box sorting and a hopper cart based multi item sorter.

- **What does it sort?** Sorts stackable items and unloads the contents of shulker boxes; each column or category (1-wide) can sort up to 50 item types. Up to 41 item types are sorted into shulker boxes. If a secondary input is added, can sort full boxes without unloading them. Sorts also some non-stackable items.
- **Sorting speed:** up to 9,7x hopper speed under optimal conditions, averaging at 4x hopper speed.
- **Size:** 66x39x58 - 40679 blocks (decorated version); 47x28x45 - 15052 blocks (without decoration)
- **Extra features:** Chunkloaders and unstackable sorter included.
- **testing and known issues:** No known issues. Tested by the creators. Both the box loaders for the bulk section and the MIS reset item lifetime using hopper carts. The overflow section should be emptied before it fills completely otherwise items and boxes can despawn, but even in that case the system doesn't break.
- [**Original post (16/10/2025)**](https://discord.com/channels/748542142347083868/749137424684285992/1428167044087677050)
- [**Download link (latest update)**](https://discord.com/channels/748542142347083868/1428167044087677050/1428230013102329968)
- [**Help thread**](https://discord.com/channels/748542142347083868/1430084216292511784)

## [1.19+] CartMIS v3

by Inspector Talon, RaPsCaLlioN1138, Christone

A complete hopper cart based storage, pairing 32 CartMIS categories with 216 *hybrid box loaders* (which start loading the assigned item into boxes only after filling a chest).

- **What does it sort?** Sorts stackable items and some non-stackable items as well. Each MIS category (1-wide) holds up to 50 different item types.
- **Sorting speed:** Up to 16x hopper speed (144000 items/hour)
- **Size:** 128x47x68 - 43100 blocks
- **Extra features:** Unstackable sorting, chunkloaders, small status indicators panel.
- **testing and known issues:** No known issues. Tested by the creators. Some rail placements can be tricky to build. The unsorted/overflow slice should be cleared before it fills up completely as it lacks protection.
- [**Original post (16/06/2024)**](https://discord.com/channels/748542142347083868/749137424684285992/1251974389088391259)
- [**Download link (latest update)**](https://discord.com/channels/748542142347083868/1251974389088391259/1339736798930272266)
- [**Youtube video**](https://www.youtube.com/watch?v=9eHcvMi7HUw)
- [**Help thread**](https://discord.com/channels/748542142347083868/1252114876625584239)


# Multi Item Sorting + Chest Halls + Bulk

The storages in this section are usually scaled to the needs of technical minecraft servers or *very advanced* single player worlds.

## [1.17+] Krebs' Main Storage System

by Krebs

A complete main storage system originarily made for Ingenium SMP

- **What does it sort?** Accepts boxes and items. If a secondary input is added, is capable of sorting full boxes without unloading them. 544 chest hall items, 90 bulk items, 10 MIS categories holding up to 54 item types each.
- **Sorting speed:** up to 8x hopper speed - (72000 items/hour) unloading shulker boxes in parallel.
- **Size:** 114x101x109 - 93156 blocks
- **Extra features:** Unstackable sorting, chunkloading, crafting station, furnace array, micro farms, big control panel, possibility to chunkload with a bot for use in the End dimension, many safety features.
- **testing and known issues:** No known issues. Some components used are functional but not up to date (unstackable sorter, parallel unloader, MIS, mixed loaders used for overflow) Fully tested and reviewed by an Archive Curator. As chosen by the creator, there isn't a player-accessible input to sort full boxes without unloading them.
- [**Archive post with download**](https://discord.com/channels/748542142347083868/833152072618606652/1083907230023295066)

## [1.20+] Yams v2
by Etikle, basil, skyzy

A complete and up to date main storage system coming in two versions: mini bulk and full bulk.

- **What does it sort?** Accepts boxes and items, depending on the version used is capable of sorting full boxes without unloading them. 640 chest hall items, 128 bulk items, 10 MIS categories holding up to 54 item types each.
- **Sorting speed:** up to 16x hopper speed (144000 items/hour) unloading shulker boxes in parallel.
- **Size:** 208x76x176 - 108957 blocks (full bulk, undecorated version)
- **Extra features:** basic safety features, chunkloading, furnace array, restock station, yeeting station, small control panel and status indicators. The mini bulk version allows calling partially filled boxes from the UI.
- **testing and known issues:** No known issues. Tested by the creators. Several issues were fixed after Archive Curator feedback. The box calling function should be clicked only once and never when the system is active, as it can easily break if spammed or spit out loose items if the the slice is currently loading items.
- [**Original post (16/07/2024)**](https://discord.com/channels/748542142347083868/749137424684285992/1262854684037611600)
- [**Download link (latest update)**](https://www.mediafire.com/folder/vlg6rvssbth2q/YAMS)
- [**Help thread**](https://discord.com/channels/748542142347083868/1182775318830907412)

# Other/Advanced

This section contains storage system that are unique and don't fall in either of the previous sections, or are so advanced that you shouldn't consider building them, unless you're already an expert of the field playing in a big techincal server. 

## [1.19+] SciCraft Main Storage

by jorvp, Obi

A complete hybrid encoded storage system made for SciCraft SMP. Uses three hybrid halls, combining normal chest halls and shulker boxes restocked from a remote bulk storage.

- **What does it sort?** Stackable items, boxes, full boxes, some non-stackable items. 384 bulk items, 768 chest hall items. No multi item sorter.
- **Sorting speed:** up to 16x hopper speed (144000 items/hour) unloading shulker boxes in parallel.
- **Size:** Very big. Almost 190000 blocks (not counting remote bulk).
- **Extra features:** many safety features, player call from remote bulk, unstackable sorting, yeeting station, crafting station, restock station, mass crafter with huge loader array, status indicators, suspicious lack of a potion brewer.
- **testing and known issues:** Tested by the creators and used in SMP for over a year. No known issues.
- [**Original post, download link and youtube video**](https://discord.com/channels/748542142347083868/1189010750606426132/1189012529284919296)
