# Better Edit Premium

A Geometry Dash editor-tools mod project for Geode.

**Status:** starter scaffold only. It is not a finished mod and has not been
compiled or tested in Geometry Dash. Do not submit this scaffold as a release.

## Build setup

1. Install Geometry Dash and Geode.
2. Install the Geode SDK / CLI using the official Geode getting-started guide:
   https://docs.geode-sdk.org/getting-started/
3. For a fresh project, the official recommended starting point is `geode new`.
   Compare this scaffold with the current official template before building.
4. Configure your Geode SDK and run `geode build` from the project directory.
5. Test in-game, inspect logs, and fix warnings/errors before packaging.

## Planned roadmap

- Select All Same Type
- Trigger Target Visualizer
- Object search and labels
- Swipeable object pages
- Persistent custom copy storage
- Decoration helper tools
- AI assistant for editor explanations and suggestions (advice-only)

## Important Geode Index limitation

The current Geode mod guidelines restrict generative AI features that place,
modify, or delete level objects, and say AI must not be used for creating levels.
Therefore, an index-compliant design should keep AI as an explicitly labeled
advice / explanation feature and keep object placement under direct user control.
Check the current rules before submission:
https://docs.geode-sdk.org/mods/guidelines/

## Publishing

A release requires a real build, in-game testing, a versioned `.geode` package,
source code, complete metadata/icon, and submission for Geode Index review.
See: https://docs.geode-sdk.org/mods/publishing/
