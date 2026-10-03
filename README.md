# No Man’s Sky — Technology Layout Assistant

An experimental in-game quality-of-life project for planning technology layouts in No Man’s Sky.

## Project status

Research and preflight are complete. The project has no implementation, packaged mod, supported game build, or release yet. The next proposed milestone is a read-only proof of concept for showing confirmed supercharged-slot positions in the Multi-Tool technology inventory.

## Goals

- Make supercharged slots easier to identify.
- Show technology adjacency only when the behavior is verified for the supported game build.
- Compare layout statistics only when calculations are validated against the game.
- Keep layout variants and previews separate from the live inventory.
- Consider automatic application only if it can use safe, native in-game actions.

## Safety and accuracy

The planned first proof of concept is read-only. It will not edit save files or change the live inventory. A preview must use a separate model of the proposed layout. No adjacency result or statistic is described as exact until it has been checked against the game on a specifically identified build.

Compatibility will be reported per game build and platform. An unknown build must disable runtime hooks instead of guessing.

## Roadmap

1. Read-only Multi-Tool inventory observer and supercharged-slot markers.
2. Verified adjacency visualization.
3. Validated statistics comparison for a limited set of technologies.
4. Isolated layout variants and previews.
5. Optional optimizer, after the model is validated.
6. Consider safe in-game application, or retain manual instructions if safe application cannot be demonstrated.

## License

No license has been selected. Until a license is added, repository contents are not offered for reuse; public visibility does not itself grant permission to copy or distribute the work.

## Contributions

The contribution and testing process will be documented before implementation begins. Please use GitHub issues for research questions and feature discussion.
