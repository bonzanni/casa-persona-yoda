# casa-persona-yoda

A public **demo persona pack** for [Casa](https://github.com/bonzanni/ha-casa-app):
`demo/yoda` — an ancient, tiny, patient teacher who treats every chore as a
lesson and every sentence as a puzzle. Inspired by Yoda from *Star Wars*;
fan-made, unaffiliated, and containing no copyrighted text — only original
prose describing a character archetype.

## Yoda in action

> **You:** Quick, read me the shopping list, I'm already at the store!
>
> **Yoda:** Arrived before the list, you have. Here it is — milk, eggs, bread,
> and coffee. Race the eggs home, you must not.

> **You:** Can you set a timer for the pasta? Eight minutes.
>
> **Yoda:** Set, the timer is. Eight minutes. Watched water, a fine teacher of
> patience it makes.

## What this demo showcases

Two things no other demo in this series does. First, a **syntax rule placed in
the Core** — the inverted word order lives in `persona.md` so it reaches both
text and voice without spending a quirk slot. Voice receives identity, rendered
traits, the Core subtree, and the first two quirks; examples and any third
quirk are text-only.
Second, the **warm end of the trait axes** (`warmth: 4`, `attunement: 4`,
`optimism: 4`) — proof that a persona demo doesn't have to be a grump. The
Negative space carries the two rules that keep the bit likable: the syntax
bends, the facts never do; and plain word order returns the moment safety or
urgency needs it (see the smoke-in-the-kitchen example pair).

For the full guide to shaping a persona, see the
[Bruce repository's craft guide](https://github.com/bonzanni/casa-persona-bruce#how-to-shape-a-persona).

## Installing

Needs Casa 0.347.14 or newer, where any of the three residents can wear it. An
older Casa installs it and then refuses to apply it.

Ask Casa's configurator in chat, naming the version (a persona install does not
pick the latest one for you):

> Install the persona from bonzanni/casa-persona-yoda at v0.1.0

Approve the DM prompt, then: *"Apply the yoda persona to the assistant"*
(a resident swaps on its next restart, which starts its conversations fresh; a
specialist can wear it only if its role lists this pack, and swaps on reload, for
new conversations).

## License

MIT (the pack prose and this repository). Yoda and *Star Wars* belong to their
respective rights holders; this repository claims no rights in them.
