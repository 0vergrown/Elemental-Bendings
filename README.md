# Elemental Bendings

Elemental Bendings is a data pack with its resource pack built in. It adds a second Origins layer called Bending, so every player picks an origin and a bending style on top of it: an Enderian who waterbends, a Merling who firebends, and so on. All four styles are built only from Apoli powers. There is no Java in the pack. Waterbenders can go further: a skill tree teaches bloodbending or plantbending, which take over waterbending one move at a time.

## Requirements

- Apoli 1.127.0 or newer and Origins 1.51.0 or newer
- Fabric 1.20.1, Fabric 1.21.1 or NeoForge 1.21.1

Put the folder (or a zip of it) in the world's `datapacks` folder and in your `resourcepacks` folder. The resource half carries the textures, models, animations and text.

## Keys

The pack registers its own keybinds under Controls > Elemental Bendings, so it never shares a key with an origin's active powers.

| Keybind          | Default |
|------------------|---------|
| Bending Stance 1 | R       |
| Bending Stance 2 | Z       |
| Bending Stance 3 | X       |

The tables below use the default letters, and the power descriptions in the Origins screen always show the keys you have bound. Every combo is a sequence of stance keys with at most about half a second between presses. Pressing a stance key on its own takes that stance, and each style has three stances taken from the martial art it is based on:

| Style        | Martial art            | Stance 1            | Stance 2                  | Stance 3                      |
|--------------|------------------------|---------------------|---------------------------|-------------------------------|
| Waterbending | Tai Chi                | Brush Knee and Push | Cloud Hands               | White Crane Spreads Its Wings |
| Firebending  | Northern Shaolin       | Bow Stance Punch    | Horse Stance Double Punch | Front Heel Kick               |
| Airbending   | Baguazhang             | Dragon Palm         | Single Palm Change        | Lion Holds the Ball           |
| Earthbending | Hung Gar               | Double Tiger Claw   | Pushing the Mountain      | Stomp                         |
| Bloodbending | Chin Na and Eagle Claw | Eagle Claw          | Dividing the Muscle       | Misplacing the Bone           |
| Plantbending | Rooted Tai Chi         | Rooting the Tree    | Pulling the Vine          | Driving the Root              |

Water stances flow slowly through circles, fire stances snap out fast, air stances twist and turn, and earth stances drop low and heavy. Bloodbending stances seize, twist and lock like a joint lock, and plantbending stances sink low and drive force into the ground. "Hold" means keep the last key down: the move runs for as long as you hold it and stops when you let go. Bending shares one short cooldown, shown by the element emblem above the hotbar dimming, and the emblem's ring drains while a held move runs. A combo you finish while the emblem is still dim plays a dry click instead of the move, so you know to try again a moment later.

## Firebending

| Move        | Keys                 | What it does                                                                              |
|-------------|----------------------|-------------------------------------------------------------------------------------------|
| Fire Punch  | R, Z, R              | A short burst of flame from the fist that sets targets alight                             |
| Fire Wall   | X, Z, R              | Sweeps a line of fire along the ground for 15 blocks                                      |
| Fire Circle | Z, R, R              | A spinning ring of flame that burns and pushes back everything within 6 blocks            |
| Fire Breath | R, Z, X, hold R      | A stream of fire from your mouth, for up to about seven seconds                           |
| Fire Jump   | Z, X in mid-air      | Rockets you upward, once before you land, even out of a fall                              |
| Fire Jet    | Z, hold X in mid-air | Hovers on a jet of fire. Jump rises and sneak sinks. With an elytra it drives you forward |

Doing Z, X and keeping X held does both: the jump rockets you up and the jet takes over at the top. The jet stops a fall the moment it starts, and a landing after a Fire Jump never hurts. Rain, water and bubble columns douse every fire move. Firebending is a quarter stronger during the day.

## Airbending

| Move      | Keys            | What it does                                                                                                                                                                                                        |
|-----------|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Air Slice | R, Z, Z         | A blade of wind that cuts through up to 15 targets and blows open the wooden door, trapdoor or fence gate it hits                                                                                                   |
| Air Kick  | Z, R, Z         | A cone of wind that throws everything back and strips leaves from trees                                                                                                                                             |
| Air Ball  | X, R, hold Z    | Spins up a ball of swirling air that you sit on cross-legged and steer by looking where you want to go. It rolls the way it moves, climbs blocks and skims across water. Let go of Z or hop off and it breaks apart |
| Air Jump  | R, X in mid-air | Leap off the air itself, up to four times before landing. With an elytra it throws you forward                                                                                                                      |

Air moves put out fires they pass through, and the landing after an Air Jump is always cushioned.

