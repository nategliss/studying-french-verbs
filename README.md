# French Verb Flashcards

A systematic approach to mastering French verb conjugations and usage at B1-B2 level.

## Files

- **verbs_todo.txt** - Simple list of infinitives to create cards for (one per line)
- **verbs_master.txt** - Complete tab-delimited deck ready for Anki import

## Workflow

### Adding new verbs
1. Edit `verbs_todo.txt` from any device (phone, computer, GitHub web)
2. Add infinitives one per line (include prepositions: "s'occuper de")
3. Commit and push

### Generating flashcards
1. Pull latest changes: `git pull`
2. Share new verbs from `verbs_todo.txt` with Claude
3. Claude generates tab-delimited entries for new verbs only
4. Append to `verbs_master.txt`
5. Commit and push

### Importing to Anki
1. **File** → **Import** in Anki
2. Select `verbs_master.txt`
3. Set delimiter to **Tab**
4. Set Note Type to **French – Verb (Principal Parts)**
5. Import (Anki automatically skips duplicates based on Infinitif field)

## Card Template

Each card includes 10 fields:

**Front (for review):**
1. Infinitif
2. Présent_3sg
3. Imparfait_3sg
4. Conditionnel_3sg
5. Subjonctif_3sg
6. Participe_passé
7. Participe_présent

**Back (for context and usage):**
8. Sens_principal
9. Sens_secondaires / Constructions
10. Notes_registre

## Field Conventions

- **Infinitif**: Include prepositions (e.g., "se méfier de", "tenir à")
- **3sg forms**: Use "il/elle" forms for consistency
- **Sens_secondaires**: Use bullets (•) to separate example sentences
- **Notes_registre**: Mark as courant, familier, soutenu, or littéraire

## Mobile Editing Options

- GitHub mobile app
- github.com in browser
- Working Copy (iOS)
- Obsidian with Git plugin

## Note Type Setup in Anki

The Anki note type "French – Verb (Principal Parts)" includes custom HTML/CSS templates for optimal visual hierarchy. See card templates in Anki for details.

---

*Last updated: February 2026*
