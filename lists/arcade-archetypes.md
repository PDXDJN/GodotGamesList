# Arcade Game Archetypes

A practical taxonomy for finding Godot repositories by old-school arcade design pattern. Most games are hybrids, so repositories may fit more than one section.

Last reviewed: 2026-06-17.

## Top-Level Taxonomy

| Family | Archetypes in this list |
|---|---|
| Shooters | Fixed-screen shooters, scrolling shooters, run-and-gun, light-gun, rail shooters, vehicle/cockpit action |
| Movement and space control | Maze chase, platformers, brawlers, fighting games, racing, sports |
| Pattern and pressure games | Puzzle arcade, action puzzle, survival/endurance, score attack |
| Performance and physical arcade | Rhythm/music, pinball, redemption/ticket |
| Hybrids | Arcade adventure and action-adventure |

## 1. Fixed-Screen Shooters

Enemies attack from above or across a single screen while the player moves in a limited zone.

Classic examples: Space Invaders, Galaga, Galaxian.

Core loop: dodge, shoot, survive waves.

Design DNA: enemy formations, attack patterns, power-ups, score chasing.

| Repository | Inspired by | Notes |
|---|---|---|
| [drxwat/godot-invaders](https://github.com/drxwat/godot-invaders) | Space Invaders | Direct Space Invaders clone made in Godot 4. |
| [Hernandez712/SpaceInvaders-Godot](https://github.com/Hernandez712/SpaceInvaders-Godot) | Space Invaders | Godot 4.4 clone with retro gameplay and wave-based attacks. |
| [johnpitchers/arcade-tribute](https://github.com/johnpitchers/arcade-tribute) | Galaga / Space Invaders | 3D tribute built with Godot 3.5.1. |
| [JKaizenn/NebulaFighters](https://github.com/JKaizenn/NebulaFighters) | Galaga | Galaga-style project with score management and enemy movement patterns. |
| [maxogod/Save-The-Galaxy](https://github.com/maxogod/Save-The-Galaxy) | Galaga / Space Invaders | 8-bit arcade shoot-'em-up made in Godot. |
| [Janosoft/Galaga](https://github.com/Janosoft/Galaga) | Galaga | Godot 4.x Galaga project with MIT license. |

## 2. Scrolling Shooters / Shmups

The screen scrolls automatically or steadily, forcing movement through enemy waves and bullet patterns.

Classic examples: R-Type, Gradius, 1942, Raiden.

Core loop: memorize patterns, dodge projectiles, upgrade weapons.

Subtypes: horizontal shooter, vertical shooter, bullet hell.

| Repository | Inspired by | Notes |
|---|---|---|
| [robotzero/l-well](https://github.com/robotzero/l-well) | R-Type-like horizontal shooter | Godot project with player/enemy bullets, starfield layers, enemies, and level scene. |
| [JSolde/Godot-demo-2D-Side-Scrolling-and-Wraparound-Shooter](https://github.com/JSolde/Godot-demo-2D-Side-Scrolling-and-Wraparound-Shooter) | Defender-like side-scroller | MIT-licensed Godot demo with wraparound world examples for Godot 4.2 and 4.3. |
| [Toxe/godot-defender-clone](https://github.com/Toxe/godot-defender-clone) | Defender | MIT-licensed WIP clone of the 1980s arcade game Defender. |
| [crystal-bit/space-shooter](https://github.com/crystal-bit/space-shooter) | Shoot-'em-up | GPL-3.0 Godot 3 shoot-'em-up created for Hacktoberfest 2019. |
| [jardel-codes/SMHUP](https://github.com/jardel-codes/SMHUP) | Sideways shoot-'em-up | Small Godot shoot-'em-up explicitly described as sideways. |
| [liamchristerry/shmup](https://github.com/liamchristerry/shmup) | Shmup | Simple 2D Godot shoot-'em-up with health, powerups, and progressive enemy waves. |

## 3. Maze Chase Games

The player navigates a maze while avoiding or manipulating enemies.

Classic examples: Pac-Man, Ms. Pac-Man, Lady Bug.

Core loop: collect items, evade enemies, use temporary power states.

Design DNA: enemy AI personalities, route optimization, risk/reward pickups.

| Repository | Inspired by | Notes |
|---|---|---|
| [clarkjohn/wizard-chase](https://github.com/clarkjohn/wizard-chase) | Pac-Man / Lock 'n' Chase | Godot 3.3.1 maze-chase game with documented enemy AI. |
| [DOAmaster/PacmanGodot](https://github.com/DOAmaster/PacmanGodot) | Pac-Man | Classic Pac-Man-like gameplay in Godot. |
| [Gianpyy/yet-another-pacman-clone](https://github.com/Gianpyy/yet-another-pacman-clone) | Pac-Man | Pixel-perfect arcade-style clone targeting Godot 4.4 or higher. |
| [Flyboy1010/GodotPacman](https://github.com/Flyboy1010/GodotPacman) | Pac-Man | Pac-Man implementation in Godot using C#. |
| [ClaytonWheeler0205/20GamesMsPacMan](https://github.com/ClaytonWheeler0205/20GamesMsPacMan) | Ms. Pac-Man | 20 Games Challenge entry focused on ghost AI and state machines. |

## 4. Platformers

The player jumps, climbs, avoids hazards, and usually reaches an endpoint or clears a compact stage.

Classic examples: Donkey Kong, Bubble Bobble, Ghosts 'n Goblins.

Core loop: movement precision, timing, enemy avoidance.

Subtypes: single-screen platformer, scrolling platformer, action platformer.

| Repository | Inspired by | Notes |
|---|---|---|
| [brandanstradling/Godot-BubbleBobble-Clone](https://github.com/brandanstradling/Godot-BubbleBobble-Clone) | Bubble Bobble | Godot Bubble Bobble clone with assets, scenes, and `project.godot`. |
| [jeetrayotu/godot-bubble-bobble](https://github.com/jeetrayotu/godot-bubble-bobble) | Bubble Bobble | Godot Bubble Bobble study project with assets, scenes, scripts, and export presets. |
| [JHDev2006/Super-Mario-World-Remastered-Public](https://github.com/JHDev2006/Super-Mario-World-Remastered-Public) | Super Mario World | Public remake/remaster project with added features. |
| [charpurrr/SuperMarioSolarEngine](https://github.com/charpurrr/SuperMarioSolarEngine) | Super Mario | Mario-style 2D engine/project in Godot. |
| [marmitoTH/Godot-Sonic-Physics](https://github.com/marmitoTH/Godot-Sonic-Physics) | Classic Sonic | Archived but widely referenced classic Sonic physics recreation. |
| [Moonlight-Team/MoonCast](https://github.com/Moonlight-Team/MoonCast) | Sonic | Godot 4 2D/3D Sonic physics engine. |

## 5. Beat 'Em Ups / Brawlers

The player fights groups of enemies, often moving across staged arenas or side-scrolling streets.

Classic examples: Double Dragon, Final Fight, Teenage Mutant Ninja Turtles, Streets of Rage.

Core loop: punch, kick, crowd-control, pick up weapons.

Design DNA: co-op, enemy waves, bosses, simple combos.

| Repository | Inspired by | Notes |
|---|---|---|
| [quiver-dev/template-beat-em-up](https://github.com/quiver-dev/template-beat-em-up) | Streets of Rage-style beat-'em-up | MIT-licensed Godot 4 template with configurable characters, attacks, enemy AI, stages, debug tools, and free assets. |
| [Anatolij-Grigorjev/StreetsOfDynasty](https://github.com/Anatolij-Grigorjev/StreetsOfDynasty) | Streets of Rage | Beat-'em-up tribute/reference project. |
| [yockgen/godot-tut01](https://github.com/yockgen/godot-tut01) | Beat-'em-up tutorial/template | Godot 4.3+ beat-'em-up tutorial project covering animation, collisions, entity architecture, AI behaviors, and data-driven stages. |
| [kfj001/g-orctober](https://github.com/kfj001/g-orctober) | Altered Beast / Golden Axe-style brawler | Sample Godot project asset with parallax scrolling, touch controls, gamepad support, chiptune SFX, and side-scrolling brawler action. |
| [opi225/Godot-Beat-Em-Up](https://github.com/opi225/Godot-Beat-Em-Up) | Beat-'em-up | Godot beat-'em-up project with scenes, sprites, world scene, and `project.godot`. |
| [NightParker725/Devil-s-Beatdown](https://github.com/NightParker725/Devil-s-Beatdown) | Beat-'em-up | Godot beat-'em-up game project. |
| [adam-j-s/dungeonsmash](https://github.com/adam-j-s/dungeonsmash) | Brawler | Godot brawler game with assets, scenes, scripts, and `project.godot`. |
| [ShirleyNekoDev/GameJam-PortalBrawler](https://github.com/ShirleyNekoDev/GameJam-PortalBrawler) | Minimal brawler | Small Godot brawler/game-jam project with project source, levels, materials, and sync code. |
| [Anatolij-Grigorjev/Godot32dBeatemUpTest](https://github.com/Anatolij-Grigorjev/Godot32dBeatemUpTest) | Beat-'em-up architecture test | MIT-licensed Godot project testing code architectures for a 2D beat-'em-up style game; project source lives under `game`. |
| [TaHaiLam2k6/UntitledGame](https://github.com/TaHaiLam2k6/UntitledGame) | Mobile beat-'em-up | Godot beat-'em-up mobile game project. |

## 6. Fighting Games

One-on-one combat with distinct characters, move sets, spacing, and competitive depth.

Classic examples: Street Fighter II, Mortal Kombat, Tekken, Virtua Fighter.

Core loop: spacing, blocking, combos, reading the opponent.

Design DNA: special moves, character matchups, competitive mastery.

| Repository | Inspired by | Notes |
|---|---|---|
| [hadougamer/godot-street-fighter](https://github.com/hadougamer/godot-street-fighter) | Street Fighter II | Educational SFII-style Godot project with scenes, scripts, sprites, music, and SFX. |
| [devkonrad/godot-street-fighter](https://github.com/devkonrad/godot-street-fighter) | Street Fighter | GDScript Street Fighter version for educational purposes. |
| [FoxFX87/Godot-FightingGameTemplate](https://github.com/FoxFX87/Godot-FightingGameTemplate) | Fighting game framework | Godot fighting-game template with fighters, hitboxes/hurtboxes, stage, UI, and resources. |

## 7. Run-and-Gun Shooters

The player moves through levels on foot while shooting enemies, often with platforming.

Classic examples: Contra, Metal Slug, Gunstar Heroes.

Core loop: move, shoot, dodge, collect weapons.

Design DNA: chaotic action, bosses, weapon variety, co-op.

| Repository | Inspired by | Notes |
|---|---|---|
| [galexbh/contra](https://github.com/galexbh/contra) | Contra | MIT-licensed Godot 3 project based on the first level of Contra. |
| [imperativelyfunctional/godot_contra](https://github.com/imperativelyfunctional/godot_contra) | Contra | Compact GDScript project with player, bullet, HUD, and map folders. |
| [AaronW-BE/godot-contra](https://github.com/AaronW-BE/godot-contra) | Contra | Apache-2.0 Godot project with player, enemy, bullet, level, and animation scenes/scripts. |
| [VictorRandall/metalslug_clone](https://github.com/VictorRandall/metalslug_clone) | Metal Slug | MIT-licensed Metal Slug clone on Godot. |
| [juan-burtet/RiderFromOuterSpace](https://github.com/juan-burtet/RiderFromOuterSpace) | Run-and-gun | GPL-3.0 run-and-gun game made with Godot Engine. |

More: [Side-scrolling shooters](side-scrolling-shooters.md).

## 8. Racing Games

The player competes against time, AI drivers, or other players.

Classic examples: Out Run, Pole Position, Daytona USA, Sega Rally.

Core loop: steer, accelerate, brake, optimize routes.

Design DNA: checkpoints, time extensions, drifting, cabinet controls.

| Repository | Inspired by | Notes |
|---|---|---|
| [pranav-dp/rashroad](https://github.com/pranav-dp/rashroad) | Road Rash-like combat racing | Pseudo-3D Godot racing game with combat mechanics and AI. |
| [avi-0/godot-racing-game](https://github.com/avi-0/godot-racing-game) | Trackmania-like racing | Godot/C# racing project with tracks, blocks, materials, scenes, and scripts. |
| [jrecuero/racing_game](https://github.com/jrecuero/racing_game) | Racing game example | Older Godot racing-game example with scenes and assets. |
| [FernandoH-G/Turtles-Racing](https://github.com/FernandoH-G/Turtles-Racing) | 2D racing | Small 2D Godot racing game with race logic and scenes. |

## 9. Sports Arcade Games

Simplified sports games focused on speed, readability, and local multiplayer.

Classic examples: NBA Jam, Track & Field, Virtua Tennis, NFL Blitz.

Core loop: quick matches, reflexes, exaggerated physics.

Design DNA: simplified rules, big animations, multiplayer rivalry.

| Repository | Inspired by | Notes |
|---|---|---|
| [DotcYuanJia/Godot_BasketballGame](https://github.com/DotcYuanJia/Godot_BasketballGame) | Basketball | MIT-licensed Godot basketball project with scenes and scripts. |
| [matheuscumpian/godot-soccer](https://github.com/matheuscumpian/godot-soccer) | Soccer | Cubedude Kickabout soccer game by GameDev.tv, built with Godot. |
| [ryan-haskell/godot-soccer-demo](https://github.com/ryan-haskell/godot-soccer-demo) | Soccer physics | Small Godot soccer demo for physics experimentation. |
| [krimshi/godot-soccer](https://github.com/krimshi/godot-soccer) | 2D soccer | MIT-licensed 2D soccer game in Godot. |
| [ktawaststjerna/godot-ball-game](https://github.com/ktawaststjerna/godot-ball-game) | Soccer-like ball game | Simple Godot soccer/ball game with multiplayer capabilities. |

## 10. Puzzle Arcade Games

Fast repeatable puzzle systems built around pattern recognition and pressure.

Classic examples: Tetris, Puyo Puyo, Puzzle Bobble, Columns.

Core loop: arrange pieces, clear space, survive increasing speed.

Design DNA: combos, chains, garbage blocks, escalating tempo.

| Repository | Inspired by | Notes |
|---|---|---|
| [jpcerrone/PokeTetris](https://github.com/jpcerrone/PokeTetris) | Tetris | Godot 4 modern Tetris clone with SRS, hold, seven-bag, ghost piece, and scoring. |
| [Sparrowworks/Tetris](https://github.com/Sparrowworks/Tetris) | Tetris | Godot Tetris clone with visual polish and ghost block support. |
| [russmatney/blox](https://github.com/russmatney/blox) | Tetris / Puyo Puyo | Cozy falling-block puzzle made for Godot Wild Jam 70. |
| [Starbit04/DrMarioMania](https://github.com/Starbit04/DrMarioMania) | Dr. Mario | Godot 4.3 .NET Dr. Mario fan game. |
| [Sparrowworks/Sokoban](https://github.com/Sparrowworks/Sokoban) | Sokoban | Godot 4 Sokoban clone with improved menus and undo support. |

## 11. Light-Gun Shooters

Players aim at targets and shoot, originally with physical gun controllers.

Classic examples: Duck Hunt, Operation Wolf, Time Crisis, House of the Dead.

Core loop: aim, shoot, reload, avoid civilians.

Design DNA: target prioritization, timed sections, branching scenes.

The public Godot repo pool for literal light-gun arcade clones is thin, so Duck Hunt-style mouse/reticle projects are the most useful matches.

| Repository | Inspired by | Notes |
|---|---|---|
| [AndresDavidCalderon/Godot-Duck-Hunt](https://github.com/AndresDavidCalderon/Godot-Duck-Hunt) | Duck Hunt | MIT-licensed Godot Duck Hunt project with gun, duck, bullet, and game scenes. |
| [wlribeiro/godot-duck-hunter](https://github.com/wlribeiro/godot-duck-hunter) | Duck Hunt | Duck-hunter project with Godot source under the `source` folder. |
| [0xNunoMiranda/Godot-DuckHunt](https://github.com/0xNunoMiranda/Godot-DuckHunt) | Duck Hunt | Small Duck Hunt-style Godot project. |
| [panihans/godot-duck-hunt](https://github.com/panihans/godot-duck-hunt) | Duck Hunt | Small Duck Hunt-style Godot repository. |

## 12. Rail Shooters

The game moves the player through a path while they aim, dodge, and shoot.

Classic examples: Space Harrier, Star Fox, After Burner, Panzer Dragoon.

Core loop: aim, dodge, shoot while the game controls forward motion.

Design DNA: spectacle, cinematic movement, reflex dodging.

| Repository | Inspired by | Notes |
|---|---|---|
| [crogersdev/rail_shooter_v1](https://github.com/crogersdev/rail_shooter_v1) | Star Fox 64-like rail shooter | Godot rail shooter with camera rig, enemies, bullets, rings, targets, and 3D assets. |
| [johnpitchers/arcade-tribute](https://github.com/johnpitchers/arcade-tribute) | 3D Galaga / Space Invaders | Not a pure rail shooter, but useful for 3D arcade shooting and staged enemy patterns. |
| [Hugo-Dz/super-godot-galaxy](https://github.com/Hugo-Dz/super-godot-galaxy) | Mario Galaxy-like 3D movement | Not a shooter, but useful as a Godot 4 reference for guided 3D movement and camera feel. |

## 13. Vehicle Combat / Cockpit Action

The player controls a vehicle, often emphasizing steering, aiming, and spectacle.

Classic examples: Battlezone, Star Wars Arcade, After Burner, Hydro Thunder.

Core loop: steer/fly/drive, shoot or avoid hazards.

Design DNA: immersive cabinets, physical controls, spectacle-first design.

Direct Battlezone/After Burner-style Godot repos are uncommon. Battle City/tank and combat-racing projects are the closest verified public matches.

| Repository | Inspired by | Notes |
|---|---|---|
| [redspirit/godot-battle-city](https://github.com/redspirit/godot-battle-city) | Battle City | 8-bit tank game implemented with Godot 2D Engine. |
| [dms-akshat/godot_battle_city](https://github.com/dms-akshat/godot_battle_city) | Battle City | GPL-3.0 Godot Battle City-style project with levels, bullets, scenes, and assets. |
| [hxhieu/godot-battle-city](https://github.com/hxhieu/godot-battle-city) | Battle City | Godot Battle City project with models, objects, scenes, scripts, and GDNative library. |
| [madhupprasad/Tank1999](https://github.com/madhupprasad/Tank1999) | Retro tank game | Godot retro tank game with assets, scenes, and scripts. |
| [kiralymark/GodotTankGame](https://github.com/kiralymark/GodotTankGame) | 3D tank action | 3D tank game made in Godot; source lives under `TankGame`. |
| [pranav-dp/rashroad](https://github.com/pranav-dp/rashroad) | Combat racing | Road Rash-like pseudo-3D racing with combat. |

## 14. Rhythm and Music Games

The player performs timed inputs to music.

Classic examples: Dance Dance Revolution, Beatmania, GuitarFreaks, Taiko no Tatsujin.

Core loop: match prompts to the beat.

Design DNA: custom controllers, score ranking, performance mastery.

| Repository | Inspired by | Notes |
|---|---|---|
| [v-pukman-gd/godot-taiko](https://github.com/v-pukman-gd/godot-taiko) | Taiko no Tatsujin | CC0 Taiko clone in Godot with songs, notes, drums, score, controls, and screens. |
| [yKoihsU/Godot-RhythmGameCore](https://github.com/yKoihsU/Godot-RhythmGameCore) | Rhythm-game framework | MIT-licensed lightweight Godot rhythm game framework. |
| [jppan/rhythmgame](https://github.com/jppan/rhythmgame) | osu!mania-style rhythm | Godot rhythm game with osu!mania 4K import. |
| [SrtHero278/idk-rhythm](https://github.com/SrtHero278/idk-rhythm) | Rhythm game | Small Godot rhythm game with scenes, scripts, assets, and autoloads. |

## 15. Action Puzzle / Single-Screen Action

Hybrid games where the challenge is contained in compact arenas or puzzle-like combat spaces.

Classic examples: Dig Dug, Bomberman, Qix, Lode Runner.

Core loop: manipulate the environment, trap enemies, clear objectives.

Design DNA: simple rules that create deep tactical pressure.

| Repository | Inspired by | Notes |
|---|---|---|
| [akien-mga/dynadungeons](https://github.com/akien-mga/dynadungeons) | Bomberman | GPL-3.0 Bomberman clone for Godot 3.x with local multiplayer and power-ups. |
| [ydanielsb97/godot-bomberman-remake](https://github.com/ydanielsb97/godot-bomberman-remake) | Bomberman | MIT-licensed Godot 4 Bomberman remake made for learning purposes. |
| [Amegatron/godot-bomberman](https://github.com/Amegatron/godot-bomberman) | Bomberman | Experimental implementation of Bomberman using Godot. |
| [Sparrowworks/Sokoban](https://github.com/Sparrowworks/Sokoban) | Sokoban | Godot 4 push-box puzzle clone with improved menus and undo support. |
| [NEW-CYLANDIA/little-warioware](https://github.com/NEW-CYLANDIA/little-warioware) | WarioWare-style microgames | Godot microgame collection built around fast single-screen challenges. |

## 16. Survival / Endurance Games

The point is to last as long as possible under escalating pressure.

Classic examples: Asteroids, Robotron: 2084, Defender, Geometry Wars.

Core loop: survive escalating enemy pressure.

Design DNA: high-score chasing, enemy swarms, tight controls.

| Repository | Inspired by | Notes |
|---|---|---|
| [kidscancode/space_rocks](https://github.com/kidscancode/space_rocks) | Asteroids | Asteroids-like game from the KidsCanCode Godot tutorial ecosystem. |
| [tstamborski/mission-apophis-2036](https://github.com/tstamborski/mission-apophis-2036) | Asteroids | Godot 4.0 Asteroids clone with story framing and downloads. |
| [taylorhansen/Asteroids-Clone](https://github.com/taylorhansen/Asteroids-Clone) | Asteroids | Learning project with keyboard and mouse controls. |
| [Toxe/godot-defender-clone](https://github.com/Toxe/godot-defender-clone) | Defender | WIP Defender clone with side-scrolling survival pressure. |
| [mlm-games/asteroids-revenge](https://github.com/mlm-games/asteroids-revenge) | Asteroids | Asteroids-inspired arcade shooter. |

## 17. Pinball and Electromechanical Descendants

Physics-driven games descended from pinball and other mechanical arcade machines.

Classic examples: traditional pinball, video pinball, redemption hybrids.

Core loop: keep the ball alive, hit targets, trigger modes.

Design DNA: physics, score multipliers, objectives layered on chaos.

| Repository | Inspired by | Notes |
|---|---|---|
| [dbisdorf/professor-pinball](https://github.com/dbisdorf/professor-pinball) | Pinball | Full 2D pinball game with bonuses, challenge events, and controller support. |
| [Calinou/libre-pinball](https://github.com/Calinou/libre-pinball) | Pinball | Free/libre pinball table with translations and classic table mechanics. |
| [LeeTeng2001/Pac-Pin-Pong](https://github.com/LeeTeng2001/Pac-Pin-Pong) | Pac-Man / Pinball / Space Invaders | Local multiplayer arcade mash-up. |

## 18. Redemption / Ticket Games

Games designed around tickets, prizes, or short physical-skill reward loops.

Classic examples: skee-ball, basketball hoops, coin pushers, claw machines.

Core loop: short skill or chance challenge, then reward payout.

Design DNA: physicality, prizes, payout tuning.

The Godot public repo pool is very thin here. Coin-pusher and simple sports-arcade projects are the best current anchors.

| Repository | Inspired by | Notes |
|---|---|---|
| [emanlaw/godot-Coin-Pusher](https://github.com/emanlaw/godot-Coin-Pusher) | Coin pusher | Godot coin-pusher project with scenes, scripts, docs, and `project.godot`. |
| [DotcYuanJia/Godot_BasketballGame](https://github.com/DotcYuanJia/Godot_BasketballGame) | Basketball arcade | Simple Godot basketball game; useful for hoop-shot redemption mechanics. |
| [FernandoH-G/Turtles-Racing](https://github.com/FernandoH-G/Turtles-Racing) | Short-loop race | Small race project useful as a short, repeatable arcade challenge reference. |

## 19. Score Attack / Abstract Action

Games built around pure mechanics rather than character progression or narrative.

Classic examples: Tempest, Centipede, Missile Command, Breakout.

Core loop: survive, clear threats, maximize score.

Design DNA: elegant rules, brutal difficulty curves, one-more-run pressure.

| Repository | Inspired by | Notes |
|---|---|---|
| [Jazuk1970/godot-centipede](https://github.com/Jazuk1970/godot-centipede) | Centipede | MIT-licensed Centipede clone written in Godot. |
| [richardbonneau/godot-missile-command-clone](https://github.com/richardbonneau/godot-missile-command-clone) | Missile Command | Godot Missile Command clone with bunkers, nukes, anti-nukes, buildings, and GUI scenes. |
| [Sparrowworks/Brick-Breaker](https://github.com/Sparrowworks/Brick-Breaker) | Arkanoid / Breakout | Godot 4 brick-breaker with a level editor. |
| [YeOldeDM/godot-breakout-example](https://github.com/YeOldeDM/godot-breakout-example) | Breakout / Arkanoid | Simple Godot 2.1.4 Breakout/Arkanoid example. |
| [zrckr/pong](https://github.com/zrckr/pong) | Pong | Simple Godot 4 Pong implementation released under the Unlicense. |
| [vnglst/pong-wars](https://github.com/vnglst/pong-wars) | Pong-like abstract action | Godot implementation of the Pong Wars concept. |

## 20. Arcade Adventure / Action-Adventure Hybrids

Arcade immediacy mixed with exploration, rooms, objectives, or light RPG structure.

Classic examples: Gauntlet, Wonder Boy, Golden Axe, Cadash.

Core loop: fight, collect, progress, survive.

Design DNA: fantasy themes, light RPG elements, co-op progression.

| Repository | Inspired by | Notes |
|---|---|---|
| [randyyaj/Godauntlet](https://github.com/randyyaj/Godauntlet) | Gauntlet 1985 | GPL-3.0 recreation of Gauntlet 1985 in Godot 4. |
| [loudsmilestudios/TetraForce](https://github.com/loudsmilestudios/TetraForce) | Game Boy Color Zelda | Zelda-inspired action-adventure with online multiplayer. |
| [fornclake/zelda](https://github.com/fornclake/zelda) | The Legend of Zelda | Godot 4.0 Zelda clone. |
| [Delta12Studio/Lango_GodotRPG](https://github.com/Delta12Studio/Lango_GodotRPG) | Zelda-like RPG | RPG/action-adventure project with Zelda-like framing. |
| [w84death/mystic-treasure-hunt](https://github.com/w84death/mystic-treasure-hunt) | Arcade adventure | MIT-licensed first-person tile-based arcade adventure/RPG made with Godot. |
