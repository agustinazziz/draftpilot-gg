# Screenshots for the landing page

Drop 4 PNGs here with these exact names. Until they exist, the page shows a
dashed placeholder box in each slot (no broken images).

| file | what to capture | shown on page |
|------|-----------------|---------------|
| `draft.png` | Draft tab with a recommendation on screen: the big pick name, the reason line (vs X · reason · WR%), and the "si la banean" fallbacks. | hero, top of page |
| `build.png` | The build panel expanded: item icons row, runes with icons, and the `lolalytics · … · situacionales por IA` source line. | "What it does" section |
| `teams.png` | The team panel (`#dteams` open) with both teams' champions sitting in their role columns. | "What it does" section |
| `plan.png` | The "por qué este pick" + "plan de partida" panels open (rationale + early/mid/late). | "How it works" section |

## How to take them

1. Open DraftPilot during (or just after) a real champ select so the champion
   portraits and names are real.
2. Windows: `Win + Shift + S`, drag a rectangle around just the app content
   (no title bar, no desktop). It copies to the clipboard.
3. Paste into Paint (or Photos) and **Save as PNG** with the name from the table.
4. Target width ~1100–1400 px. Keep all four a similar width so the page looks even.
5. Put the files in this folder and commit:
   ```
   git add img/*.png
   git commit -m "Add app screenshots"
   git push
   ```

No fixed height — the page scales each image to the column width.
