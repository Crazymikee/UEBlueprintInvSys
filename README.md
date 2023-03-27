# UEBlueprintInvSys
Multiplayer Inventory System for UE 5.1 in blueprints

Fairly extendable multiplayer inventory that is segmented out to be understandable to work with.
Requires limited modifications to the underlying item move logic when adding additional functionality to the inventory (per-project data for items ECT)

System is split into 3 sections
Core
Custom
Example

Core folder contains the base essentials to facilitate usage of the inventory (add,move,split,create,drop,delete)
Custom folder contains data structs / function lib intended to be modified per project based on needs (add vars for your items to have the functionality needed for your game)
Example folder contains examples on how to implement the inventory into your game framework (inv comp added to actors/players, ui elements to trigger function requests, ECT)
