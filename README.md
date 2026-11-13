# Elemental Bendings

Elemental Bendings is a data pack with its resource pack built in. It adds a second Origins layer called Bending, so every player picks an origin and a bending style on top of it: an Enderian who waterbends, a Merling who firebends, and so on. All four styles are built only from Apoli powers. There is no Java in the pack. Every style can go further with a skill tree of paths: waterbenders can learn bloodbending, plantbending or icebending, firebenders lightningbending, combustionbending, blue fire or dragon fire, earthbenders metalbending, lavabending or sandbending, and airbenders vacuumbending, soundbending or spiritual airbending.

## Requirements

- Apoli 1.132.0 or newer and Origins 1.52.0 or newer
- Fabric 1.20.1, Fabric 1.21.1 or NeoForge 1.21.1

Put the folder (or a zip of it) in the world's `datapacks` folder and in your `resourcepacks` folder. The resource half carries the textures, models, animations and text.

## Keys

The pack registers its own keybinds under Controls > Elemental Bendings, so it never shares a key with an origin's active powers.

| Keybind          | Default |
|------------------|---------|
| Bending Stance 1 | R       |
| Bending Stance 2 | Z       |
| Bending Stance 3 | X       |

The tables below use the default letters. In the Origins screen, hover the icon next to a power's name to see its combo with the keys you have bound. Every combo is a sequence of stance keys with at most about half a second between presses. Pressing a stance key on its own takes that stance, and each style has three stances taken from the martial art it is based on:

| Style             | Martial art            | Stance 1                   | Stance 2                  | Stance 3                      |
|----------------------|----------------------------------------------|----------------------------|---------------------------------|------------------------------------|
| Waterbending      | Tai Chi                | Brush Knee and Push        | Cloud Hands               | White Crane Spreads Its Wings |
| Firebending       | Northern Shaolin       | Bow Stance Punch           | Horse Stance Double Punch | Front Heel Kick               |
| Airbending        | Baguazhang             | Dragon Palm                | Single Palm Change        | Lion Holds the Ball           |
| Earthbending      | Hung Gar               | Double Tiger Claw          | Pushing the Mountain      | Stomp                         |
| Bloodbending      | Chin Na and Eagle Claw | Eagle Claw                 | Dividing the Muscle       | Misplacing the Bone           |
| Plantbending      | Rooted Tai Chi         | Rooting the Tree           | Pulling the Vine          | Driving the Root              |
| Lightningbending  | Northern Shaolin       | Dragon Shoots Its Whiskers | Separating Yin and Yang   | The Pathway of Energy         |
| Combustionbending | Forms after Shiva      | Opening the Third Eye      | Stomp of the Destroyer    | Lord of the Dance             |
| Icebending        | Tai Chi, Hung Gar and Northern Shaolin | Freezing Cloud Hands | Glacier Horse   | Ice Spear Hand                |
| Metalbending      | Chu Gar Southern Praying Mantis and Hung Gar | Southern Mantis | Rooted Horse | Phoenix Eye Strike or Cable Launch |
| Lavabending       | Bajiquan and Hung Gar  | Bajiquan Elbow             | Spinning Shuriken Palm    | Pro-Bending Sweep             |
| Sandbending       | Earth stances with air and water footwork | Sweeping the Dunes | Coiling the Storm  | Sand Sail Push                |
| Vacuumbending     | Xingyiquan and Baguazhang | Three Body Posture | Splitting Palm   | Tiger Embrace                 |
| Soundbending      | Tai Chi and Baguazhang | Play the Pipa              | Strike the Ears with Both Fists | Fan Through the Back    |
| Spiritual airbending | Baguazhang          | Double Palm Change         | Point to Heaven, Stab the Earth | Turning the Millstone   |

Water stances flow slowly through circles, fire stances snap out fast, air stances twist and turn, and earth stances drop low and heavy. Bloodbending stances seize, twist and lock like a joint lock, and plantbending stances sink low and drive force into the ground. Lightningbending stances circle, split the energy apart and strike with two fingers. Sifu Kisu, the martial artist who designed the show's bending styles, said the circling arms and thrusting finger strike of lightningbending come from a move in Shaolin Form Number 2 called Dragon Shoots Its Whiskers, though some sources give its traditional name as Dragon Shoots Its Whispers. Combustionbending has no martial art of its own, so its stances follow Shiva, whose third eye inspired it: hands raised to the forehead, a heavy stomp and the Nataraja dance. Icebending stances begin as flowing waterbending circles and then stop dead into rooted Hung Gar and Northern Shaolin strikes, the moment the water freezes. Metalbending stances are compact and snappy: Toph's narrow Southern Praying Mantis stance with hooked hands, a deep Hung Gar horse stance with clawed palms that grip the earth inside the metal, and a straight two-finger strike. With a chain in either hand or in midair, the third stance becomes Lin Beifong's cable launch, one arm thrust forward with two fingers pointed and the other tucked against the ribs. Lavabending stances keep the legs wide and heavy while the arms stay loose: a Bajiquan elbow strike, Ghazan's circling palms that spin a lava disc, and Bolin's bouncing pro-bending footwork with a sweeping arm. Sandbending stances keep a wide earthbending base for the shifting sand and add the circular, relaxed arm sweeps of airbending and waterbending. "Hold" means keep the last key down: the move runs for as long as you hold it and stops when you let go. Bending shares one short cooldown, shown by the element emblem above the hotbar dimming, and the emblem's ring drains while a held move runs. A combo you finish while the emblem is still dim plays a dry click instead of the move, so you know to try again a moment later.

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

