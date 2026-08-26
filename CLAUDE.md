# Project Smart Home Blueprints

## Repo structure
- Root `README.md` = project entry point + blueprint index table.
- `Home Assistant Blueprints/` = actual `.yaml` blueprint files.

## Rule: keep README in sync
Whenever a new blueprint is added to `Home Assistant Blueprints/`, update the root `README.md` blueprint table with a new row:

| Blueprint | What it does |
|---|---|
| [Blueprint Name](./Home%20Assistant%20Blueprints/filename.yaml) | one-line description |

- Link path must URL-encode the space in `Home Assistant Blueprints` as `%20`.
- Description = one line, matches tone of existing rows (practical, plain).
- Pull the name + description from the blueprint's own `name:` and `description:` fields when possible.
