# CSCI E-12 Harvard Final Project Fall Semester 2026 by James Sweetsir

## 🚀 Project Structure

```text
src/
  data/
    monsters.json
    items.json
    skills.json
    quests.json
  pages/
    index.astro            ← the game
    monsters/[id].astro    ← one page per monster
    items/[id].astro       ← one page per item
    skills/[id].astro      ← one page per skill
  scripts/
    game.ts                ← combat, XP, save/load
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
