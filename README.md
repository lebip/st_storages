# List of complete main storages

This is a list of the complete main storages that have been published in the Storage Tech Discord server. As a list, it's meant to be complete and informative, providing enough data to allow you to choose what storages try out or eventually build in your survival world. Storages posted outside said server, deemed outdated by the creators, nonfunctional, unfinished or requested not to be posted here won't be part of this list. If a working and finished system is missing, info is incomplete or outdated, let us know.

For the end user, a storage is often (but not always) a combination of *multi item sorting* (multiple item types in the same chests, often called "MIS"), *chest halls* (a single item type in limited capacity for each chest) and *Bulk* (a single item type stored in shulker boxes for each pile of chests, ensuring high capacity and density. Bulk often - but not always - means *box sorting*, as the boxes are sorted in the correct slices without being unloaded first). A storage may have all three of them, only some of them, or even take advantage of a hybrid of the functionality of the mentioned above.  

# Notes / FAQ

- **If you're a complete redstone beginner or simply overwhelmed by the amount of options, pick something from the "multi item sorting" section, _such as the compact categorizer_. If you want something more, try the smaller storages (YAMIS, J-MIS) in the "multi item sorting + bulk" section.**
- All storages accept any item even if not capable of sorting it, *only the renamed items used when building should never be put in the input*. 
- **Assume that every redstone machine breaks when "unloaded" during operation. This means you should never leave the area without a chunkloader active, or close the world in single player. Once the storage is done sorting, it's safe to log off.**
- All storage systems require some inventories to be correctly filled. When using litematica, you can press "i" to see what the content of a storage block is supposed to look like. Familiarize with the system you chose in the world download before building it in survival mode. Unless you're extremely careful and used to build redstone machines, expect to make mistakes when building. Use the schematic verifier function, triple check the inventories, don't pick a storage you won't be comfortable troubleshooting, and, before asking in the help threads, use the search function as your question was likely answered before.
- Many storages must be aligned with chunk borders, which you can see by pressing f3+g.
- As storages are usually chunkloaded and work in the meantime you do other stuff, the speed they sort at isn't the only metric to take into account. 1x hopper speed means a full shulker box takes ~12 minutes; 8x hopper speed is more than enough speed for everyone. Consider your inputs and the projects you do in your world (how many shulker boxes do you sort when coming back from a project? 1? 20? 100?) then choose accordingly.
- None of these storage systems is guaranteed to work on paper/spigot/folia/whatever modified server. If you're playing on a public server that doesn't allow chunkloaders or periodically clears item entities, then said server is also very likely to disrupt normal redstone behaviour in the disingenuous attempt of reducing lag, and there's nothing we can do about that.
- Lithium and Enhanced Block Entities are two very useful mods for fabric that reduce the lag storage systems cause, without altering game mechanics. The first optimizes the server side, reducing, for instance, static hopper lag. The latter improves the fps when there are a lot of chests to render.
- A safe way of using stacked shulker boxes is carpet mod with the rule /carpet stackableShulkerBoxes=true and, since 1.21, the additional mod StackableShulkersFix. Other ways, such as using the function included in tweakeroo, can break storage systems.
- **To link correctly the chunkloaders, you must build each portal in the nether in the x and z coordinates of the corresponding portal in the overworld divided by 8, and at the same y level or as close a possible to that. Observe the world downloads to have a practical example to follow.**


# Multi Item Sorting

## [1.19+] Compact Categorizer

By Inspector Talon and metamilo

A barebones multi item sorter that sacrifices speed and advanced features for simplicity. Targeted to beginners.

<img width="2000" height="1897" alt="compact_categorizer_overview" src="https://github.com/user-attachments/assets/fc2f8deb-3c5a-49f1-9d43-e400af767e9a" />

<details>
<summary>Picture gallery - click to expand</summary>

input:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d134cf1b-f766-479d-a208-e430055e6b0b" />
UI:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ca4626c7-d6fd-4a55-a4f7-79763c6d157f" />

</details>

<details>
<summary>How to set the filters - click to expand</summary>

The filters of this system are these chests, also called whitelisters. Depending on the version chosen, barrels are used in the same way:

<img width="1920" height="1020" alt="2025-10-25_18 03 12" src="https://github.com/user-attachments/assets/dde16924-c9ee-4d6e-8a62-30d025af8bea" />


by default, the chest has three unstackables/full stacks and 55 64-stackable renamed items (which must never be put in the input):

