# Metamorphosis-BN
A mod for Cataclysm: Bright Nights. It is highly recommended to play with my other mods Nine Cloud Dream and Phantasmagoria.
### Premise
They say that the Cataclysm turned everyone into a monster. But what if you were a monster before the Cataclysm? Are you finally normal now?

This simple mod adds a new path of magic you can tread. The new Abomination class has five spells that can be learned and they are as follows. Be warned however, for this system of magic uses your self as a grotesque medium, and if you use it too much it'll strain your body and soul.

• Ignorance Is Bliss: Terrify your enemies by allowing them to catch a glimpse of the real you. However, Psychopaths will be able to resist this effect. The effects may stack up to six times, so cast away!

• Stone of the Kalpa: You behold in your bosom, in the most sacred heart of hearts, a stone. This stone, is the axis of the world. And thus, it is indestructible. Albeit now it is hardly a pebble, and in time will become dust, yet never forget that it was once a mountain of epic proportions, eclipsing the stars and planets. You are enshrined in a suit of armor that gives decent protection.

• Summon Cardinal of the North: In the ye olden days, the four Heavenly Kings were defeated by the Divine Armament and in turn became the Four Cardinals. Call forth the Cardinal of the North, and tremble in awe and terror. Be aware that there is a chance the Cardinal may be hostile to you. It is a frightening game of luck.

• Dreams of a Cannibal: Once there was a man who yearned to heal his own wounds with the flesh and blood of others. Through crude trials, he succeeded. Don the mantle of the one called Hannibal and witness his gift. Melee damage above 5 inflicted upon another will now heal you.

• Shadow Realm: Herald the darkness and dampen the light with this accursed spell. It is an AOE spell that covers the area in shadow. Great for swift getaways.

You can randomly encounter various books that teach you these wicked arts while traversing the world.

### Changelog
2024.04.27. (Sat) First Release

2024.05.03. (Fri)

• Fixed the Husk of Humanity recipe being autolearned and it needing 5 corpses OR 50 paper instead of 5 corpses AND 50 paper.

• The Cardinal of the North is now capable of using the Ignorance Is Bliss spell. It is possible to resist the spell if the player is a Psychopath and vice versa, meaning Psychopath NPCs will be unaffected as well if either you or the Cardinal casts it at them. (Note to Self: Originally this feature was throwing off invalid spell_id errors. The cause was monsters.json loading earlier than spells.json due to alphabetical precedence. Changing spells.json to 0_spells.json made it work.)

2024.06.06. (Thur)

• Altered the Kalpa armor to allow the player to wear more than one, and subsequently the effects of the Kalpa can stack only up to two times now, coinciding with the number of Kalpa armor you can wear. Before it was four times, for armor you could only wear one of... Partially changed the description of the book Tales of the Abominable One.