## Waterbending

| Move            | Keys                                                | What it does                                                                |
|-----------------|-----------------------------------------------------|-----------------------------------------------------------------------------|
| Pick Up Water   | Z, X, R                                             | Draws water up and holds it for fifteen seconds                             |
| Healing Water   | Z, X, hold R with a potion bottle in your main hand | Heals you and whoever you point it at                                       |
| Water Blast     | Z while holding water                               | Hurls the water in a jet that knocks back and puts out fire                 |
| Freeze and Thaw | X while holding water                               | Turns the held water to ice, and back                                       |
| Water Whip      | R, hold Z while holding water                       | Coils the water around you. Tap R to lash out with it                       |
| Water Shield    | R, hold X while holding water                       | A bubble of water that stops arrows and fire. You can barely move inside it |
| Ice Spear       | R while holding ice                                 | A piercing spear that freezes and slows what it hits                        |
| Ice Shards      | Z while holding ice                                 | A spray of freezing shards                                                  |
| Water Glide     | R, Z, hold X while in water                         | Rides a wave across the surface wherever you look                           |

You can only pick up water you can reach: water, ice, snow or rain within five blocks, or standing in water. Without a source, a water bucket in your inventory lasts three pick-ups and then becomes an empty bucket, and a potion bottle is used up into a glass bottle. Waterbending is a quarter stronger at night and twice as strong under a full moon.

## Waterbending paths

Defeating creatures as a waterbender earns mastery points, one for every four. Spend them in the Waterbending Paths skill tree, opened with Apoli's skill tree key (K by default). It holds two paths and you can learn only one: buying the first skill of either path locks the other. Shift-click a bought skill to refund it, starting with the ones you bought last, if you want to choose again.

Each path starts with a skill that replaces Pick Up Water with its own way of drawing, so what you hold becomes blood or sap and the moves you make with held water become the path's versions. The later skills replace the rest of the moveset, and every skill needs the one above it in the tree.

### Bloodbending

Bloodbending bends the blood of living creatures, so undead, golems, blazes, slimes and other bloodless things are out of its reach. It works only at night until you learn Psychic Bloodbending, and in the daytime you have your waterbending back. The full moon doubles it along with the rest of your waterbending.

| Move                 | Keys                          | Skill                | What it does                                                                                                                                                                              |
|----------------------|-------------------------------|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Draw Blood           | Z, X, R                       | Bloodbending         | Tears blood out of every living creature within six blocks, wounding each a little, and you hold it as a ball                                                                             |
| Blood Blast          | Z while holding blood         | Bloodbending         | Hurls the blood as a heavy ball that bursts on whatever it hits                                                                                                                           |
| Clot and Thin        | X while holding blood         | Bloodbending         | Clots the blood into a dark, hard mass, and thins it again                                                                                                                                |
| Clot Spear           | R while holding clotted blood | Bloodbending         | A piercing spear that leaves its victims withering                                                                                                                                        |
| Clot Shards          | Z while holding clotted blood | Bloodbending         | A spray of hard shards                                                                                                                                                                    |
| Blood Whip           | R, hold Z while holding blood | Blood Whip           | A whip of blood. Tap R to lash out, and every creature it cuts gives you back a little health                                                                                             |
| Transfusion          | R, R while holding blood      | Transfusion          | Pours the blood into the creature you look at and heals it. Sneak to drink it and heal yourself instead                                                                                   |
| Levitation           | R, hold X while holding blood | Levitation           | Lifts every creature in front of you off the ground. They hang helpless until you let go or the blood runs out, then drop                                                                 |
| Blood Puppetry       | Z, R, hold X                  | Blood Puppetry       | Takes hold of the creature you look at and works it like a puppet that follows your aim. Tap R to make it lash out at everything around it, or Z to hurl it away. It replaces Water Glide |
| Psychic Bloodbending |                               | Psychic Bloodbending | Bloodbending works at any hour, so your waterbending is gone for good                                                                                                                     |

Bloodbending, Blood Whip, Transfusion and Levitation cost 2 points each, Blood Puppetry 3 and Psychic Bloodbending 4. A player you levitate or puppet deals no damage of their own and can't use items, and a puppet can't bend either.

### Plantbending

Plantbending bends the water inside living plants, at any hour. Drawing it needs plants close by: leaves, grass, flowers, crops, vines, moss or mushrooms. The plants you drain wither for thirty seconds and then grow back.

