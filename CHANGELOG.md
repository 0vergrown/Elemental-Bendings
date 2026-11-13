## 2026-11-13

### Changed

- Sound Bubble, Calming Hum and Sand Clones set mobs on each other with Apoli's `aggro_at` instead of a fake punch. The lured mobs no longer take a hit from the taunt, and they hold their new target the way they would after being attacked.
- The README asks for Apoli 1.132.0. It makes Fire Breath and the other cone moves hit a creature you look at from close range, lets `aggro_at` set one mob on another, and keeps capes and elytras on the body while Flight leans and banks it.

### Fixed

- Snare Trap binds its victim for three and a half seconds. The leash that frees ensnared creatures topped out at half a second, so the vines fell away almost at once.
- Spirit Dash works while you look down. Any downward look used to put every landing spot inside the ground, so the copy stayed put and you went nowhere. The copy now travels along the ground at the same distance, or one block up a step, when the aimed spot is buried.
- The Spirit Dash copy no longer shoves you when it appears, since it can no longer collide with anyone.
- Plant Golem's fingers no longer sink into the floor, and crouching no longer tips the golem's body forward through its own robe.
- Bloodbending's hold on a victim lasts its full 14 ticks between refreshes. It was cut to 10, so a lag spike could free the victim early.
- Long Air Ball and Spirit Sphere rides keep the other moves locked until the ride ends. The shared cooldown topped out at 20 seconds, which let other combos fire partway through a ride.

## 2026-11-12

### Added

- Airbending Paths skill tree, with three paths that exclude each other:
  - Vacuumbending: Pressure Burst, Vacuum Vortex (replaces Air Slice), Pressure Wave (replaces Air Kick), Pressure Barrier, Vacuum Pull (replaces Air Jump), Wall Run and Suffocation.
  - Soundbending: Sonic Scream (replaces Air Slice), Sonic Clap (replaces Air Kick), Sound Bubble, Echolocation, Dead Silence, Calming Hum, Disorienting Tone and Shattering Scream, which replaces Sonic Scream.
  - Spiritual airbending: Spirit Slice, Spirit Gust, Spirit Sphere and Spirit Leap strengthen the four air moves, followed by Flight, Spirit Dash, Meditation and Astral Projection.
