# Info
This repo contains my [wishlist](wishlist.txt) of items in Destiny 2 (weapons and armor that I am chasing), for use with [Destiny Item Manager](https://destinyitemmanager.com) (DIM). The wishlist itself is just a regular textfile (.txt) populated with lines like `dimwishlist:item=1234&perks=456,567`, which points DIM to an item in the Destiny API with the specified perkset (notice *item* and *perks* in the `code line`). For more information on the subject, go [here for DIM's own documentation on it](https://github.com/DestinyItemManager/DIM/blob/master/docs/COMMUNITY_CURATIONS.md).

# Adding items
To add items to the wishlist you need to know the hash-id of the item in question and any perks you want on it. To find these you can go to [Destiny Tracker's Item Databse](https://destinytracker.com/destiny-2/db). This provides you with a GUI where you can pick and choose the perks you want on a given item. If that's not your thing there's also [Destiny Data Explorer](https://data.destinysets.com/) where you can search for basically anything in the game, including items and perks naturally. Then there's also [light.gg](https://light.gg) which will show you available perk-combinations and API hashes for items.

To make populating the list easier and not quite so tedious, you can use [this site](https://48klocs.github.io/wish-list-magic-wand/fingerwave.html). It will *automagically* create variations of an item with perks you put in. So if you're interested in, say, a Spare Rations but you're down to get either Rampage or Kill Clip, you just put those perks into the form and it will spit out the following lines...
```
// Spare Rations
dimwishlist:item=3116356268&perks=3250034553,1561002382,247725512,1015611457
dimwishlist:item=3116356268&perks=3250034553,1561002382,247725512,3425386926
```
...*which* corresponds to a Spare Rations Hand Cannon with Hammer-Forged Rifling in column one, High-Caliber Rounds in column two, Rapid Hit in three and Kill Clip in four for the first line and Rampage for the second line. Quick note: you need to add perks in all four slots if you are going to use the above tool (hence why I added Hammer-Forged and High-Cal. Rounds).

# Useful links
- [Destiny Tracker's Item Database](https://destinytracker.com/destiny-2/db)
- [Destiny Data Explorer](https://data.destinysets.com)
- [light.gg](https://light.gg)
- [48klocs Perk Permutation tool](https://48klocs.github.io/wish-list-magic-wand/fingerwave.html)
