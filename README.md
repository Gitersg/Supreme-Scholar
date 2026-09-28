# Supreme Scholar

A local study ledger. Open it in a browser and use it. No account, no database server, no deploy step.

**Levels:** Foundation → Mortal → Scholar → Adept → Master → Transcendent → Supreme

## What it does

- Name field starts empty. Write your own name.
- Left side shows live rank and XP.
- Missions, exams, steps, and deadlines.
- XP: Easy 25 · Medium 60 · Hard 120 · Boss 250. XP is added only when a card is marked done.
- Rank and cards stay in that browser’s storage.

## Backup

- **Export JSON** downloads one file of your name, rank data, and cards.
- **Import JSON** reads that file back and replaces what is on screen.

Keep the file if you clear the browser or switch machines. Clearing site data deletes the in-browser copy.

## Not required

`supabase-schema.sql` and the old Next.js package notes are an earlier draft. They are not how this app runs.