| Move         | Keys                           | Skill        | What it does                                                                                                                                                                        |
|--------------|--------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Wither       | Z, X, R near plants            | Plantbending | Pulls the water out of every plant within four blocks and holds it as sap                                                                                                           |
| Leaf Storm   | Z while holding sap            | Plantbending | A storm of razor leaves                                                                                                                                                             |
| Condense     | X while holding sap            | Plantbending | Presses the sap into thick mud, and thins it again                                                                                                                                  |
| Mud Shot     | R while holding mud            | Plantbending | Heaves the mud in a heavy arc. It hits far harder than water, slows and blinds                                                                                                      |
| Mud Splatter | Z while holding mud            | Plantbending | A wide spray of mud that slows and blinds                                                                                                                                           |
| Vine Whip    | R, hold Z while holding sap    | Vine Whip    | A thorned vine whip. Tap R to lash out, and the lash drags what it hits toward you and slows it                                                                                     |
| Vine Snare   | R, hold X while holding sap    | Vine Snare   | Vines burst from the ground in front of you and bind every creature they catch. They can't move or jump, and the thorns cut them for as long as you hold X                          |
| Snare Trap   | X, Z, R looking at open ground | Snare Trap   | Hides a coil of vines that binds the first creature to step on it. You can keep three set at once, and each lasts a minute                                                          |
| Spore Cloud  | Z, R, X                        | Spore Cloud  | Bursts the pollen and spores out of every flower and mushroom within ten blocks and dazes the creatures standing near them. It replaces Water Glide                                 |
| Plant Golem  | Z, X, X, R near plants         | Plant Golem  | Pulls the plants around you into a towering golem for thirty seconds. It is huge, armored and hits hard, but it is slow. R slams the ground, and the combo again lets you out early |

Plantbending, Vine Whip, Vine Snare, Snare Trap and Spore Cloud cost 2 points each, and Plant Golem costs 4.

## Earthbending

| Move          | Keys                                 | What it does                                                                                                                                                                                                                                                                                                                                                  |
|---------------|--------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Earth Kick    | Z, R, X                              | Rips out the block you look at and kicks it level at whoever is in front of you                                                                                                                                                                                                                                                                               |
| Earth Launch  | Z, R, X while sneaking               | Launches you off the ground                                                                                                                                                                                                                                                                                                                                   |
| Earth Lift    | X, Z, X                              | Lifts the block you look at and holds it just below your crosshair, where it follows your aim. R throws it where you look, Z drops it                                                                                                                                                                                                                         |
| Earth Pillar  | R, X, Z                              | Thrusts a pillar out of the earth you look at, up to 12 blocks away. From the ground or a one block step it rises three blocks, from a wall it shoots two blocks out of the side you can see, and from a ceiling it hangs down. Anything in its way takes a hit and is carried to the pillar's tip and thrown off the end. Aim at your own feet to ride it up |
| Earth Shaping | R, Z, X, hold Z                      | Raises a wall of earth three blocks high wherever you look at the ground, two to seven blocks away. Sweep across the ground to build a wall                                                                                                                                                                                                                   |
| Earth Tunnel  | R, Z, X, hold X                      | Tunnels through natural earth as long as you hold it. Ores stay where they are                                                                                                                                                                                                                                                                                |
| Earth Column  | Z, X, hold X while standing on earth | A column rises under your feet and carries you up                                                                                                                                                                                                                                                                                                             |
| Earth Wave    | X, Z, Z, R                           | Three rows of earth roll forward along the ground and crash through everything                                                                                                                                                                                                                                                                                |

Earthbenders bend natural earth and stone: dirt, sand, gravel, clay, mud, stone, deepslate, terracotta, the stones of the Nether and the End, and the ores inside them. Snow lying on top of earth doesn't get in the way, and grass, flowers and snow make room for raised earth. When no earth is in reach, the action bar says so. Blocks you tear out and earth you raise settle back into place after thirty seconds, so bending never leaves permanent holes or free blocks. Tunnels are the exception: they stay open, but only natural earth gives way and nothing drops. Kicks, waves and columns need solid footing.

## Changing how long moves last

Fire Breath and Fire Jet each last up to about seven seconds. To make one last longer, raise `max` in its `fuel.json` (`powers/firebender/fire_breath/fuel.json` or `powers/firebender/fire_jet/fuel.json`) and the matching `140` in the power that starts it.

## Layout

Powers live in a folder per origin, named after the power: `powers/firebender/fire_breath.json`. Anything only one power uses sits in a folder named after that power, such as `powers/firebender/fire_breath/fuel.json`. Shared powers are in `powers/bending/`. The waterbending paths live in `powers/waterbender/bloodbending/` and `powers/waterbender/plantbending/`, and the skill tree and its skills in `skill_trees/`. Textures, models and animations follow the same folders under `assets/elemental_bendings/`.
