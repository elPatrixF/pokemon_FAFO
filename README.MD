# Pokémon FA&FO EDITION
Two modifications, based on the [**disassembly of Pokémon Red/Blue**][pokered] and the [**disassembly of Pokémon Emerald**][pokemerald]. This is a modification of Pokemon that makes all Status screens unreachable, hides most UI elements, and hides the names of all attacks, among other things to make the game feel more like you're really a regular person training a Pokémon. FA&FO stands for Pokémon Fumble Around & Find Out! (Obviously)

The whole point of this hack is to make it more difficult to figure out what is going on at any given moment, and the only way to find out is through trial and error, or research, or from vibes alone.

# Download here

* [Pokemon RED FA&FO version](https://github.com/elPatrixF/pokemon_FAFO/releases/download/red/pokered.gbc)
* [Pokemon BLUE FA&FO version](https://github.com/elPatrixF/pokemon_FAFO/releases/download/red/pokeblue.gbc)
* [Pokemon EMERALD FA&FO version v1.1.0](https://github.com/elPatrixF/pokemon_FAFO/releases/download/emerald/pokeemerald_fafo_1.1.0.gba)
* [Pokemon EMERALD FA&FO version v1.1.0 (midcore)](https://github.com/elPatrixF/pokemon_FAFO/releases/download/emerald/pokeemerald_fafo_1.1.0_midcore.gba) (See screenshots below)
* Check the [releases page](https://github.com/elPatrixF/pokemon_FAFO/releases) for more information.

# Screenshots and videos

![Title screen](https://i.imgur.com/yVfByoG.png)
![1](https://i.imgur.com/YJOYJaU.png)
![2](https://i.imgur.com/7Q2Itg1.png)
![3](https://i.imgur.com/yqq0bBN.png)

[**Sample video of Pokemon RED here.**][preview] - [(On Twitter)](https://twitter.com/elpatrixf/status/2029281398062776719)

![Title Screen](https://i.imgur.com/9iew1f2.png)
![Party view](https://i.imgur.com/0AjM5vm.png)
![One](https://i.imgur.com/YYjWWvv.png)
![two](https://i.imgur.com/ZIMQc6S.png)
![three](https://i.imgur.com/YbyFqqj.png)

[**Sample video of Pokemon EMERALD here.**][preview2] - [(On Twitter)](https://twitter.com/elpatrixf/status/2030281559882842380)

Regular Version: (All attack names are "???")

![Regular Version](https://i.imgur.com/bMFHlr8.png)

"Midcore" Version: (Each attack has a unique, fixed, nonsensical name that can be written down)

![Midcore Version](https://i.imgur.com/v98rJhh.png)

New in 1.1.0: Single-use "POKé TEST KIT" object that lets you see your Pokemon stats.

![POKé TEST KIT](https://i.imgur.com/BxwgddL.png) ![POKé TEST KIT 2](https://i.imgur.com/0TGsNpS.png)

# Changes from Base game

Things that were changed from base game Pokemon Red:

* Attack names are all obscured. (Attack names changed to ????)
* Pokemon types are all obscured (Type names changed to ?)
* Party view hides HP and Level.
* Status screen cannot be accessed from Party menu. (Prints a message)
* Status screen cannot be accessed from Battle menu. (Prints a message)
* Status screen cannot be accessed from Bill's PC menu. (Cancels out)
* UI is hidden during battle. (Render call is skipped)
* Level up info is skipped. (Only plays a jingle and skips showing the stats)

Things that were changed from base game Pokemon Emerald:

* Battle UI is hidden, you can't tell the HP, or Level anymore. (You can still tell a pokemon is close to dying from messages and the alarm jingle.)
* PP is hidden and all attack types are shown as ????.
* Party list no longer shows any information other than Name.
* Summary option is removed from Party list and PC.
* Game strings have been modified to give less information.
* All attack names have been replaced by "?"
* All descriptions of moves, contest moves, and abilities have been replaced with a generic one.
* Using a potion to recover HP does not tell you the amount
* You no longer know what's the next pokemon an opponent will send out.
* Experience and level gain is hidden.
* Most attack and ability description have been purposefuly obscured
* Opponent does not reveal what pokemon they're about to send out

PLEASE NOTE: I haven't tested pokemon Red beyond viridian forest, I get the feeling everything should be ok but I have no idea. You're welcome to download the repository and improve the whole thing in whichever way you want, I just leave this as it is!

# Known Issues for Pokemon Emerald:

* Since this is a modification of the source code, all the offsets are different from the Original game, so *Randomizers and rom patches do not work on this rom*. If you really really want to try a randomized version of this I can maybe figure out how to make a randomizer for this myself :( but it's going to be PRETTY difficult.
* If you started playing on v1.0.0 and updated to v1.1.0 you will NOT have the free POKé TEST KITs from the start of the game :( but in case of emergency, saves from 1.0.0 are compatible with the base unmodified game, so you can copy the save data to the original rom, and check information from there, if you really REALLY must know info.
  * The only reason they might not be compatible is because the POKé TEST KIT is a new object that isn't present in the base game.
* [Please check the release page for more details about the current known issues and bugs.](https://github.com/elPatrixF/pokemon_FAFO/releases/tag/emerald)

Also I'm currently manually and very slowly testing pokemon emerald (Just playing it lol) to see if there's any bugs. Double Battles work fine. I have no idea if Contests or the Battle Frontier will work, but they SHOULD.

## See also

- [**Disassembly of Pokémon Red/Blue**][pokered]
- [**Disassembly of Pokémon Emerald**][pokemerald]

[pokered]: https://github.com/pret/pokered
[pokemerald]: https://github.com/pret/pokeemerald
[preview]: https://bsky.app/profile/did:plc:biouhdj7o3nsuth5irlickaz/post/3mgb23j43vk26
[preview2]: https://bsky.app/profile/elpatrixf.com/post/3mghy7rdb522s