- Suffocation (X, Z, hold X, 3 points) pulls the air out of a creature's lungs the way Zaheer does. A bubble of empty air closes over its head while it clutches its throat, its air runs out, and it takes damage that ignores armor and grows the longer the hold lasts. Letting go, running out of time or taking a hit lets it breathe again.
- Pressure Barrier holds a wall that slows any projectile passing through it to a crawl, and Wall Run carries a sprinting vacuumbender up walls.
- Echolocation follows the Tainted pack's echolocation without its blindness. Creatures within 24 blocks glow through walls by kind for eight seconds, and anything that makes a sound keeps glowing.
- Shattering Scream breaks glass, panes, ice, lanterns, candles, flower pots, amethyst and other fragile blocks in front of the bender, including small ones that sit on floors and hang from ceilings.
- A Disoriented effect, applied by Disorienting Tone and Sound Bubble. It rolls the camera, hazes the screen, turns footsteps and creature calls into phantom zombies, skeletons and creepers, makes aiming clumsy, stops sprinting and circles stars over the head. Creatures that have it stumble around.
- Flight and Astral Projection take their look from the Weightless mod, with hover, lean, bank, rise and sink poses, a white trail, spirit sparks while rushing and speed lines on screen. Flight holds its height when you fly level. The astral body stays behind meditating as a clone while the spirit flies through blocks.
- Stances and emblems for the three air paths, after Xingyiquan and Baguazhang (vacuumbending), Tai Chi (soundbending) and Baguazhang circle walking (spiritual airbending).
- Blockbench models for the vacuum bubble, the vacuum vortex, the pressure wall and the sound bubble, and Aseprite textures for every air path icon, emblem, particle, model and overlay.
- Bramble Field, the last plantbending skill (X, X, Z while looking at grass or plants, 3 points, after Snare Trap). Thorned brambles rise ring by ring out of the grass, moss, leaves and flowers within three blocks of the spot you aim at, up to 16 blocks away. For ten seconds anything standing in them takes 1.5 damage every half second and gets Slowness III, then the brambles sink back into the ground. They never hit the caster, the moon multiplier applies, crimson and warped nylium grow crimson and warped brambles, and the field needs 15 seconds before it rises again.
- Each bramble spike is a minion with a 1.3 scale model (rise, sway and sink clips) and a hitbox shrunk to a quarter, so it doesn't catch the crosshair. Spikes join a scoreboard team with collisions off so they never push walkers, and they deal a new `brambles` damage type tagged `#minecraft:no_knockback`. On 1.20.1, which has no such tag, that damage is dealt without an attacker so it doesn't knock back there either.
- Blood Levitation (Z, Z, hold X at night, after Levitation). Bloodbenders lift themselves with their own blood: jump climbs, sneak sinks and walking forward drifts. The grip drains the whole time and lasts longest under a full moon, so the bender sinks as it weakens and drops when it fails. The blood needs five seconds to settle before the next lift.
- Root Glide (R, Z, hold X on water or lava, after Spore Cloud). A raft of kelp, roots and leaves carries plantbenders across water, and crimson and warped roots carry them across lava with fire immunity. Riders take no fall damage. It replaces Water Glide for plantbenders.
- Sand Clones (R, X, R while standing on earth). Up to three warriors of packed sand climb out of the ground, with four at most at a time. They have 6 health and last 30 seconds, crumble when they die, time out or are hit by their owner, and hostile mobs that are hunting a player turn on them instead. The same combo aimed at one of your clones bursts it into a cloud of sand that blinds and slows everything within four blocks. Clones wear a 3D model of sand clumps.
- Earthbending Paths skill tree, with three paths that exclude each other and replace one earth move per skill:
  - Metalbending: Earth Kick and Earth Lift also hurl metal blocks, plus Sword Throw, Helmet Shards, Shrapnel Shield, Metal Gauntlets, Metal Wall, Metal Pillar, Magnetic Pull and Metal Chains (Chain Lash and Chain Grapple).
  - Lavabending: Melt, Lava Ball, Lava Disc, Lava Wave, Eruption, Molten Wall and Magma Slam.
  - Sandbending: red sand, suspicious sand, sandstone and concrete powder join the bendable earth and thrown sand blinds, plus Sand Surfing, Sand Clones and Quicksand.
- Chain Grapple (X, R, Z with a chain in either hand). A steel cable up to 64 blocks long hooks a block or a creature and hauls the bender in. Strafing orbits the anchor, a boost builds while swinging, the bender hovers near the anchor, and speed carries on for a few seconds after letting go. The physics numbers come from the ODM gear in the dannys-aot mod.
- Icebending path for waterbenders: Draw Ice, Ice Blast, Deep Freeze (crushed ice, solid ice, packed ice), Ice Whip, Ice Shield, Ice Skating (skate whenever you sprint) and Ice Prison. Ice Prison encases a creature through a new Encased effect; blows from outside crack the ice, and a trapped player can punch their way out sooner.
- Stances and emblems for the icebending, metalbending, lavabending and sandbending paths.

### Changed

- The airbender origin and the Air Nomad entry point to the Airbending Paths tree.
- The README covers the airbending paths.
- Psychic Bloodbending needs every other bloodbending skill before it can be bought, and it now grants the bloodbending stances and emblem. Bramble Field does the same for plantbending. Until then a bender keeps the water stances and the water emblem, also at night as a bloodbender.
- Plant Golem no longer uses the capstone frame in the skill tree.
- Every summon in the pack carries one shared sound replacement power, so the air ball, combustion charges, quicksand, fire tornadoes, snare traps, eruptions, bramble spikes, sand clones and Flash Step afterimages no longer make the generic or hostile hurt and death sounds when they time out or die.
- Spore Cloud no longer replaces Water Glide. Root Glide does.
- Metalbending moves that turn armor into weapons take its protection with them. The armor, toughness and knockback resistance of the scrapped piece drop until the move ends, and only that piece is hidden while it is away.
- Lightning Redirection's badge says that it reuses Lightning Bolt's keys.
- The README asks for Apoli 1.131.0 and Origins 1.52.0.

### Fixed

