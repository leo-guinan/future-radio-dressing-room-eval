# Changing EVAL

EVAL is a character in Future Radio, and you can help shape them. If an episode made EVAL's
criticism land wrong, or right in a way that should become canon, propose it here.

## Three ways in

1. **Talk to EVAL first.** `git clone <this repo> && cd <this repo>`, then
   `npx github:leo-guinan/future-radio-character-bible chat .`. `/propose <your note>` writes a
   viewer note with the last few lines of your conversation attached. Commit it on a branch and
   open a pull request.
2. **Add a viewer note.** Create `memory/viewer-notes/YYYY-MM-DD-short-title.md`:

   ```markdown
   ---
   from: your name or handle (or "anonymous")
   experience: what you watched or heard — the episode, the scene, the moment
   episode: E02
   ---
   What should be true about EVAL from now on, in a sentence or two.
   ```

3. **Edit CHARACTER.md** for changes to who EVAL *is*: the job, constraints or recurring conflict.
   These get the closest review.

No GitHub account? Open an issue with the "Viewer note" form instead.

## What can't change in a pull request

- `history/` and `history.jsonl` are the record of what EVAL actually did in the writers' room.
  Written by the room only.
- `memory/notes.md` is append-only. Respond to an old note with a new one.
- `bible/` is generated. Leave it out of your PR; it's rebuilt on merge.

A check runs on every pull request and explains anything it rejects.
