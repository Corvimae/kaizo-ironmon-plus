## Ironmon+ Touring Ruleset v1.0.0

**Last updated: June 12, 2022**

## 1. RULESET
#### 1.01 - Base Ruleset
All rules from the [Kaizo Ironmon+ ruleset](/rules.md) apply unless otherwise specified in this document.

* (a) If a rule in the Touring ruleset contradicts the Kaizo ruleset, the Touring ruleset overrules.

## 2. LIMITATIONS
#### 2.01 - Centers
After you get your first badge, each Pokémon center may only be used to heal once. 

* (a) Once a center is used, you may still access the PC to box and unbox your HM friend.
* (b) You may not PC heal your main.
* (c) If there is a healer at the entrance to the Elite Four, you may use it once.

#### 2.02 - Potion Allotment
The first time you enter a town with a Pokémart, you may immediately run to the mart and purchaes 5 Potions.

* (a) If you forget to do this, you may purchase them before you leave; the purpose of going to the mart
immediately is to help prevent double-purchasing.

#### 2.03 - Stalling
You may only throw five balls per trainer battle to stall.

* (a) This restriction does not apply to the secondary Pokémon in a double battle.

#### 2.04 - Combat Stage Setup
In the Elite Four, you may not use non-damaging setup moves or battle items to raise any single combat stage above 3.

* (a) Moves such as Charge Beam, which deal damage but also increase a stat, are not restricted.
* (b) If a combat stage is at or below 3 and a set-up move would increase it above 3, you may not use that move.
* (c) Rule 2.04(b) only applies when you select a move; if an opponent's move such as Swagger increases your stat before your set-up move goes off, its use does not violate this rule. 

## 3. PERMISSIONS
#### 3.01 - Field Healing
HP and status conditions can be healed outside of battle unless you are inside a Gym or the Elite Four.

* (a) This rule overrides Kaizo rule 3.07.
* (b) You still may not heal PP outside of battle.

---

## Design Notes

This ruleset is intended to be the Ironmon+ variant of [Survival Ironmon](https://gist.github.com/valiant-code/adb18d248fa0fae7da6b639e2ee8f9c1#survival-ironmon-ruleset), and is an attempt to modify that ruleset with the following goals:

1. Replace the FireRed/LeafGreen-centric values provided in that ruleset with generic, per-town interactions so that the ruleset scales for every game.
1. Simplify the Elite Four set-up move rules to make them more consistent.
1. Remove some of the more esoteric aspects of the ruleset.

The Ironmon+ ruleset was born out of my frustration with Ironmon's Gen 3 focus, and the release of Survival just further emphasized that Ironmon is designed for FRLG with little consideration for other games in the series. As I've made changes to most of the rules of Survival, I'll list each of them followed by my rational for changing them.

Note that these rules are currently untested, and thus I have honestly no idea if they're easier or harder than Kaizo. I feel like they're probably harder?

Lastly, please don't be mad at me. :<

#### 10 Heal Limit
> You may only recover at a PokeCenter (or equivalent NPC) 10 times throughout the main run. Once you earn your 8th badge you earn a bonus 11th heal. If you complete the Elite 4 in a Johto game you earn an additional 7 heals for Kanto.

The heal limit is the core concept of Survival, and thus balance of exactly how many heals the runner is permitted is core to determining how challenging the run actually is. Most Pokémon games are longer than FRLG, and thus will require more heals to create a similar level of difficulty. Changing this to once-per-town is arbitrary, but so is 10, and at least this scales. 

I also inherently dislike rules that require external resource tracking on the part of the runner. It opens more room for mistakes, and I'd hate to see runs get invalidated because a runner miscounted and accidentally used 11 heals. Once-per-town still requires some management, but should be easier to keep track of, especially early on.

Lastly, the current ruleset discourages switching from your starter, as you risk using up valuable resources while scouting for a new main. Allowinging infinte center heals before the first badge allows early-game pivoting, and since the heal limit is now per-town, no rebalancing is required to account for this.

#### Start off shopping
> You can buy up to 20 Potions BEFORE the first Non-Rival trainer fight, once you have started the first fight, the normal IronMON shopping rules apply.

This is another rule that doesn't scale with longer games. I also feel that this rule in conjunction with the 10 heal limit creates "zombie runs", where a run is _technically_ alive as you haven't died yet, but you've used up so much of your resources that you're better off resetting.

By providing a steady drip-feed of resources, the scaling issue is somewhat alleviated while also providing the opportunity to "revive" a zombie run by managing to reach another Pokémart.

#### Important Trainer's Pokemon get Held Items
> The Randomizer option to add held items to Boss Trainers and Important Trainers must be enabled and set to Sensible Items.

This challenge is frustrating enough without losing to a Quick Claw.

#### PP Up Limit
> You may only use 1 PP Up on each move. PP Max's may not be used at all, but you may "trade-in" each PP max by selling it and buying a Hyper Potion or three Full Heals once they are available in the store.

PP Ups are extremely valuable, no doubt, but this change feels like it's intended to account for the fact that Survival allows PP healing outside of battle. Allowing full PP Up usage but banning field PP healing still requires PP management while not making PP Maxes feel like a disappointment.

Also, with the limited number of heals, PP management is going to be a **bad time** anyways.

#### Full Set Bonus
> If you collect all 5 Flutes (Red/Blue/Yellow/Black/White) You will be allowed to purchase two Hyper Potion or five Full Heals.

hmmm.

#### Favorite Limits
Ironmon+ does not have the favorites clause, so this is not relevant.

#### Don't Throw Too Much
> You can only throw five balls per trainer battle to stall.

I don't really know why this rule was added, but sure? My changes account for doubles battles at least, as Tate & Liza do _not_ need to be made more difficult.

#### Banned Abilities
> If your pokemon has BST of 400 or more, the following abilities are banned: Huge Power/Pure Power, Battle Armor/Shell Armor, Parental Bond, Protean, Fur Coat, Magic Guard

I don't think most people believe Battle Armor and Shell Armor to be overpowered. Protean, Fur Coat, and Magic Guard are all strong, but not game-breaking in my experience doing Gen 6 attempts.

#### Gym Leader TMs
The Kaizo Ironmon+ ruleset already implements this change.

#### Cut a move, Hold any Item
> You are allowed to hold any previously banned held item (except for Lucky Egg and Everstone) if you teach Cut to your pokemon. You may use Cut in Combat. You may still use the consumable items allowed in the Kaizo ruleset without making this trade.

Trading a move for a held item is a neat idea, but the implementation feels arbitrary. Regardless, Kaizo Ironmon+ allowed held items, as Gen 5+ games _really_ need the help to get going.

#### Damaging Healing Moves Allowed
> Moves that damage the enemy to heal yourself are now allowed to be used in trainer battles only. Leech Seed/Giga Drain/Drain Punch etc. Moves like Softboiled/Morning Sun/Wish are still banned.

This is the most FRLG-centric rule. Oblivion Wing is the absolute best move in Gen 6 if this is allowed.

#### Elite 4 and Final Gauntlet Specific Rules
The way this is implemented in the Survival ruleset is clunky. Tail Glow and Swords Dance are extremely strong for sure, and I understand the need to prevent +6 sweeps. However, the Survival implementation is overly complicated while also creating weird false equivelencies; one X Attack is not equivelent to one Swords Dance, nor is one Bulk Up the same as one Tail Glow. By enforcing a limit on the stages themselves rather than the method through which the stages are achieved, worse set-up moves are still viable while placing a check on the power of Swords Dance and Tail Glow.
