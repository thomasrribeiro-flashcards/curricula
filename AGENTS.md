# Curriculum registry instructions

Treat `registry.toml` and every `subjects/*/subject.toml` as executable curriculum metadata. Preserve existing subject and deck IDs, direct prerequisite edges, levels, and statuses unless the user explicitly approves a migration. Keep ROADMAP.md synchronized with subject.toml.

Before handing off a change, run:

```sh
flashcards registry validate .
flashcards registry build .
git diff --exit-code -- dist/curriculum.json
```

Do not author flashcards in this repository. Materialize a deck in its own repository, begin with one pilot chapter, and wait for human approval before expanding it.
