# Pokémon Red and Blue FA&FO EDITION

Based on the [**disassembly of Pokémon Red/Blue**][pokered]. This is a modification of Pokemon Red that makes all Status screens unreachable, hides most UI elements, and hides the names of all attacks.

The whole point of this hack is to make it more difficult to figure out what is going on at any given moment, and the only way to find out is through trial and error, or research, or from vibes alone.

In a way this is what being a normal pokemon trainer would feel like, without any additional help

Sorry I couldn't figure for the life of me how to make it look good, so I'll just post a zip with the entire repository modified, you figure it out.

[**Sample video here.**][preview]

![Title screen](https://i.imgur.com/yVfByoG.png) ![1](https://i.imgur.com/YJOYJaU.png) ![2](https://i.imgur.com/7Q2Itg1.png) ![3](https://i.imgur.com/yqq0bBN.png)

Things that were changed from base game:

* Attack names are all obscured. (Attack names changed to ????)
* Pokemon types are all obscure (Type names changed to ?)
* Party view hides HP and Level.
* Status screen cannot be accessed from Party menu. (Prints a message)
* Status screen cannot be accessed from Battle menu. (Prints a message)
* Status screen cannot be accessed from Bill's PC menu. (Cancels out)
* UI is hidden during battle. (Render call is skipped)
* Level up info is skipped. (Only plays a jingle and skips showing the stats)

## See also

- [**Disassembly of Pokémon Red/Blue**][pokered]

[pokered]: https://github.com/pret/pokered
[preview]: https://bsky.app/profile/did:plc:biouhdj7o3nsuth5irlickaz/post/3mgb23j43vk26
