# Pokémon Nova

> **Development prototype for Apple platforms**  
> Current public status: **Active development / pre-alpha**  
> Last updated: **26 September 2026**

Pokémon Nova is an experimental single-player RPG project focused on native Apple platforms. The current prototype explores a 2.5D overworld, native input across Apple devices, story-driven exploration, quests and a progressively expanding Pokémon-style game loop.

This repository is under active development. Features, compatibility and content may change substantially before a public release.

## Current development status

The project currently includes a working foundation for:

- native app startup and game-state flow
- 2.5D world exploration with a fixed gameplay camera
- multiple connected map areas, interiors, islands, tunnels and underground sections
- player movement and collision-oriented world navigation
- touch, keyboard and game-controller input
- starter selection and basic Pokémon party/state foundations
- NPCs, signs, interactive world objects and quests
- inventory and one-time rewards
- health, damage and recovery foundations
- game menus and longer scrollable information panels
- persistent-style event flags and conditional game events in the runtime model
- conditional dialogue choices
- lightly animated water
- softer, more rounded tree presentation
- subtle idle and walking animation for the player character

### Currently being expanded

The next development areas include:

- persistent save games and recovery
- larger branching conversations and story-event sequencing
- broader world-event handling
- battle-system implementation
- encounters, capture and progression loops
- more complete Pokémon data and gameplay systems
- world content, environments and visual polish
- audio, effects and animation improvements
- performance, accessibility and device testing

The project is still a **technical gameplay prototype**, not a feature-complete game or release candidate.

## Platforms

| Platform | Current project status | Minimum / target configuration | Input |
|---|---|---|---|
| **iPhone** | Primary mobile development target | iOS 17.0+ | Touch, compatible game controller |
| **iPad** | Supported by the iOS target | iPadOS based on the iOS 17.0+ target | Touch, compatible game controller |
| **macOS** | Native desktop target | macOS 27.0+ in the current project configuration | Keyboard, mouse/trackpad, compatible game controller |
| **iOS Simulator** | Development target available | Current compatible Xcode simulator runtimes | Simulated touch / development input |

### Development devices

Primary physical-device work currently includes:

- **iPhone 17 Pro Max**
- **iPhone 12 Pro Max**
- Apple Silicon Mac development environment

[More Device](https://github.com/Axonsoft-Software/Pokemon_Nova/tree/main/Device-Support)

Device compatibility is still being validated. A device being listed here does **not** mean the project has completed release-quality certification on that hardware.

## Technology

Pokémon Nova is being developed as a native Apple-platform project using:

- **Swift**
- **Metal** for graphics
- **Xcode**
- native iOS/iPadOS and macOS application targets

Public documentation intentionally stays at a product and capability level. Internal architecture, source-level implementation details, algorithms, signing identifiers, private configuration and development credentials are not documented here.

## Verification status

The latest fully documented Xcode-verified gameplay baseline is **development step 25**, where the shared gameplay core completed **150 automated tests** and both Apple app targets were reported as building successfully.

Development steps **26–27** added the latest visual animation work and conditional dialogue functionality. Their portable/core checks passed, but a complete Xcode, Metal and physical-device regression pass is still pending for those newest changes.

This distinction is intentional: a feature is not presented as device-verified until it has actually completed the corresponding Apple-platform test pass.

## Development roadmap

The long-term direction is an offline-first single-player RPG with:

- a larger multi-region world
- story progression and recurring characters
- exploration, quests and world interactions
- Pokémon collection and team management
- encounters and capture
- single and double battles
- progression, evolution and additional Pokémon systems
- gyms, league progression and endgame content
- expanded visual effects, animation and audio

The roadmap is iterative. Individual systems may be redesigned as development and device testing continue.

## Repository and development notes

This README is intentionally suitable for a public GitHub overview. It does not expose private implementation documentation or internal project details.

Before any public distribution, the project still requires additional technical testing, content review, licensing review and release preparation.

## Legal notice

Pokémon is a trademark of Nintendo / Creatures Inc. / GAME FREAK inc. This project is an unofficial fan-development project and is not affiliated with, endorsed by or sponsored by Nintendo, Creatures Inc., GAME FREAK inc. or The Pokémon Company.

Any third-party names, trademarks or assets remain the property of their respective owners. Public distribution of game content or assets should only occur where the necessary rights and permissions are available.
