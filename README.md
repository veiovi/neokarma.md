# neokarma.md

A story and its world in one human-readable, editable Markdown file.

neokarma.md describes the premise, universe, character voice, rules, pacing and milestones of an interactive adventure. Optional sections add branches, consequences, dice, conditions and other game mechanics. A player runs the structure; an AI character tells the story around the person's choices.

- [Read the current specification snapshot](neokarma.md)
- [Try a small, complete example](examples/the-lantern-path.neokarma.md)
- [Read the illustrated guide and latest specification](https://neokarma.md/)
- [Try stories in AI Pets](https://aipets.com/studio/stories)

## Start with one file

Download the example, open it in a text editor and change the world or the events. Keep the headings and any linked destination names consistent. The first milestone opens the story; the last ends it. You can also give [the specification](neokarma.md) to an AI agent and describe the adventure you want to write.

Standalone single-file stories are supported. Reusable modular worlds, characters and rules are future direction, not a requirement or an implemented import syntax in this edition. The neokarma.md website is documentation; this repository does not announce a marketplace launch.

## Use it on AI Pets

1. Sign in and open **Studio → Stories → Import neokarma.md**.
2. Choose your file, review the reader's errors and warnings, then choose **Import and open story**. This creates a new private story without assigning it to a pet.
3. Choose **Play story**, select an owned pet, and configure the provider keys required by that pet. Browser play uses your providers; no hardware is required.
4. Edit and export your file in Studio. Device assignment is a separate action for supported AI Pets hardware.

Saving changes to an assigned story restarts it for its assigned pets and clears their adventure diaries. Experiment with a new unassigned copy first. A story's role and voice do not replace the selected pet's identity.

## Status

This is the **2026-10-25 specification snapshot**, using the existing `neokarma: 1` file marker. It is a documentation release, not a new parser version or a promise of universal compatibility.

AI Pets implements file import/export, browser playback, milestones, scenes, voice, pacing, branches, consequences and optional game mechanics. The specification also documents **fights under an internal test gate**: ordinary accounts and Pocket devices currently play a `Fight:` place as an ordinary milestone. Animation and sound references require assets supplied by the runtime; a Markdown file does not embed them.

The specification's AI Pets compatibility profile describes that implementation's limits, including a 100 KiB file cap. Those are not universal requirements for other implementations.

See [STATUS.md](STATUS.md) for provenance and validation, and [CONTRIBUTING.md](CONTRIBUTING.md) for feedback.

## Licensing

No specification-wide reuse license has been selected for this repository. Public availability does not imply an MIT, Apache or Creative Commons license grant. The licenses of separate AI Pets software or community story releases do not automatically apply here. A license choice remains with the rights holder.