- Ice Prison could never be bought. Its requirement checked for an Ice Skating power that did not exist under that name, which also hid Ice Skating from the Origins screen.
- Blood Levitation, Root Glide and Sand Clones showed no icon in the skill tree.

## 2026-11-11

### Added

- Tooltip badges in the Origins screen that show each move's combo with the player's own key bindings, and follow them when the keys are rebound.
- Twelve skill icons for the firebending paths.

### Changed

- Fire tornadoes stay where they form. The tornado appears where the bender looks, up to ten blocks away, settles onto the ground and stays for ten seconds.
- Lightningbending and combustionbending replace one fire move per skill, where the root used to take over the whole moveset. The root takes Fire Punch, and later skills take Fire Wall, Fire Circle, Fire Breath and the jumps.
- Lightning Storm and Charged Blast need every other skill in their path, and they grant the path's stances and emblem.
- Blue fire and dragon fire turn one fire move per skill hotter, and the Fire Tornado completes the path.
- The Origins screen lists each path move in place of the move it replaces, with its own description. Water moves hide while a path is active.
- Skill tree descriptions are one or two lines long so they fit on screen, and the firebending tree is regrouped into short chains.

### Removed

- Key combos from power and skill descriptions. They live in the badges now.

### Fixed

- The dragons on the dragon fire tornado swam tail first.

## 2026-11-10

### Added

- Firebending Paths skill tree with four paths that exclude each other. Firebenders earn mastery points the same way waterbenders do.
  - Lightningbending: Lightning Bolt, Thunderclap, Chain Lightning, Lightning Stream, Flash Step, Lightning Strike, Lightning Redirection and Lightning Storm. Rain and water never douse lightning, and creatures in water or rain take half again as much from it.
  - Combustionbending: Combustion Blast, Delayed Detonation, Explosive Repulsion, Combustion Barrage, Blast Jump, Cluster Detonation, Smoke Screen and Charged Blast. Blasts tear craters in natural earth, leaves and logs that fill back in later, and the third eye misfires when the bender takes a hit to the head.
  - Blue fire and dragon fire: the base fire moves with hotter flames (40% more damage and three more seconds of burning) and a Fire Tornado.
- Stances and emblems for lightningbending (Northern Shaolin) and combustionbending (forms after Shiva).
- Fire tornado models: a slim twisted blue funnel with a spiked crown and a lashing tendril, and a wide rainbow dragon fire vortex with the dragons Ran and Shaw coiling up it.
- Hand drawn icons for every skill in both skill trees, in place of vanilla item icons.

### Changed

- Beam particles draw at 0.15 block spacing.
- The README asks for Apoli 1.130.0.

### Removed

- The stand-in explosion particle and sound, since Apoli sends real explosions to clients now.

### Fixed

- Lightning missed most targets because its rays had no width and stopped at 28 blocks. Bolt, redirect, chain and strike rays are 0.4 blocks wide, the bolt reaches 40 blocks, the redirect 48, the chain 32 and the stream 14, and the stream no longer misses targets up close.
- Flash Step put its landing spot inside blocks when the ray hit the ground or a wall, so every fallback failed. It lands from the hit point now.
- Worn armor showed through the Plant Golem.

## 2026-11-07

### Added

- Waterbending Paths skill tree. Waterbenders earn a mastery point for every four creatures they defeat. Bloodbending and plantbending exclude each other, and each path's first skill replaces Pick Up Water.
  - Bloodbending, at night until Psychic Bloodbending: Draw Blood, Blood Blast, Clot and Thin, Clot Spear, Clot Shards, Blood Whip, Transfusion, Levitation, Blood Puppetry and Psychic Bloodbending. Undead and constructs have no blood to bend, and a creature you levitate or puppet cannot attack or use items.
  - Plantbending, at any hour: Wither (drained plants grow back after 30 seconds), Leaf Storm, Condense, Mud Shot, Mud Splatter, Vine Whip, Vine Snare, Snare Trap, Spore Cloud and Plant Golem.
  - Chin Na and Eagle Claw stances for bloodbending and rooted Tai Chi stances for plantbending.
- 18 ore variants from the stone, deepslate and Nether families can be bent. Tunnels leave ores in place.
- A dry click plays when a combo lands while bending is on cooldown, and earth moves say when no earth is in reach.

