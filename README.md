# Curricula

This repository is the published source of truth for Thomas Ribeiro's cross-subject learning graph. Deck repositories remain independent; this registry owns subject metadata, direct prerequisite edges, recommended preparation, and curriculum order.

## Validate and compile

```sh
npx --yes github:thomasrribeiro/flashcards registry validate .
npx --yes github:thomasrribeiro/flashcards registry build .
```

Edit a subject package under `subjects/`, validate the complete graph, rebuild `dist/curriculum.json`, and publish changes through a pull request. The compiled index is deterministic and is consumed by the flashcards website.