<img width="511" height="408" alt="2025-10-25_18 04 25" src="https://github.com/user-attachments/assets/c369ee97-7be0-4769-a53e-f10aef737981" />


To add an item, place one sample in the chest and remove one of the renamed items:

<img width="519" height="399" alt="2025-10-25_18 04 30" src="https://github.com/user-attachments/assets/e5a156de-d5fd-433f-ba6d-24107f665231" />


To add items that only stack up to 16, remove 4 renamed items for each 16-stackable added to the chest:

<img width="518" height="411" alt="2025-10-25_18 04 37" src="https://github.com/user-attachments/assets/dd4eefe8-a2ae-48e0-a5c8-ef5147a37dd3" />


The procedure for barrels is the same:

<img width="521" height="255" alt="2025-10-25_18 06 27" src="https://github.com/user-attachments/assets/4b0438da-6e27-4fe9-838b-e8201537695c" />

**Remember to never add the same item to multiple slices.**

The hopper cart needs to be filled with 4 non stackable items, leaving the last slot empty:
<img width="529" height="400" alt="2025-10-25_18 05 27" src="https://github.com/user-attachments/assets/710f545b-7864-4250-9e18-24cc97c2e83d" />

</details>

- **What does it sort?** Sorts only stackable items (no shulker box unloader) into columns of chests; each column or category (1-wide) can hold up to 23 or 50 item types depending on the version chosen.
- **Sorting speed:** up to ~2/3 hopper speed - 6000 items/hour - speed depends on how many slices are built.
- **Size:** 17x18x27 - 2236 blocks (smaller version) 
- **Extra features:** none, it just sorts.
- **testing and known issues:** No known issues. The world download has [some artifacts](https://discord.com/channels/748542142347083868/1151464188787576853/1353796836342632579) . Tested by the creators. No chunkloading included.
- [**Original post (13/09/2023)**](https://discord.com/channels/748542142347083868/749137424684285992/1151464188787576853)
- [**Download link (latest update)**](https://discord.com/channels/748542142347083868/1151464188787576853/1342278082383581245)
- [**Youtube video**](https://www.youtube.com/watch?v=DnrAoKd8ZOc)
- [**Help thread:**](https://discord.com/channels/748542142347083868/1291785785707856026/1291785785707856026)

## [1.16+] Simple multi-item sorter

By UnnervingS

A full system using MIS v4.2.

<img width="1870" height="1202" alt="image" src="https://github.com/user-attachments/assets/e2f4bc55-dcbe-4e0f-9887-5a5a8c41dadc" />

<details>
<summary>How to set the filters - click to expand</summary>

The filters of this system are these chests:

<img width="1920" height="1020" alt="2025-10-25_18 31 05" src="https://github.com/user-attachments/assets/0602ee7c-0caf-483b-b5cb-0d419c632b5c" />



by default, the chest is completely filled with either renamed blockers or unstackable items. To assign an item to the slice, replace one of the blockers with **two** samples of the item:

<img width="517" height="418" alt="2025-10-25_18 31 23" src="https://github.com/user-attachments/assets/59ca2a55-2cc7-44fb-a1c4-d6e242b45001" />

When filling the hopper below the filter chests, rememeber to use **different** items!
<img width="516" height="393" alt="2025-10-25_18 31 35" src="https://github.com/user-attachments/assets/461c2c35-ca47-427c-832d-088781aa2a6a" />

</details>


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

<img width="870" height="501" alt="504684233-26608fdc-2aa0-4317-a980-087be627c7dc" src="https://github.com/user-attachments/assets/519b73f2-1e9c-4d21-8dad-bbbae61d22d6" />

<details>
<summary>How to set the filters - click to expand</summary>

The filters of this system are these chests, also called whitelisters.

<img width="1920" height="1020" alt="2025-10-25_18 42 21" src="https://github.com/user-attachments/assets/51ec84a4-23dc-4d62-83dc-e7d0350cc6af" />


by default, the chest has three unstackables/full stacks and 55 64-stackable renamed items (which must never be put in the input):

<img width="511" height="408" alt="2025-10-25_18 04 25" src="https://github.com/user-attachments/assets/c369ee97-7be0-4769-a53e-f10aef737981" />


To add an item, place one sample in the chest and remove one of the renamed items:

<img width="519" height="399" alt="2025-10-25_18 04 30" src="https://github.com/user-attachments/assets/e5a156de-d5fd-433f-ba6d-24107f665231" />


To add items that only stack up to 16, remove 4 renamed items for each 16-stackable added to the chest:

<img width="518" height="411" alt="2025-10-25_18 04 37" src="https://github.com/user-attachments/assets/dd4eefe8-a2ae-48e0-a5c8-ef5147a37dd3" />

The renamed items and the full stacks/unstackable items can be placed in different ways, there's no difference as long as the number is correct:

<img width="519" height="411" alt="2025-10-25_18 44 48" src="https://github.com/user-attachments/assets/55c11e53-8531-4646-8a02-fe996d84c8a1" /> <img width="519" height="411" alt="2025-10-25_18 45 59" src="https://github.com/user-attachments/assets/9ff76d98-cbe2-4769-b0af-62d27b6a5c2c" /> <img width="514" height="405" alt="2025-10-25_18 45 50" src="https://github.com/user-attachments/assets/de65f669-e044-4f38-9c5d-6c3cd6052f98" />

</details>

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

<img width="3840" height="3840" alt="image" src="https://github.com/user-attachments/assets/fc28b428-ec56-4ca0-af98-c70e1fe3995c" />

<details>
<summary>Picture gallery - click to expand</summary>

input:
<img width="1920" height="1020" alt="2025-10-23_19 29 27" src="https://github.com/user-attachments/assets/51f46182-ba7f-42e4-af54-ced4d086c3eb" />

UI:
<img width="1920" height="1020" alt="2025-10-23_19 29 15" src="https://github.com/user-attachments/assets/57a3bc3b-e41a-43fe-835b-35c875441d34" />


</details>

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

<img width="1124" height="638" alt="504685292-d14dd662-aeed-42ff-9248-9a41bc4072b2" src="https://github.com/user-attachments/assets/48b65311-e3a6-47fa-9971-297e1a5ba557" />

<details>
<summary>Picture gallery - click to expand</summary>

input:
<img width="1920" height="1020" alt="2025-10-23_19 31 46" src="https://github.com/user-attachments/assets/4a00c8b1-1f5f-4d61-8a4a-614318efd82e" />

UI:
<img width="1920" height="1020" alt="2025-10-23_19 31 57" src="https://github.com/user-attachments/assets/2cfb7feb-2dc8-4605-bad3-1882feafefdd" />
<img width="1920" height="1020" alt="2025-10-23_19 32 08" src="https://github.com/user-attachments/assets/2f1349ad-60a7-4052-ad11-7308e24d643b" />



</details>


- **What does it sort?** Sorts stackable items and unloads the contents of shulker boxes; each column or category (2-wide) can sort up to 54 item types. 32 categories; also sorts up to 64 item types into shulker boxes.
- **Sorting speed:** ~hopper speed - almost 9000 items/hour.
- **Size:** 29x21x49 - 17610 blocks.
- **Extra features:** Chunkloader included. The shulker boxes partially filled can be called from the UI. There is a nether portal for player use and a pause lever.
- **testing and known issues:** No known issues. Tested by the creators. Noisy, and laggy on low end hardware due to clocking pistons. The unsorted/overflow/unstackable slice should be cleared before it fills up completely as it lacks protection. The box calling function should be clicked only once and never when the system is active, as it can easily break if spammed or spit out loose items if the the slice is currently loading them.
- [**Original post (16/04/2025)**](https://discord.com/channels/748542142347083868/749137424684285992/1361920281634930718)
- [**Download link (latest update)**](https://discord.com/channels/748542142347083868/1361920281634930718/1402919604078116884)
- [**Help thread**](https://discord.com/channels/748542142347083868/1275462763791126558)

## [1.21+] XianyuMIS v2

By siderXD, Capybruh

A full storage system combining single item type box sorting and a hopper cart based multi item sorter.

<img width="1414" height="1111" alt="504685686-4febab3d-49e8-4e79-b765-269e61007877" src="https://github.com/user-attachments/assets/1ff9fdd5-3fc5-4b64-bc43-5d0ecd869337" />

<details>
<summary>Picture gallery - click to expand</summary>

input:
<img width="1920" height="1020" alt="2025-10-23_19 33 33" src="https://github.com/user-attachments/assets/a14b7092-6213-49ef-876f-6df145f04889" />

UI:
<img width="1920" height="1020" alt="2025-10-23_19 33 17" src="https://github.com/user-attachments/assets/9ed9cb46-a39d-4322-af50-b13aa8411f8e" />
<img width="1920" height="1020" alt="2025-10-23_19 33 52" src="https://github.com/user-attachments/assets/f449eedd-b9ee-45a7-8b93-ffdc9a777d8d" />



</details>


- **What does it sort?** Sorts stackable items and unloads the contents of shulker boxes; each column or category (1-wide) can sort up to 50 item types. Up to 41 item types are sorted into shulker boxes. If a secondary input is added, can sort full boxes without unloading them. Sorts also some non-stackable items.
- **Sorting speed:** up to 9,7x hopper speed under optimal conditions, averaging at 4x hopper speed.
- **Size:** 66x39x58 - 40679 blocks (decorated version); 47x28x45 - 15052 blocks (without decoration)
- **Extra features:** Chunkloaders and unstackable sorter included.
- **testing and known issues:** No known issues. Tested by the creators. Both the box loaders for the bulk section and the MIS reset item lifetime using hopper carts. The overflow section should be emptied before it fills completely otherwise items and boxes can despawn, but even in that case the system doesn't break.
- [**Original post (16/10/2025)**](https://discord.com/channels/748542142347083868/749137424684285992/1428167044087677050)
- [**Download link (latest update)**](https://discord.com/channels/748542142347083868/1428167044087677050/1428230013102329968)
- [**Help thread**](https://discord.com/channels/748542142347083868/1430084216292511784)

## [1.19+] G-MIS v2.1

by GanglesXIII

A full storage system combining MIS v4.2 and single item type box sorting.

<img width="1741" height="1100" alt="area_render_6_" src="https://github.com/user-attachments/assets/330f8a64-eefb-4f6b-925e-311145fe425f" />

<details>
<summary>Picture gallery - click to expand</summary>

input:
<img width="1920" height="1020" alt="2025-10-23_19 38 15" src="https://github.com/user-attachments/assets/96c644d7-8582-47db-b7a2-5868793ca18e" />

UI:
<img width="1920" height="1020" alt="2025-10-23_19 38 40" src="https://github.com/user-attachments/assets/4694232c-3502-43e9-9c72-a0886f59af32" />
<img width="1920" height="1020" alt="2025-10-23_19 38 47" src="https://github.com/user-attachments/assets/fb737829-d125-48fb-8b08-4a7941e30f01" />
<img width="1920" height="1020" alt="2025-10-23_19 39 01" src="https://github.com/user-attachments/assets/571b892a-7caa-44a2-8e08-66ddc2f60916" />



</details>


- **What does it sort?** Sorts stackable items and unloads the contents of shulker boxes; each column or category (1-wide) can sort up to 54 item types; also sorts up to 54 item types into shulker boxes; if a secondary input is added, can sort full boxes without unloading them. Sorts also some non-stackable items.
- **Sorting speed:** up to 9x hopper speed under optimal conditions, ~1x hopper speed on average.
- **Size:** 57x86x84 - 34515 blocks (decorated version).
- **Extra features:** Chunkloaders and unstackable sorter included. Safety features
- **testing and known issues:** Unreliable unstackable sorter. A high number of MIS 4.2 slices in use can be laggy on low end hardware due to clocked dust lines. The bulk section stores partially filled boxes, as chosen by the creator to not make any item inaccessible. If the overflow section for unstackables fills up completely, items are dropped into lava. The pleasure of doing so is left to the user in case of overflow from bulk/MIS. No protection if the unsorted items section completely fills up.
- [**Archival post**](https://discord.com/channels/748542142347083868/833152072618606652/1080307180076544020). The post includes a link to a youtube video and a help thread.


## [1.19+] CartMIS v3

by Inspector Talon, RaPsCaLlioN1138, Christone

A complete hopper cart based storage, pairing a hopper-cart based MIS with *hybrid box loaders* (which start loading the assigned item into boxes only after filling a chest).

<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/9c18d345-7d06-4689-89a7-d2feb00a9cdd" />

<details>
<summary>Picture gallery - click to expand</summary>

input:
<img width="1920" height="1020" alt="2025-10-23_19 36 06" src="https://github.com/user-attachments/assets/53be6ab7-8310-4afa-a050-e94f109bd295" />


UI:
<img width="1920" height="1020" alt="2025-10-23_19 36 14" src="https://github.com/user-attachments/assets/79de7652-4d39-453c-a90d-805ac9fdb6ef" />
<img width="1920" height="1020" alt="2025-10-23_19 36 22" src="https://github.com/user-attachments/assets/6639545b-81b2-4ecc-b4e1-c4fd0d2ce245" />
<img width="1920" height="1020" alt="2025-10-23_19 36 28" src="https://github.com/user-attachments/assets/f1d701dc-7b2b-4026-aed4-91d1c3d9f0ff" />



</details>

- **What does it sort?** Sorts stackable items and some non-stackable items as well. Each of the 32 MIS category (1-wide) holds up to 50 different item types. There are 216 hybrid box loaders holding a single item type.
- **Sorting speed:** Up to 16x hopper speed (144000 items/hour)
- **Size:** 128x47x68 - 43100 blocks
- **Extra features:** Unstackable sorting, chunkloaders, small status indicators panel.
- **testing and known issues:** No known major issues. Tested by the creators. Some rail placements can be tricky to build. The unsorted/overflow slice should be cleared before it fills up completely as it lacks protection. The user should stick around until the chunkloading light turns on aftern inputting items and when sorting boxes directly into the bulk.
- [**Original post (16/06/2024)**](https://discord.com/channels/748542142347083868/749137424684285992/1251974389088391259)
- [**Download link (latest update)**](https://discord.com/channels/748542142347083868/1251974389088391259/1339736798930272266)
- [**Youtube video**](https://www.youtube.com/watch?v=9eHcvMi7HUw)
- [**Help thread**](https://discord.com/channels/748542142347083868/1252114876625584239)


# Multi Item Sorting + Chest Halls + Bulk

The storages in this section are usually scaled to the needs of technical minecraft servers.

## [1.20+] Yams v2
by Etikle, basil, skyzy

A complete and up to date main storage system coming in two versions: mini bulk (MB) and full bulk (FB).

<img width="2000" height="2000" alt="area_render_5_" src="https://github.com/user-attachments/assets/7edc565a-d644-48e0-a5e2-b9ef6008bb63" />

<details>
<summary>Picture gallery - click to expand</summary>

input:
<img width="1920" height="1020" alt="2025-10-23_19 41 38" src="https://github.com/user-attachments/assets/d260bd2c-69ed-4735-ba3d-821877fa6b6d" />

UI:
<img width="1920" height="1020" alt="2025-10-23_19 41 15" src="https://github.com/user-attachments/assets/6ce06784-dfc3-488a-a32b-2a343a258819" />
<img width="1920" height="1020" alt="2025-10-23_19 41 51" src="https://github.com/user-attachments/assets/021da9f6-f4e7-498a-b8e2-da87d18303b0" />
<img width="1920" height="1020" alt="2025-10-23_19 41 57" src="https://github.com/user-attachments/assets/863b4f69-b94d-44d4-b6d6-0136a0876d3d" />
<img width="1920" height="1020" alt="2025-10-23_19 42 02" src="https://github.com/user-attachments/assets/f0b120a2-91e3-4fc0-bbd5-7b159e783303" />
<img width="1920" height="1020" alt="2025-10-23_19 41 04" src="https://github.com/user-attachments/assets/597a9009-617e-43a7-bcf4-5b02c62c5525" />


</details>


- **What does it sort?** Accepts boxes and items, depending on the version used is capable of sorting full boxes without unloading them. 640 chest hall items, 128 bulk items, 10 MIS categories holding up to 54 item types each.
- **Sorting speed:** up to 16x hopper speed (144000 items/hour) unloading shulker boxes in parallel.
- **Size:** 108x75x114 - 78493 blocks (full bulk, undecorated version - not counting glass floor)
- **Extra features:** basic safety features, chunkloading, furnace array, restock station, yeeting station, small control panel and status indicators. The mini bulk version allows calling partially filled boxes from the UI.
- **testing and known issues:** No known major issues. Tested by the creators. Several issues were fixed after Archive Curator feedback. The box calling function should be clicked only once and never when the system is active, as it can easily break if spammed or spit out loose items if the the slice is currently loading them.
- [**Original post (16/07/2024)**](https://discord.com/channels/748542142347083868/749137424684285992/1262854684037611600)
- [**Download link (latest update)**](https://www.mediafire.com/folder/vlg6rvssbth2q/YAMS)
- [**Help thread**](https://discord.com/channels/748542142347083868/1182775318830907412)

## [1.17+] Krebs' Main Storage System

by Krebs

A complete main storage system originarily made for Ingenium SMP

<img width="2048" height="2048" alt="image" src="https://github.com/user-attachments/assets/c55b1008-54c1-4ecc-aead-c7910a6916e1" />

<details>
<summary>Picture gallery - click to expand</summary>

input:
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/fb05add9-3e1a-4447-986a-4bfaf3d70b76" />

UI:
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/d9eae6e1-9163-4785-a2e5-d10e3cbb6294" />
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/1c35cd44-f6b0-4f6e-8b1a-1ab3a2c15f89" />
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/b4c621c9-4b99-4165-be89-a957c62a0b0e" />
<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/53f6ff0c-c63b-439d-a426-f9e4d2b82c78" />


</details>


- **What does it sort?** Accepts boxes and items. If a secondary input is added, is capable of sorting full boxes without unloading them. 544 chest hall items, 90 bulk items, 10 MIS categories holding up to 54 item types each.
- **Sorting speed:** up to 8x hopper speed - (72000 items/hour) unloading shulker boxes in parallel.
- **Size:** 114x101x109 - 93156 blocks
- **Extra features:** Unstackable sorting, chunkloading, crafting station, furnace array, micro farms, big control panel, possibility to chunkload with a bot for use in the End dimension, many safety features.
- **testing and known issues:** No known issues. Some components used are functional but not up to date (unstackable sorter, parallel unloader, MIS, mixed loaders used for overflow) Fully tested and reviewed by an Archive Curator. As chosen by the creator, there isn't a player-accessible input to sort full boxes without unloading them.
- [**Archive post with download**](https://discord.com/channels/748542142347083868/833152072618606652/1083907230023295066)



# Other/Advanced

This section contains storage system that are unique and don't fall in either of the previous sections, or are so advanced that you shouldn't consider building them, unless you're already an expert of the field playing in a big techincal server. 

## [1.19+] SciCraft Main Storage

by jorvp, Obi

A complete hybrid encoded storage system made for SciCraft SMP. Uses three hybrid halls, combining normal chest halls and shulker boxes restocked from a remote bulk storage.

<img width="1820" height="899" alt="area_render_1_" src="https://github.com/user-attachments/assets/5c471cec-2918-4980-a47e-e16d5b611da7" />

<details>
<summary>Picture gallery - click to expand</summary>

input:
<img width="1920" height="1020" alt="2025-10-23_19 51 02" src="https://github.com/user-attachments/assets/b184baf8-2bcc-4f51-acf9-20857a192130" />

UI:
<img width="1920" height="1020" alt="2025-10-23_19 51 10" src="https://github.com/user-attachments/assets/390c4ee8-7307-4ca0-bbea-4da272874b47" />
<img width="1920" height="1020" alt="2025-10-23_19 51 16" src="https://github.com/user-attachments/assets/1d29b033-86e0-4cce-b505-30a24f85b03c" />
<img width="1920" height="1020" alt="2025-10-23_19 51 23" src="https://github.com/user-attachments/assets/9c48c0fe-2cbe-4b99-afdf-5feb685673a3" />
<img width="1920" height="1020" alt="2025-10-23_19 51 45" src="https://github.com/user-attachments/assets/6b3db113-80da-4756-986e-12a2710203f1" />
<img width="1920" height="1020" alt="2025-10-23_19 51 56" src="https://github.com/user-attachments/assets/c232b319-590a-4ef3-bcc0-20ffe0295c51" />
<img width="1920" height="1020" alt="2025-10-23_19 52 10" src="https://github.com/user-attachments/assets/99567d62-3c99-488e-87df-59d169563f2e" />
<img width="1920" height="1020" alt="2025-10-23_19 52 24" src="https://github.com/user-attachments/assets/885f4bb0-14fa-43cd-b0a1-c5597a6580ac" />



</details>

- **What does it sort?** Stackable items, boxes, full boxes, some non-stackable items. 384 bulk items, 768 chest hall items. No multi item sorter.
- **Sorting speed:** up to 16x hopper speed (144000 items/hour) unloading shulker boxes in parallel.
- **Size:** Very big. Almost 190000 blocks (not counting remote bulk).
- **Extra features:** many safety features, player call from remote bulk, unstackable sorting, yeeting station, crafting station, restock station, mass crafter with huge loader array, status indicators, suspicious lack of a potion brewer.
- **testing and known issues:** Tested by the creators and used in SMP for over a year. No known issues.
- [**Original post, download link and youtube video**](https://discord.com/channels/748542142347083868/1189010750606426132/1189012529284919296)