### Changed

- The full moon doubles waterbending. Night alone adds a quarter.
- Fire Jump (Z, X in mid-air) and Fire Jet (Z, hold X) are separate moves. The jet brakes a fall, climbs while jump is held and sinks while sneaking, and the landing after a jump is cushioned.
- Cooldowns are roughly halved, held water lasts fifteen seconds and every held move runs longer.
- Earth Pillar carries creatures standing next to it out to the tip and launches them for 4 damage. A side hit on a one block step rises from the step.
- Earth moves see through thin snow, clear thick snow lying on top of earth, and raise pillars and walls from the face you aimed at.
- Per-family block tags and a shared function cut the pack to about 1.07 MB.

### Fixed

- Pick Up Water often failed on a quick tap, because its last key had a hidden three tick hold.
- Earth moves stopped on snow layers, and ores in the way blocked them.
- Earth Pillar buried whatever it hit, because its launch ray hit the new pillar.
- Earth Pillar and Earth Shaping guessed the hit face from the camera angle and picked the wrong one on shallow ground hits.
- A Fire Jet started mid-fall kept falling, and the jet needed a second combo after a jump.

## 2026-11-06

### Added

- The first version adds a second Origins layer called Bending, with Non-Bender, Waterbender, Earthbender, Firebender and Airbender, built only from Apoli powers with no commands and no Java.
- Three keybinds, Bending Stance 1 to 3 (R, Z and X by default), so the pack never shares a key with an origin's own powers. Every move is a short sequence of stance keys, and held moves run while the last key stays down.
- Waterbending: Pick Up Water, Healing Water, Water Blast, Freeze and Thaw, Water Whip, Water Shield, Ice Spear, Ice Shards and Water Glide. Water needs a source within five blocks (water, ice, snow or rain), a water bucket lasts three pick-ups, and potion bottles are used up.
- Earthbending: Earth Kick, Earth Launch, Earth Lift, Earth Pillar, Earth Shaping, Earth Tunnel, Earth Column and Earth Wave. Moved earth returns after 30 seconds, and tunnels only cut through natural earth.
- Firebending: Fire Punch, Fire Wall, Fire Circle, Fire Breath, Fire Jump and Fire Jet. Rain, water and bubble columns douse fire.
- Airbending: Air Slice, Air Kick, Air Ball and Air Jump. Air Slice blows open wooden doors, trapdoors and fence gates.
- Fire is stronger by day and water at night.
- Element emblems above the hotbar that dim during the shared cooldown and drain their ring while a held move runs.
- Three stances per style on the stance keys, taken from Tai Chi, Northern Shaolin, Baguazhang and Hung Gar.
- Original particles, textures, models and poses for every move, with nothing taken from BendingStyles.
- Differences from BendingStyles: Earth Kick flies level and homes in (the mod shot kicked blocks into the ground), Earth Lift holds the block in front of you when you look down, Fire Wall starts ahead of the caster, and the Air Ball is a ridden minion that climbs blocks and skims across water. The mod's items, mobs and structures are not included, and moves that depended on a held item became combos or were dropped.

### Changed

- The namespace is `elemental_bendings`, renamed from `elementalbendings`, including the keybind and lang keys.
- Held water and ice are drawn with particles, like in the original mod.
- The Air Ball is smaller and only steers while it touches the ground or water. The rider sits cross-legged on top, and the ball turns toward its travel direction and rolls forward.
- Earth Lift follows your aim smoothly. At 120 degrees per second the block's mean lag behind the crosshair dropped from 37.6 to 9.5 degrees.
- Healing Water heals in pulses, and Fire Breath, Fire Jet, Water Shield and Water Glide spawn fewer particles and sounds per tick.
- Water and fire poses ease like their martial arts: water flows and fire snaps.
- The README asks for Apoli 1.127.0 and Origins 1.51.0.

### Removed

- The held water orb model and its three textures.

### Fixed

- Earth Kick and Earth Wave flew back at the caster at most angles.
- Projectile models showed at the feet of air and water benders.
- Fist and head particle streams and the emblem sat off to the left.
- The Air Ball stayed for its whole lifetime after you let go or hopped off.
