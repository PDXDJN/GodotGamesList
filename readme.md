# Godot Arcade Game Repositories

A curated index of open-source Godot projects that remake, clone, pay tribute to, or closely study classic arcade and arcade-adjacent games.

Last reviewed: 2026-06-19.

## Scope

This list focuses on playable projects, learning projects, and focused engines/frameworks where the classic inspiration is clear from the repository name, README, topics, or description.

Included:

- Godot projects inspired by arcade staples such as Pong, Breakout, Space Invaders, Asteroids, Pac-Man, Bomberman, Frogger, Snake, Tetris, Sokoban, Galaga, Contra, Defender, Metal Slug, and pinball.
- Classic-console-adjacent projects when they are commonly useful to arcade-game developers, such as Mario, Sonic, Zelda-like, and Dr. Mario projects.
- Small learning projects if the repo is specific, runnable, and useful as a reference.

Not included:

- Generic Godot templates, plugins, engines, or awesome lists unless they point directly to relevant games.
- Repositories where Godot is only mentioned incidentally.
- Closed-source games without a public repository.

## Quick Picks

| Use case | Repositories |
|---|---|
| Bomberman-style local multiplayer | [akien-mga/dynadungeons](https://github.com/akien-mga/dynadungeons) |
| Modern Godot 4 Tetris reference | [jpcerrone/PokeTetris](https://github.com/jpcerrone/PokeTetris), [Sparrowworks/Tetris](https://github.com/Sparrowworks/Tetris) |
| Breakout or Arkanoid in Godot 4 | [Sparrowworks/Brick-Breaker](https://github.com/Sparrowworks/Brick-Breaker) |
| Beginner-friendly Pong | [endlessm/moddable-pong](https://github.com/endlessm/moddable-pong), [zrckr/pong](https://github.com/zrckr/pong) |
| Space Invaders in Godot 4 | [drxwat/godot-invaders](https://github.com/drxwat/godot-invaders), [Hernandez712/SpaceInvaders-Godot](https://github.com/Hernandez712/SpaceInvaders-Godot), [andreas-paul/space-invaders](https://github.com/andreas-paul/space-invaders) |
| Side-scrolling shooters | [galexbh/contra](https://github.com/galexbh/contra), [VictorRandall/metalslug_clone](https://github.com/VictorRandall/metalslug_clone), [JSolde/Godot-demo-2D-Side-Scrolling-and-Wraparound-Shooter](https://github.com/JSolde/Godot-demo-2D-Side-Scrolling-and-Wraparound-Shooter), plus [more side-scrolling shooters](side-scrolling-shooters.md) |
| Pac-Man style maze chase | [clarkjohn/wizard-chase](https://github.com/clarkjohn/wizard-chase), [DOAmaster/PacmanGodot](https://github.com/DOAmaster/PacmanGodot), [Gianpyy/yet-another-pacman-clone](https://github.com/Gianpyy/yet-another-pacman-clone) |
| Pinball | [dbisdorf/professor-pinball](https://github.com/dbisdorf/professor-pinball), [Calinou/libre-pinball](https://github.com/Calinou/libre-pinball) |

## Game Repository Lists

| List | Notes |
|---|---|
| [Paddle, brick, and pinball](paddle-brick-pinball.md) | Pong, Breakout, Arkanoid, pinball, and hybrid paddle-table projects. |
| [Maze, chase, and arena action](maze-chase-arena-action.md) | Pac-Man-style maze games, Bomberman-style arena games, and close variants. |
| [Space shooters and fixed shooters](space-shooters-fixed-shooters.md) | Space Invaders, Galaga, Asteroids, and related fixed-screen or survival shooters. |
| [Falling blocks and tile puzzles](falling-blocks-tile-puzzles.md) | Tetris, Dr. Mario, Sokoban, and other tile-focused puzzle references. |
| [Snake, crossing, and short-loop arcade](snake-crossing-short-loop-arcade.md) | Snake, Frogger, and concise arcade-loop projects. |
| [Platform, physics, and adventure adjacent](platform-physics-adventure-adjacent.md) | Mario, Sonic, Zelda-like, and beat-'em-up references useful to arcade-game developers. |
| [Side-scrolling shooters](side-scrolling-shooters.md) | Contra-like run-and-gun games, Metal Slug-style projects, Defender-style horizontal shooters, and adjacent shmup references. |
| [Skill and knowledge games](skill-knowledge-games.md) | Trivia, quiz, memory, word puzzles, Minesweeper, Sudoku, Wordle, typing, and reaction-speed games. |

## Reference Lists

| List | Notes |
|---|---|
| [Arcade game archetypes](arcade-archetypes.md) | Taxonomy of 20 arcade design archetypes, with representative Godot repositories for each. |
| [Godot MCP servers](godot-mcp-servers.md) | MCP servers and Godot editor integrations for AI-assisted Godot workflows. |
| [Resources](resources.md) | Royalty-free music, free sound effects, free game graphics, useful Godot tools, and reusable game components. |

## Related Curated Lists

| Repository | Notes |
|---|---|
| [godotengine/awesome-godot](https://github.com/godotengine/awesome-godot) | Large Godot resource list; includes some games and demos such as DynaDungeons and BlockPop. |
| [radek-sprta/awesome-game-remakes](https://github.com/radek-sprta/awesome-game-remakes) | Broad open-source game remake list, not Godot-specific. |
| [leereilly/games](https://github.com/leereilly/games) | Archived but still useful list of open-source games. |
| [bobeff/open-source-games](https://github.com/bobeff/open-source-games) | Large open-source games catalog. |

## Contribution Guidelines

Additions are welcome. Please keep entries useful and verifiable.

For each new entry:

- Link directly to the public repository.
- Confirm it is a Godot project, preferably by checking for `project.godot`, README instructions, topics, or explicit description.
- Put it in the closest category.
- Keep notes factual and short.
- Prefer original source repositories over forks unless the fork is the active maintained version.
- Avoid linking to abandoned empty shells unless they contain runnable source or a useful technique.

Suggested row format:

```markdown
| [owner/repo](https://github.com/owner/repo) | Classic inspiration | Short factual note. |
```

## Search Seeds

Useful search terms for finding more repositories:

```text
site:github.com Godot Tetris clone
site:github.com Godot Pac-Man clone
site:github.com Godot Space Invaders clone
site:github.com Godot Asteroids clone
site:github.com Godot Breakout Arkanoid clone
site:github.com Godot Bomberman clone
site:github.com Godot Frogger clone
site:github.com Godot Galaga clone
site:github.com Godot Pong clone
site:github.com Godot Snake arcade
site:github.com Godot Sokoban clone
site:github.com Godot Contra clone
site:github.com Godot Metal Slug clone
site:github.com Godot run-and-gun
site:github.com Godot side-scrolling shooter
site:github.com Godot Defender clone
site:github.com Godot Dig Dug clone
site:github.com Godot Lode Runner clone
site:github.com Godot Missile Command clone
site:github.com Godot Donkey Kong clone
site:github.com Godot beat em up brawler
site:github.com Godot Bubble Bobble clone
site:github.com Godot rhythm game
```
