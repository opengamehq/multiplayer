# opengame-multiplayer

Build multiplayer for a browser game, or a lobby where bots stand in for players. Covers one authority deciding what happened, a relay that only forwards and polices, capped messages, host migration and rejoin, smooth remote players, the lobby as the loading screen, a match that never pauses, bot lobbies, fair spawns, voice, testing several browsers and naming what was never proven.

It is one of the [OpenGame](https://opengame.io) agent skills, which teach a coding agent such
as Claude Code, Codex, Cursor or OpenCode to build a browser game and put it online.

## Install

```bash
npx skills add opengamehq/multiplayer
```

The skill installs under its own name, `opengame-multiplayer`. Every OpenGame skill, each under its own
name, installs from [opengamehq/opengame](https://github.com/opengamehq/opengame):

```bash
npx skills add opengamehq/opengame
```

How the skills fit into making and shipping a game is at [docs.opengame.io](https://docs.opengame.io).

## Changes

This is version 1.1.1. [CHANGELOG.md](CHANGELOG.md) lists what changed in each one.

## Issues

OpenGame's release tooling writes this repository from [opengamehq/opengame](https://github.com/opengamehq/opengame),
so a change made here is replaced by the next release, and it does not take pull requests.
Open an issue [there](https://github.com/opengamehq/opengame/issues) for a skill that teaches the wrong thing.

## License

[Apache 2.0](LICENSE).