## Firebending paths

Firebenders earn mastery points the same way waterbenders do, one for every four creatures they defeat, and spend them in the Firebending Paths skill tree. It holds four paths and you can learn only one. A path takes over your firebending one skill at a time: each lightningbending or combustionbending skill swaps one fire move for a new one or adds a move, and each blue fire or dragon fire skill turns one of your fire moves hotter. The last skill of a path needs every other skill in it, and buying it completes the path and puts the path's emblem above the hotbar. Lightningbending and combustionbending also bring their own stances then.

The Origins screen follows along. When a skill replaces a move, the move's entry disappears and the new move takes its place in the list, with its own description and combo.

### Lightningbending

Lightning is not fire, so rain and water never douse it, and creatures standing in water or rain take half again as much from it. Like the rest of firebending it is a quarter stronger by day.

| Move                  | Keys            | Skill                 | Replaces               | What it does                                                                                                                                                                                                                                       |
|-----------------------|---------------------------------|-----------------------|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Lightning Bolt        | R, Z, R         | Lightningbending      | Fire Punch             | You circle your arms to gather lightning, then thrust it from your fingertips at whatever you aim at, up to 40 blocks away. It still finds a creature when your aim is slightly off                                                                |
| Thunderclap           | X, Z, R         | Thunderclap           | Fire Wall              | A clap that sends a fan of lightning through everything in front of you and throws it back                                                                                                                                                         |
| Chain Lightning       | Z, R, R         | Chain Lightning       | Fire Circle            | Lightning that hits a creature up to 32 blocks away and leaps from it to the next one nearby, up to four more times                                                                                                                                |
| Lightning Stream      | R, Z, X, hold R | Lightning Stream      | Fire Breath            | A crackling stream of lightning, up to 14 blocks long, for up to about seven seconds. It slows what it hits                                                                                                                                        |
| Flash Step            | X, X            | Flash Step            | Fire Jump and Fire Jet | You vanish and reappear where you look, up to twelve blocks away: on the ground you aim at, or just in front of the wall. Looking steeply down sends you straight ahead instead. You leave a crackling afterimage and run faster for three seconds |
| Lightning Strike      | X, R, X         | Lightning Strike      |                        | Calls lightning down onto the spot you look at, up to 48 blocks away                                                                                                                                                                               |
| Lightning Redirection | R, Z, R (Lightning Bolt's keys) | Lightning Redirection |      | It has no combo of its own. For four seconds after your strike lands, Lightning Bolt's combo redirects that lightning instead of firing a normal bolt: no wind-up, nearly twice the damage and a hard knockback. Lightning that strikes you hurts a quarter as much and opens the same window                          |
| Lightning Storm       | X, R, X         | Lightning Storm       | Lightning Strike       | For six and a half seconds lightning rains down around you and seeks out nearby creatures, and you can redirect it the whole time. It needs half a minute to gather again                                                                          |

Every lightningbending skill costs 2 points, except Lightning Storm at 3. Thunderclap leads to Chain Lightning, Lightning Stream to Flash Step, and Lightning Strike to Lightning Redirection and then Lightning Storm, which completes the path.

### Combustionbending

Combustionbenders gather all their chi behind a third eye tattooed on the forehead, and it leaves as a beam of fire that explodes on whatever it touches. Every attacking blast tears a crater in natural earth, leaves and logs, and the crater fills back in after thirty seconds. A blast that goes off close to you hurts you too. The tattoo appears with the first skill, Combustionbending.

The third eye is delicate. Each hit to your head strains it for another eight seconds, up to thirty. The fire emblem above the hotbar fills up to show how badly, and once the path is complete the eye on the combustionbending emblem cracks instead. While it is strained, any blast can misfire and explode in your face, more often the worse the strain. A hit to the head while you gather a blast sets it off at once.

| Move                | Keys                                | Skill               | Replaces               | What it does                                                                                                                                                   |
|---------------------|-------------------------------------|---------------------|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Combustion Blast    | R, Z, R                             | Combustionbending   | Fire Punch             | A beam from your forehead that explodes where it hits, up to 36 blocks away                                                                                    |
| Delayed Detonation  | X, Z, R                             | Delayed Detonation  | Fire Wall              | A blast that sticks to the ground or to a creature, glows for a moment and a half and then explodes much harder                                                |
| Explosive Repulsion | Z, R, R                             | Explosive Repulsion | Fire Circle            | A blast all around you that throws everything back and leaves you unhurt                                                                                       |
| Combustion Barrage  | R, Z, X                             | Combustion Barrage  | Fire Breath            | Four quick, smaller blasts, each aimed wherever you look at that moment                                                                                        |
| Blast Jump          | X, X                                | Blast Jump          | Fire Jump and Fire Jet | A controlled blast behind you throws you the way you look, or straight up when you look at the ground. Twice before you land, and the landing never hurts      |
| Cluster Detonation  | X, R, X                             | Cluster Detonation  |                        | A heavy blast that throws out five burning embers, which bounce away and go off one after another                                                              |
| Smoke Screen        | Z, Z, R                             | Smoke Screen        |                        | Blasts the ground into a cloud of smoke that blinds and slows everyone near you while you leap back and run faster                                             |
| Charged Blast       | Hold the last R of Combustion Blast | Charged Blast       |                        | Up to two seconds of charge for a blast twice as strong with a wider crater. If anything hurts you while you charge, it misfires as hard as you had charged it |

Every combustionbending skill costs 2 points, except Charged Blast at 3. Explosive Repulsion leads to Smoke Screen, Delayed Detonation to Cluster Detonation, and Combustion Barrage to Blast Jump and then Charged Blast, which completes the path.

### Blue fire and dragon fire

Blue fire is the mark of a master firebender, and dragon fire is a sub-bending learned from the dragons. Neither changes what your moves do. Each skill turns one fire move blue, or makes it shimmer through every color with dragon fire, and that move deals forty percent more damage and keeps what it sets alight burning three seconds longer. The first skill, Blue Fire or Dragon Fire, does this to Fire Punch for 2 points. The Wall, Circle, Breath, and Jump and Jet skills cost 1 point each: Wall leads to Circle, and Breath to Jump and Jet.

The last skill of each path is its Fire Tornado (X, R, X, 3 points). It needs the other four skills, and it completes the path and changes your emblem. The two tornadoes look different. Blue fire spins a tall, narrow funnel of blue and white flame with a crown of spikes and a whip of fire on one side. Dragon fire spins a wide rainbow vortex with the two dragons, Ran and Shaw, coiling up through it. A tornado forms where you look, up to ten blocks away, and stays there for ten seconds. It burns everything that comes close, and every few moments it lashes out at the nearest creature and drags it in. It needs fifteen seconds to gather again, and rain douses it like any other fire move.

## Airbending

| Move      | Keys            | What it does                                                                                                                                                                                                        |
|-----------|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Air Slice | R, Z, Z         | A blade of wind that cuts through up to 15 targets and blows open the wooden door, trapdoor or fence gate it hits                                                                                                   |
| Air Kick  | Z, R, Z         | A cone of wind that throws everything back and strips leaves from trees                                                                                                                                             |
| Air Ball  | X, R, hold Z    | Spins up a ball of swirling air that you sit on cross-legged and steer by looking where you want to go. It rolls the way it moves, climbs blocks and skims across water. Let go of Z or hop off and it breaks apart |
| Air Jump  | R, X in mid-air | Leap off the air itself, up to four times before landing. With an elytra it throws you forward                                                                                                                      |

Air moves put out fires they pass through, and the landing after an Air Jump is always cushioned.

## Airbending paths

Airbenders earn mastery points the same way, one for every four creatures they defeat, and spend them in the Airbending Paths skill tree. It holds three paths and you can learn only one. Vacuumbending and soundbending take over your airbending one skill at a time, each skill replacing one air move or adding one. Spiritual airbending keeps your moves and makes each of them stronger, then teaches new ones. The last skill of each path needs every other skill in it and brings the path's stances and emblem. The Origins screen shows each new move in place of the one it replaces.

### Vacuumbending

Vacuumbenders take air away instead of pushing it. Air Ball stays as it is.

| Move             | Keys               | Skill            | Replaces  | What it does                                                                                                                                                                                                                                                                                                                                     |
|------------------|--------------------|------------------|-----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Pressure Burst   | X, Z, R            | Vacuumbending    |           | You squeeze the air around you into your hands and let it go at once. The blast hurts everything within five blocks and throws it away from you                                                                                                                                                                                                  |
| Vacuum Vortex    | R, Z, Z            | Vacuum Vortex    | Air Slice | A pocket of low pressure opens where you look, up to 14 blocks away, and drags every creature and item within six blocks toward it for three seconds. Then it collapses and flings whatever is left into the air                                                                                                                                 |
| Pressure Wave    | Z, R, Z            | Pressure Wave    | Air Kick  | A ring of compressed air throws back everything within five blocks and snuffs out fires. For three seconds the pressure stays around you and shoves back anything that comes close                                                                                                                                                               |
| Pressure Barrier | Z, X, hold Z       | Pressure Barrier |           | Holds a square wall of pressurized air in front of you for up to ten seconds. Arrows and other projectiles lose most of their speed in it and creatures that push through are slowed. Let go to fire the wall forward                                                                                                                            |
| Vacuum Pull      | R, X               | Vacuum Pull      | Air Jump  | Tears the air out of a point up to 22 blocks ahead and lets the pressure drag you to it, like a grapple with no rope. It works in mid-air three times before you land, and sneaking lets go                                                                                                                                                      |
| Wall Run         | Sprint into a wall | Wall Run         |           | You run straight up the wall for about three seconds, and jumping kicks you off it. The landing never hurts                                                                                                                                                                                                                                      |
| Suffocation      | X, Z, hold X       | Suffocation      |           | Pulls the air out of the lungs of the creature you look at, up to 16 blocks away, for as long as you hold X, up to five seconds. A bubble of empty air closes over its head and it clutches its throat. It can't breathe, sprint, eat or drink, and it takes damage that ignores armor, more the longer you hold. A hit on you breaks your focus |

Every vacuumbending skill costs 2 points except Suffocation, which costs 3. Pressure Barrier needs Pressure Wave, Wall Run needs Vacuum Pull, and Suffocation sits under Vacuum Vortex and needs every other skill.

Suffocation is Zaheer's technique. Undead, golems and other creatures that don't breathe are immune, letting go or running out of time lets the creature breathe again, and the move needs fifteen seconds to recover.

### Soundbending

Soundbenders shape the vibrations in the air. Air Ball and Air Jump stay as they are.

| Move              | Keys         | Skill             | Replaces     | What it does                                                                                                                                                                                                                 |
|-------------------|--------------|-------------------|--------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Sonic Scream      | R, Z, Z      | Soundbending      | Air Slice    | A scream focused into a beam that hits everything in front of you up to ten blocks away and pushes it back                                                                                                                   |
| Sonic Clap        | Z, R, Z      | Sonic Clap        | Air Kick     | A thunderclap through everything in front of you that throws it far back                                                                                                                                                     |
| Sound Bubble      | R, Z, X      | Sound Bubble      |              | Throws a bubble of air with a growl trapped inside. Where it bursts, hostile creatures nearby turn on the creature it hit and that creature fights back. A player it hits is disoriented for a few seconds                   |
| Echolocation      | X, X         | Echolocation      |              | Every creature within 24 blocks glows through walls for eight seconds: hostile ones red, players white and the rest green. Anything that makes a sound in that time keeps glowing                                            |
| Dead Silence      | Z, Z, X      | Dead Silence      |              | For twelve seconds you make no sound and set off no sculk, and creatures within eight blocks lose track of whoever they were hunting unless they stand right next to them. The combo again ends it early                     |
| Calming Hum       | X, Z, hold Z | Calming Hum       |              | Hum for up to fifteen seconds. Animals within 16 blocks come to you and calm down, and wolves, iron golems, bees and other defenders nearby turn on the hostile creatures around them                                        |
| Disorienting Tone | Z, X, Z      | Disorienting Tone |              | Everything within seven blocks is disoriented for six seconds. Players see the world sway, hear sounds that aren't there and can't aim or sprint properly. Creatures stumble around and lose track of what they were hunting |
| Shattering Scream | R, Z, Z      | Shattering Scream | Sonic Scream | Reaches 16 blocks, hits half again as hard, slows what it hits and shatters glass, panes, ice, lanterns, candles, flower pots, amethyst and other fragile blocks in front of you                                             |

Every soundbending skill costs 2 points except Shattering Scream, which costs 3. Sound Bubble needs Sonic Clap, Dead Silence needs Echolocation, Disorienting Tone needs Calming Hum, and Shattering Scream sits under Disorienting Tone and needs every other skill.

Disoriented is a status effect of its own. A disoriented player's view rolls and drifts and a haze washes over the screen. Footsteps and creature calls come out as zombies shuffling, skeletons rattling or a creeper hissing, and stars circle the player's head.

### Spiritual airbending

Spiritual airbenders draw on the spirit world. The first four skills each strengthen one air move, and the rest teach new ones.

| Move              | Keys                  | Skill                | Replaces  | What it does                                                                                                                                                                                                                                                            |
|-------------------|-----------------------|----------------------|-----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Spirit Slice      | R, Z, Z               | Spiritual Airbending | Air Slice | Glows with spirit energy, flies faster and farther, cuts through up to 20 creatures and hits forty percent harder                                                                                                                                                       |
| Spirit Gust       | Z, R, Z               | Spirit Gust          | Air Kick  | Reaches 16 blocks, throws harder, strips leaves and hurts what it throws                                                                                                                                                                                                |
| Spirit Sphere     | X, R, hold Z          | Spirit Sphere        | Air Ball  | Shimmers with spirit light, rolls faster and holds together half again as long                                                                                                                                                                                          |
| Spirit Leap       | R, X in mid-air       | Spirit Leap          | Air Jump  | Six leaps before you land instead of four, and farther with an elytra                                                                                                                                                                                                   |
| Flight            | Z, Z, hold X          | Flight               |           | Fly for as long as you hold X, up to twelve seconds. Walk forward to fly where you look, jump to rise, sneak to sink and sprint to rush. Flying and landing never hurt                                                                                                  |
| Spirit Dash       | X, X                  | Spirit Dash          |           | Sends an astral copy of you up to seven blocks ahead, straight through walls and floors, and you step into it a moment later. The copy needs room to stand where it stops. When you look down at solid ground, it travels along the ground instead and steps up one block if it has to |
| Meditation        | X, Z, hold Z          | Meditation           |           | Float in the lotus position for as long as you hold Z, up to twenty seconds. You heal, your hunger eases, harmful effects leave you and you sense every creature within 32 blocks through walls. You can't move until you stand up                                      |
| Astral Projection | R, R while meditating | Astral Projection    |           | Leave your body and roam as a spirit for up to forty seconds. The spirit flies like Flight, passes through blocks (sneak to sink through floors), sees in the dark and can't be hurt, but it can't touch, break, use or attack anything. The combo again takes you back |

Spirit Gust, Spirit Sphere and Spirit Leap cost 1 point each, Spiritual Airbending, Flight, Spirit Dash and Meditation 2 each, and Astral Projection 3. Spirit Sphere needs Spirit Gust, Flight needs Spirit Leap, Spirit Dash needs Flight, and Astral Projection sits under Meditation and needs every other skill.

Flight takes its look from the Weightless mod. The flyer hovers with arms spread, leans into forward flight, banks when strafing and takes a different pose to rise or sink. A thin white streak trails behind, spirit sparks drift off while rushing, and speed lines race across the screen.

While you project, your body stays behind meditating in the lotus position. You snap back to it at once if it is hurt, or you stray more than 64 blocks away, and the projection needs thirty seconds to recover.

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

Defeating creatures as a waterbender earns mastery points, one for every four. Spend them in the Waterbending Paths skill tree, opened with Apoli's skill tree key (K by default). It holds three paths, and you can learn only one: buying the first skill of a path locks the other two. Shift-click a bought skill to refund it, starting with the ones you bought last, if you want to choose again.

Each path starts with a skill that replaces Pick Up Water with its own way of drawing, so what you hold becomes blood, sap or ice and the moves you make with held water become the path's versions. The later skills replace the rest of the moveset, and every skill needs the one above it in the tree. The last skill of each path (Psychic Bloodbending, Bramble Field and Ice Prison) also needs every other skill in that path, and buying it gives you that path's stances and emblem. Icebending works one move at a time like the firebending paths: each skill turns one water move into ice, and the last one completes the path.

The Origins screen lists each path move you buy under the water move it stands in for. While a path is active, which for bloodbending means at night or at any hour after Psychic Bloodbending, the screen hides the water moves you can't use.

### Bloodbending

Bloodbending bends the blood of living creatures, so undead, golems, blazes, slimes and other bloodless things are out of its reach. It works only at night until you learn Psychic Bloodbending, and in the daytime you have your waterbending back. The full moon doubles it along with the rest of your waterbending.

| Move                 | Keys                          | Skill                | What it does                                                                                                                                                                              |
|----------------------|-------------------------------|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Draw Blood           | Z, X, R                       | Bloodbending         | Tears blood out of every living creature within six blocks, wounding each a little, and you hold it as a ball                                                                             |
| Blood Blast          | Z while holding blood         | Bloodbending         | Hurls the blood as a heavy ball that bursts on whatever it hits                                                                                                                           |
| Clot and Thin        | X while holding blood         | Bloodbending         | Clots the blood into a dark, hard mass, and thins it again                                                                                                                                |
| Clot Spear           | R while holding clotted blood | Bloodbending         | A piercing spear that leaves its victims withering                                                                                                                                        |
| Clot Shards          | Z while holding clotted blood | Bloodbending         | A spray of hard shards                                                                                                                                                                    |
| Blood Whip           | R, hold Z while holding blood | Blood Whip           | A whip of blood. Tap R to lash out, and every creature it cuts gives you back a little health                                                                                             |
| Transfusion          | R, R while holding blood      | Transfusion          | Pours the blood into the creature you look at and heals it. Sneak to drink it and heal yourself instead                                                                                   |
| Levitation           | R, hold X while holding blood | Levitation           | Lifts every creature in front of you off the ground. They hang helpless until you let go or the blood runs out, then drop                                                                 |
| Blood Levitation     | Z, Z, hold X at night         | Blood Levitation     | Bends the blood in your own body to lift you off the ground while you hold X. Jump rises, sneak sinks and walking forward drifts you along. Your grip slips the whole time, so you start to sink as it weakens and drop when it fails. It holds longest under a full moon, and your blood needs five seconds to settle before the next lift |
| Blood Puppetry       | Z, R, hold X                  | Blood Puppetry       | Takes hold of the creature you look at and works it like a puppet that follows your aim. Tap R to make it lash out at everything around it, or Z to hurl it away. It replaces Water Glide |
| Psychic Bloodbending |                               | Psychic Bloodbending | Bloodbending works at any hour, so your waterbending is gone for good                                                                                                                     |

Bloodbending, Blood Whip, Transfusion, Levitation and Blood Levitation cost 2 points each, Blood Puppetry 3 and Psychic Bloodbending 4. Psychic Bloodbending comes after Blood Puppetry and needs every other bloodbending skill, and buying it gives you the bloodbending stances and emblem. A player you levitate or puppet deals no damage to their own and can't use items, and a puppet can't bend either.

### Plantbending

Plantbending bends the water inside living plants, at any hour. Drawing it needs plants close by: leaves, grass, flowers, crops, vines, moss or mushrooms. The plants you drain wither for thirty seconds and then grow back.

| Move         | Keys                           | Skill        | What it does                                                                                                                                                                                                                                |
|--------------|--------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Wither       | Z, X, R near plants            | Plantbending | Pulls the water out of every plant within four blocks and holds it as sap                                                                                                                                                                   |
| Leaf Storm   | Z while holding sap            | Plantbending | A storm of razor leaves                                                                                                                                                                                                                     |
| Condense     | X while holding sap            | Plantbending | Presses the sap into thick mud, and thins it again                                                                                                                                                                                          |
| Mud Shot     | R while holding mud            | Plantbending | Heaves the mud in a heavy arc. It hits far harder than water, slows and blinds                                                                                                                                                              |
| Mud Splatter | Z while holding mud            | Plantbending | A wide spray of mud that slows and blinds                                                                                                                                                                                                   |
| Vine Whip    | R, hold Z while holding sap    | Vine Whip    | A thorned vine whip. Tap R to lash out, and the lash drags what it hits toward you and slows it                                                                                                                                             |
| Vine Snare   | R, hold X while holding sap    | Vine Snare   | Vines burst from the ground in front of you and bind every creature they catch. They can't move or jump, and the thorns cut them for as long as you hold X                                                                                  |
| Snare Trap   | X, Z, R looking at open ground | Snare Trap   | Hides a coil of vines that binds the first creature to step on it for three and a half seconds. You can keep three set at once, and each lasts a minute                                                                                    |
| Spore Cloud  | Z, R, X                        | Spore Cloud  | Bursts the pollen and spores out of every flower and mushroom within ten blocks and dazes the creatures standing near them                                                                                         |
| Root Glide   | R, Z, hold X on water or lava  | Root Glide   | Kelp, roots and leaves knot into a raft under your feet and carry you across the water wherever you look while you hold X. Over lava the crimson and warped roots of the Nether carry you and keep the heat off. You take no fall damage while riding. It replaces Water Glide |
| Plant Golem  | Z, X, X, R near plants         | Plant Golem  | Pulls the plants around you into a towering golem for thirty seconds. It is huge, armored and hits hard, but it is slow. R slams the ground, and the combo again lets you out early. Your armor and whatever you hold stay hidden inside it |
| Bramble Field | X, X, Z looking at plants     | Bramble Field | Thorned brambles burst out of the grass, moss, leaves and flowers around the spot you look at, up to 16 blocks away, and spread outward ring by ring. For ten seconds they cut and badly slow every creature that walks through them, then sink back into the ground. They never hurt you, and the full moon doubles their bite. Crimson and warped nylium grow crimson and warped brambles. The plants need fifteen seconds before they rise for you again |

Plantbending, Vine Whip, Vine Snare, Snare Trap, Spore Cloud and Root Glide cost 2 points each, Plant Golem 4 and Bramble Field 3. Root Glide comes after Spore Cloud. Bramble Field comes after Snare Trap and needs every other plantbending skill, and buying it gives you the plantbending stances and emblem.

### Icebending

An icebender freezes water the instant it bends it, so everything comes out as ice that hits harder and freezes what it touches. What you draw is held as crushed ice. Water Glide and healing water stay as they are.

| Move         | Keys                               | Skill        | Replaces         | What it does                                                                                                                                                                  |
|--------------|------------------------------------|--------------|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Draw Ice     | Z, X, R                            | Icebending   | Pick Up Water    | Draws water from the same sources and freezes it into crushed ice as it reaches your hands                                                                                   |
| Ice Blast    | Z while holding crushed ice        | Ice Blast    | Water Blast      | Hurls a jagged block of ice that shatters on impact, freezing and slowing what it hits                                                                                       |
| Deep Freeze  | X while holding ice                | Deep Freeze  | Freeze and Thaw  | Crushed ice becomes solid ice, solid ice becomes packed ice, and packed ice loosens back into crushed ice. Ice Spear and Ice Shards thrown from packed ice hit half again as hard |
| Ice Whip     | R, hold Z while holding crushed ice | Ice Whip    | Water Whip       | A whip of jagged ice. Tap R to lash out, and every lash freezes and slows what it cuts                                                                                        |
| Ice Shield   | R, hold X while holding crushed ice | Ice Shield  | Water Shield     | A dome of thick ice that stops arrows and fire, makes blows land a quarter as hard and freezes whoever strikes it                                                            |
| Ice Skating  | Sprint                             | Ice Skating  |                  | Your shoes freeze whenever you sprint, so you skate across any ground as if it were ice, faster than you can run                                                             |
| Ice Prison   | Z, Z, X near water                 | Ice Prison   |                  | Encases the creature you look at, up to 16 blocks away, in ice for five seconds. It can't move. A player can punch the ice to break out sooner, and blows from outside crack it too |

Icebending costs 2 points, Ice Prison 3 and the rest 2 each. Ice Prison needs every other icebending skill, and buying it gives you the icebending stances and emblem. It uses a water source like Draw Ice does and puts the Encased effect on its target.

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

## Earthbending paths

Earthbenders earn mastery points the same way, one for every four creatures they defeat, and spend them in the Earthbending Paths skill tree. It holds three paths and you can learn only one. Metalbending and lavabending take over your earthbending one skill at a time, each skill replacing one earth move or adding one, and sandbending adds to it. The last skill of each path needs every other skill in it and brings the path's stances and emblem. The Origins screen shows each new move in place of the one it replaces.

### Metalbending

Metalbenders feel the specks of earth still trapped in refined metal. The root skill lets Earth Kick and Earth Lift rip up and hurl blocks of iron, gold, copper in every state of weathering, raw ore, netherite and ancient debris, and they hit harder than earth. The other skills turn the metal you wear and carry into weapons. Chainmail, iron, gold and netherite all count as metal armor, and the shards, plates and gauntlets take the color of the piece they come from. While a piece's metal is away from your body it gives you no armor, toughness or knockback resistance, and that piece stops showing until the metal reforms, while the rest of your armor stays visible. The helmet comes back when the shards return or the gauntlets end, the chestplate when the plates fold back, and the leggings and boots when you stop raising walls or three seconds after a pillar.

| Move            | Keys                              | Skill            | Replaces      | What it does                                                                                                                                                                         |
|-----------------|--------------------------------------|------------------|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Sword Throw     | X, R, hold R with a metal sword   | Sword Throw      |               | Throws the iron, gold or netherite sword in your main hand. It spins out to where you look, up to 12 blocks, cuts through everything on the way and follows your aim while you hold R. Let go and it flies back to your hand |
| Metal Gauntlets | X, X, R with a metal helmet       | Metal Gauntlets  |               | Reshapes your helmet into gauntlets for twelve seconds. Punches hit five points harder and throw foes back                                                                           |
| Helmet Shards   | Z, Z, R with a metal helmet       | Helmet Shards    |               | Scraps your helmet into six shards that seek out the creatures in front of you, then fly back to your head                                                                           |
| Shrapnel Shield | Z, Z, hold X with a metal chestplate | Shrapnel Shield |            | Your chestplate breaks into plates that whirl around you for up to twelve seconds. Projectiles bounce off, blows land a third as hard and the plates cut whoever comes close          |
| Metal Wall      | R, Z, X, hold Z                   | Metal Wall       | Earth Shaping | With metal leggings and boots, raises walls of metal on any solid ground. Iron raises iron, gold raises gold, netherite raises netherite and chainmail raises bars. Without them it raises earth |
| Metal Pillar    | R, X, Z                           | Metal Pillar     | Earth Pillar  | With metal leggings and boots, drives a pillar of metal out of any solid surface. Without them it raises earth                                                                      |
| Magnetic Pull   | R, R, Z                           | Magnetic Pull    |               | Pulls dropped ingots, nuggets, raw ore and metal gear within 12 blocks to you, and drags creatures wearing metal armor off their feet toward you                                    |
| Chain Lash      | X, R, X with a chain in either hand | Metal Chains   |               | Chains the creature you look at, up to 16 blocks away, to the nearest other creature. Both are slowed while the chain shrinks and drags them together, and it snaps when they collide. With no one else near, the chain binds them to you and reels them in |
| Chain Grapple   | X, R, Z with a chain in either hand | Metal Chains   |               | Shoots a steel cable into the block or creature you look at, up to 64 blocks away, and hauls you toward it. Strafe left or right to swing around the anchor, hold jump to boost and sneak to let go |

Metalbending, Sword Throw, Metal Gauntlets, Helmet Shards, Shrapnel Shield, Metal Wall, Metal Pillar and Magnetic Pull cost 2 points each, and Metal Chains costs 3.

Chain Grapple works like the cables of the Metalbending Police. The cable pulls you straight at the anchor and lifts you while you hang below it. Strafing swings you around the anchor in a circle that tightens as the cable pulls you in, and boosting builds up over about a second to make you circle faster and climb harder. When you let go you keep most of your speed for a few seconds, so you can fire the next cable in mid-flight and keep swinging. Firing at a new anchor while you hang swaps the cable over without dropping you, and firing at nothing lets go. Hanging on tires your arms, three times as fast while you boost, and when they give out the cable slips free. They recover quickly once you stand on the ground and slowly in the air. You take no fall damage while the cable holds you, but a long drop after letting go still hurts. On a server, swinging through open air for more than four seconds without dropping can trip the vanilla flying check, so turn on allow-flight in server.properties if players get kicked for flying.

### Lavabending

Lavabenders heat earth until it melts and cool it again whenever they like. The magma they make burns anyone standing on it, but never them, and their lava discs cut through stone and metal. Most of the magma is magma blocks, with lava only where it is walled in, so it can never run off. All of it settles back into the earth it came from after a while.

| Move        | Keys                          | Skill       | Replaces      | What it does                                                                                                                                       |
|-------------|----------------------------------|-------------|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| Melt        | R, Z, X, hold X               | Lavabending | Earth Tunnel  | Melts the earth you look at, up to 8 blocks away, into magma and lava while you hold it. Aim at magma or lava instead to cool it into stone        |
| Lava Ball   | X, Z, X looking at lava or magma | Lava Ball | Earth Lift    | Scoops up a ball of lava that hovers below your crosshair. R throws it and Z drops it. It bursts into flames and splashes magma where it lands      |
| Lava Disc   | Z, R, X                       | Lava Disc   | Earth Kick    | Melts a block of earth, magma or lava into a spinning disc and throws it where you look. It cuts through creatures and through stone, earth and metal |
| Lava Wave   | X, Z, Z, R                    | Lava Wave   | Earth Wave    | Three rolling rows of lava that burn through everything and leave a trail of magma                                                                 |
| Eruption    | R, X, Z                       | Eruption    | Earth Pillar  | The ground at the spot you look at, up to 16 blocks away, rumbles and erupts, hurling everyone there into the air and leaving a molten crater       |
| Molten Wall | R, Z, X, hold Z               | Molten Wall | Earth Shaping | A wall of molten rock five blocks wide and three high in front of you. It stops projectiles, burns whoever touches it and cools into stone           |
| Magma Slam  | Z, Z, Z                       | Magma Slam  |               | Slams the ground. A ring of magma races outward and everything within six blocks is burned and thrown back                                          |

Lavabending, Lava Ball, Lava Disc, Lava Wave, Eruption and Molten Wall cost 2 points each, and Magma Slam costs 3.

### Sandbending

Sandbending is earthbending with sand added to it. Concrete powder and every kind of sandstone join the earth you can bend, so you can kick, lift, raise and roll them like any earth, and raised concrete powder hardens into concrete. Sand you throw or roll at a creature bursts into a cloud that blinds it for a moment. Earth Tunnel leaves concrete powder and cut sandstone alone, since those are almost always someone's building.

| Move         | Keys                            | Skill        | What it does                                                                                                                                                            |
|--------------|---------------------------------|--------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Sand Surfing | X, X, hold Z while on sand      | Sand Surfing | Rides a wave of sand wherever you look for up to twenty seconds, up dunes and over steps, and you never take fall damage while surfing. It works on sand, red sand, sandstone and concrete powder |
| Sand Clones  | R, X, R while standing on earth | Sand Clones  | You crouch and press your palm to the ground, and up to three warriors of packed sand climb out of it around you. Hostile creatures that are after a player turn on the clones instead, and the clones fight back with their fists. Each clone lasts thirty seconds or a few hits, then crumbles, and one you strike yourself falls apart at once. Clumps of sand stick out all over them, so no two look quite finished. You can keep four. The same combo aimed at one of your clones bursts it into a cloud of sand that blinds and slows everything within four blocks |
| Quicksand    | Z, X, Z while standing on earth | Quicksand    | The ground around you turns to quicksand for eight seconds. Every creature in it other than you sinks to its waist and can barely move until the sand spits it back out six seconds later |

Sandbending, Sand Surfing and Sand Clones cost 2 points each, and Quicksand costs 3 and needs both Sand Surfing and Sand Clones.

## Changing how long moves last

Fire Breath, Fire Jet and Lightning Stream each last up to about seven seconds. To make one last longer, raise `max` in its `fuel.json` (`powers/firebender/fire_breath/fuel.json`, `powers/firebender/fire_jet/fuel.json` or `powers/firebender/lightningbending/lightning_stream/fuel.json`) and the matching `140` in the power that starts it.

## Layout

Powers live in a folder per origin, named after the power: `powers/firebender/fire_breath.json`. Anything only one power uses sits in a folder named after that power, such as `powers/firebender/fire_breath/fuel.json`. Shared powers are in `powers/bending/`. The waterbending paths live in `powers/waterbender/bloodbending/`, `plantbending/` and `icebending/`, the firebending paths in `powers/firebender/lightningbending/`, `combustionbending/`, `blue_fire/` and `dragon_fire/`, the earthbending paths in `powers/earthbender/metalbending/`, `lavabending/` and `sandbending/`, the airbending paths in `powers/airbender/vacuumbending/`, `soundbending/` and `spiritual_airbending/`, and the four skill trees and their skills in `skill_trees/`. The Encased effect that Ice Prison applies is `effects/encased.json`, and the Disoriented effect that Disorienting Tone and Sound Bubble apply is `effects/disoriented.json`. Textures, models and animations follow the same folders under `assets/elemental_bendings/`.
