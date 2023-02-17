# Reference Guide

Below you can find detailed rules for some of the parts of "Skyrim: The Adventure Game".
Note that the rules below do not include everything form the core rulebook and you will still need to reference it.

Some of the rules below are neither defined in the rulebook nor agreed up by the BoardGameGeek community.
In this case there might be multiple options for a given rule denoted by a `(Option X)` in the title of the rule.
Until we find the official ruling, take any of these and apply them to your entire game

## Bounty

1. When having a bounty on you and you enter a hold you have two options
   1. pay X amount of gold and continue your turn
   2. fight the guards. This ends your turn

## `Clear` Keyword

1. If the clear keyword specifies a set of enemies then fight them as separate groups in a [Combat Encounter](#combat-encounter)
2. If the clear keyword specifies a dungeon type then handle this as a [Explore a dungeon](#explore-a-dungeon) action (including the additional loot at the end)
3. Other characters on your space may join you on the Combat Encounter, even if this is listed on a personal quest. This counts as their action this turn and they do not get the rewards of the quests (if any)
4. Even if this specifies enemies from the dungeon deck this does not count as a [Explore a dungeon](#explore-a-dungeon) action

## Combat

1. In a combat you fight one or multiple enemies at the same time
2. Each combat is always part of an [Combat Encounter](#combat-encounter) (so even if you have a combat with a single enemy you treat it as an encounter)
3. Combat process
   1. if the enemy is not a trap: a single character that is part of the [Combat Encounter](#combat-encounter) may choose to sneak
      1. the player roles the following amount of skill test dice: 3 + 1 for each `Sneak` keyword on any of his items
      2. If the player succeeds the skill test (as specified on the enemy card) he attacks with any of their available combat actions (paying the appropriate stamina cost) without needing to roll an additional skill test
      3. failing a sneak test has no drawback
      4. you can not attack with spells when sneaking (excluding the spell muffle)
      5. you can not sneak when wearing heavy armor
      6. you can not push for the sneak test
   2. if the enemy has the `Ambush` keyword and sneaking did not succeed (or no character tried)
      1. the enemy resolves the `Skull` action targeting the following character
      2. the character choosing to sneak (if any)
      3. a Character by the players choice
   3. if the enemy is a trap: a single character that is part of the [Combat Encounter](#combat-encounter) may choose to lockpick
       1. the player roles the following amount of skill test dice: 3 + 1 for each `Lockpick` keyword on any of his items
       2. If the player succeeds the skill test (as specified on the enemy card) the trap is defeated immediately
       3. if the player fails in the skill test the `Skull` action of the trap activates and targets the lockpicking character
       4. you can not push for the lockpick test
   4. Resolve [Combat Rounds](#combat-round) until the enemies are defeated or all characters have fled

## Combat Encounter

1. Each fight against a single or multiple groups of face-up enemy cards
2. Your normal Dungeon consists of two separate groups with one enemy each
3. Encounter process
   1. Draw all enemies of the encounter in the order specified and place them face-down next to each other
   2. For each group of enemies specified in the encounter
      1. flip the enemies of the group face-up
      2. fight the enemies as described in [Combat](#combat)
      3. collect the rewards from all enemies
      4. after all enemies are defeated
         1. if it is from a dungeon deck:
             1. if the level of the enemy is lower than the enemy discard level of any of the characters in the fight: remove the enemy from the game
             2. else: place it on the discard pile of the dungeon deck
         2. if it is from the numbered deck: put it back to the numbered deck
      5. Restore your Stamina and magica Track, do not restore your health track
   3. If you flee before flipping all enemies face-up: place the remaining face-down enemies back on the respective dungeon decks (in the reverse order of drawing them)
   4. Restore your Stamina, magica and Health track

## Combat Round

1. The individual part of [Combat](#combat)
2. Combat round process:
   1. All characters taking part in the [Combat Encounter](#combat-encounter) may
      1. drink any potions provided they can pay the appropriate cost
      2. switch any equipped item paying one stamina for each item switched
   2. Decide the character that will act this Combat Round. He turns his character card sideways. You may not choose a character with a sideways character card
   3. Roll the enemy die but do not resolve the action yet
      1. if the die shows an action not present on the enemy card it is treated as a miss (no action)
      2. if the enemy rolls a legendary attack, but no character participating in the combat has a legendary skill then the attack is treated as if the enemy would have rolled a miss
   4. if you have a follower or a summon do the following for each of them in any order
      1. roll an enemy die to select the action
      2. resolve the action
   5. select the action you want to take and resolve it
       1. offensive action
           1. resolve the enemy action
           2. pay your action cost in stamina or magica
           3. roll the skill test as described by your action (you may push as defined in [Push](#push))
           4. if the roll is successful apply the damage, otherwise nothing happens
       2. defensive action
           1. pay your action cost in stamina or magica
           2. roll the skill test as described by your action (you may push as defined in [Push](#push))
           3. if your roll is successful: cancel the enemy action (if it is a group attack still resolve it for the other players though)
           4. if your roll is unsuccessful: resolve the enemy action
       3. special action
           1. pay your action cost in stamina or magica
           2. roll the skill test as described by your action (you may push as defined in [Push](#push))
           3. if your roll is successful: apply the special action
           4. resolve the enemy action
   6. if all character cards are turned sideways: turn them back

## Dungeon Deck

1. Each deck is split by the type of enemy
2. Each deck starts with three level `0` cards and then the level `1-7` cards in decreasing order (if you have more than one card with the same level shuffle them and add them all)
3. Next to each deck is the discard pile for the given deck
4. At the end of the game turn if the discard pile is not empty
   1. if no player interacting with this dungeon deck had a legendary skill
      1. add one card from respective the dungeon deck to the discard pile
      2. shuffle the discard pile
      3. place the discard pile on top of the dungeon deck
   2. if any player interacting with this dungeon deck had a legendary skill
      1. shuffle the dungeon deck and the discard pile together
5. If you need to draw from a dungeon deck, but the deck is empty. if the discard pile is not empty: reshuffle it as if it was the end of the game turn

## Enchantment

1. Can be applied to weapons, items or armor
2. Enchantment of the same type can stack (as in you can have multiple of the same type)
   1. A few enchantments do not make sense to be stacked. In this case when drawing enchantments then redraw

## `Enchant an item` keyword

1. Treat this as an enchant action on the market without the cost for the first (or first two in case of Enchanting) card drawn

## Encounter

1. An encounter is any of the following
   1. A Town Encounter
   2. A Wilderness Encounter
   3. interact with the text of any of the cards (e.g. finishing a quest)
   4. Fighting one or multiple enemies (see [Combat Encounter](#combat-encounter)) (e.g. as part of a [Explore a dungeon](#explore-a-dungeon) action)
   5. Fighting a roaming monster (see [Roaming Monster](#roaming-monster) )

## Enemy

1. A monster or a trap from a dungeon deck or from the numbered deck
2. Each enemy from a dungeon deck has a number in the top left corner. This represents its level

## Explore a dungeon

1. Can be taken as one of the actions in a game turn
2. Can only be done if you are at a dungeon location
3. If more than one character is at a given dungeon location and multiple characters choose this action you handle the encounter below as a group of all characters doing this action
4. Explore a dungeon process
   1. Look up the enemies to encounter on the `Dungeon Challenge` Reference Card for your current Story Chapter
   2. All enemies having a box around them are to be treated as being in the same encounter group
   3. Handle the Encounter as defined in [Combat Encounter](#combat-encounter)
   4. If you defeated all enemies of the encounter the character who killed the last enemy draws a Treasure as specified below
      1. if the highest level of an enemy was 3 or lower: draw a B-Chest
      2. otherwise draw an A-Chest

## Follower

1. Each character may only have one follower
2. Summoned creatures do not count as followers

## Game Turn

1. The main game loop. Consist of the following in order
   1. Drawing an Event Card
   2. Move roaming monsters if specified by the chapter rules
   3. Moving
   4. Take one of the following actions
      1. Handle a [Roaming Monster](#roaming-monster) (required if on the same space)
      2. [Explore a dungeon](#explore-a-dungeon)
      3. Explore an area (Stronghold or wilderness)
      4. Complete a Quests (multiple characters can join this if they are on the same space)
   5. If at a stronghold, optionally do the actions specified in [Stronghold](#stronghold) (this may also be done before your action)
   6. Pass the starting player token to the next player
   7. [Level Up](#level-up) your character

## Level Up

1. If you have the required experience to level up you must do so
   1. it costs initially 7 experience to level up
   2. the price increases by 1 experience for each level up
   3. the maximum level up costs 15 experience
2. Level up process
   1. remove all of your experience tokens
   2. if you have remaining empty skill slots on your character board (there are 8 in total)
      1. take a skill token of your choice from the box and place it on you character board in the lowest numbered slot
      2. ensure the skill token is on the non-legendary side
   3. if you have all skill slots filled you need to choose one skill to increase to legendary level
      1. If you get a legendary skill for the first time during level up take the 20 legendary enemy cards from the box and add them to the dungeon decks
   4. increase one of your [Tracks](#track) by one point. Therefor increase the current and maximum value of the Track

## Market

1. Markets can be accessed in strongholds if there is no [Thread Token](#thread-token) on them
2. Using a Market is free and does not cost any kind of action
3. on the market you can
   1. buy items
   2. sell items
   3. upgrade, enchant or craft items
   4. buy components
   5. buy a horse

## `Protect` keyword (Option 1)

1. Allows the owner of this item to take the damage anyone else in the current [Combat Encounter](#combat-encounter) is receiving
2. Only the armor of the owner of the item applies against the damage
3. This does not count as a Combat Turn of the owner of the item

## `Protect` keyword (Option 2)

1. Allows the owner of this item to take the damage a specific other Character in the current [Combat Encounter](#combat-encounter) will be receiving
2. The effect of the Protect Action is active until the owner of the item takes his turn again
3. Only the armor of the owner of the item applies against the damage
4. This counts as special action of the Combat Turn

## Push

1. When resolving a skill test you may reroll [Skill test dice](#skill-test-dice) by paying the appropriate cost
2. If the cost is specified on a card you can push any number of times by paying the appropriate cost each time
3. If you want to push on you skill test for an attack in a [Combat Round](#combat-round)
   1. You may push the following number of times
      1. `4` times if you have any track with a maximum of `10`
      2. `3` times if you have any track with a maximum of `8` or higher
      3. `2` times otherwise
   2. You pay depending on the action you do the skill test for
      1. if the action is payed in stamina the push costs 1 stamina each
      2. if the action is payed in magica the push costs 1 magica each

## Roaming Monster

1. A roaming monster is placed on the world map
2. if you need to place a roaming monster, but there are none left you loose the game
3. there can only be a single roaming monster on a given space
4. It only moves if an event card specifies it
5. characters ending there movement on a roaming monster must encounter it as their only action in this game turn
6. if multiple characters end their turn on the same roaming monster they handle the encounter as a group
7. if characters do not defeat a roaming monster they encounter they may move one space in any direction

## Skill test dice

1. Each die has the following chances
   1. 1/2 a circle
   2. 1/3 a triangle
   3. 1/6 a diamond
2. The dice in the box are no hard limit. If you need more add some d6 with the following rules
   1. 1-3 a circle
   2. 4-5 a triangle
   3. 6 a diamond

## Soul Trap

1. Can be applied on weapons and items using enchantments
2. Can not be applied to armor
3. Triggers only if the item it is applied to is equipped when dealing the final damage to the enemy
4. If your followers or summons deal the final damage the effect is not activated

## Stronghold

1. Strongholds are visible on the world map with their name
2. If you end your turn on a stronghold you can do the following:
   1. access the [Market](#market)
   2. pay 5 gold to remove one [Thread Token](#thread-token) from it
3. you can place [Thread Tokens](#thread-token) on strongholds causing the Unrest level to rise
4. the [Thread Tokens](#thread-token) are placed on the top right of the game board by the name of the Stronghold
5. each stronghold may have up to 3 [Thread Tokens](#thread-token) on it
6. the Unrest level of the Stronghold equals the amount of [Thread Tokens](#thread-token) placed on it
7. Depending on the Unrest level the Following happens:
   1. 1-3 Unrest: you can no longer access the market
   2. 2-3 Unrest: if you want to enter the stronghold you need to pay 5 gold to enter the stronghold
      1. you may still end your turn on the stronghold without paying 5 gold
      2. if you want to remove a [Thread Token](#thread-token) from a stronghold in this condition you need to pay 5 gold to enter it and additionally 5 gold for each [Thread Token](#thread-token) to remove
   3. 3 Unrest: each game turn, after drawing the event card add an additional [Thread Token](#thread-token) to one of the accepting cards/stronghold

## `Summon` keyword

1. Can only be used while in a [Combat Encounter](#combat-encounter)
2. draw a card of the given enemy type from the respective [Dungeon Deck](#Dungeon Deck)
3. A summoned creature is handled in combat like a follower, but does not count against the limit of one follower
4. the summoned creature is removed at the end of the [Combat Encounter](#combat-encounter)

## Thread Token

1. A black token with a face and some blades on it

## Track

1. each character board features three tracks
2. a health track in red
3. a stamina track in green
4. a magica track in blue
5. The current value of a track is specified by a matching colored cube
6. The maximum value of the track is specified by a limiting token or by the right end of the board if the token has been removed
7. You can not increase your track beyond the right end of the board. Effects that would cause that are ignored
8. health/stamina and magica can be payed, by reducing the current value by a given amount
   1. if you have insufficient stamina or magica to pay you may pay the leftovers in health

## Unrest

See [Stronghold](#stronghold)

## `Upgrade an item` keyword

1. Treat this as an upgrade action on the market without the cost for the first (or first two in case of Smiting) card drawn
