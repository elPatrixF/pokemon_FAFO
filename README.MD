# Pokémon FA&FO EDITION
Two modifications, based on the [**disassembly of Pokémon Red/Blue**][pokered] and the [**disassembly of Pokémon Emerald**][pokemerald]. This is a modification of Pokemon that makes all Status screens unreachable, hides most UI elements, and hides the names of all attacks.
FA&FO stands for Pokémon Fumble Around & Find Out! (Obviously)

The whole point of this hack is to make it more difficult to figure out what is going on at any given moment, and the only way to find out is through trial and error, or research, or from vibes alone.

In a way this is what being a normal pokemon trainer would feel like, without any additional help

[**Sample video of Pokemon RED here.**][preview]
[**Sample video of Pokemon EMERALD here.**][preview2]

Pokemon Red FA&FO
![Title screen](https://i.imgur.com/yVfByoG.png) ![1](https://i.imgur.com/YJOYJaU.png) ![2](https://i.imgur.com/7Q2Itg1.png) ![3](https://i.imgur.com/yqq0bBN.png)
Pokemon Emerald FA&FO
![Title Screen](https://i.imgur.com/9iew1f2.png)![Party view](https://i.imgur.com/0AjM5vm.png)![One](https://i.imgur.com/YYjWWvv.png)![two](https://i.imgur.com/ZIMQc6S.png)

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

Also I'm currently manually and very slowly testing pokemon emerald (Just playing it lol) to see if there's any bugs. I have no idea if the Battle Frontier will work, or if Double Battles are fine, but they SHOULD be.

## See also

- [**Disassembly of Pokémon Red/Blue**][pokered]
- [**Disassembly of Pokémon Emerald**][pokemerald]

[pokered]: https://github.com/pret/pokered
[pokemerald]: https://github.com/pret/pokeemerald
[preview]: https://bsky.app/profile/did:plc:biouhdj7o3nsuth5irlickaz/post/3mgb23j43vk26
[preview2]: https://bsky.app/profile/did:plc:biouhdj7o3nsuth5irlickaz/post/3mgb23j43vk26
