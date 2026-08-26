# Project Smart Home — Example Blueprints

A growing collection of Home Assistant blueprints from
[Project Smart Home](https://www.skool.com/) — real automations shared so
you can see how they're built, import them straight into your own setup,
and learn patterns you can adapt for your own home.

These aren't toy examples. They're pulled from a real, running smart home,
so you'll see practical patterns for things like state-based triggers,
repeat loops, choose blocks, and template logic — the building blocks that
let Home Assistant respond to your home instead of you managing it.

## Why blueprints?

A blueprint turns a working automation into something reusable: instead of
copying raw YAML and manually rewriting entity IDs, you import it and pick
your own entities from dropdowns. It's also one of the best ways to learn —
reading a well-built blueprint shows you the *why* behind the YAML, not
just the *what*.

## Blueprints in this repo

| Blueprint | What it does |
|---|---|
| [F1 Safety Car / VSC Light Flasher](./f1_safety_car_light_flasher.yaml) | Flashes a light when an F1 session goes live or the track goes to Virtual Safety Car, at different speeds so you can tell them apart |

*(More added as they're built — see [Project Smart Home](https://www.skool.com/) for the full library and walkthroughs.)*

## How to import a blueprint

1. Click into any blueprint file above and copy the **raw** URL
2. In Home Assistant: **Settings → Automations & Scenes → Blueprints → Import Blueprint**
3. Paste the raw URL and import
4. Configure the inputs (your entities, colors, timings) and save

Or use a one-click import badge where provided on individual blueprint pages.

## About Project Smart Home

Project Smart Home is a community focused on simplifying home automation —
sharing real implementation blueprints, walkthroughs, and the reasoning
behind them, so you're not just copy-pasting YAML but actually understanding
how to build your own.

---
Questions or ideas for a blueprint you'd like to see? Open an issue or drop it in the community.
