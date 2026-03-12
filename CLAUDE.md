# Global Claude Code Instructions

---

## REGOLA 1 — GitHub Backup (tutti i progetti, sempre)

Per ogni progetto:
1. `git init` nella cartella del progetto
2. `gh repo create` (account: AlessioSerreli) — nome repo chiaro, senza overlap o duplicati
3. Struttura organizzata: ogni progetto ha la sua repo dedicata, cartelle interne ordinate per blocco/funzionalità
4. Commit ad ogni avanzamento significativo — messaggi descrittivi, imperativo, concisi
5. Push su GitHub dopo ogni commit — il remoto è sempre aggiornato

Git identity:
- Name: Alessio Serreli
- Email: aseeerreli@gmail.com
- GitHub account: AlessioSerreli (HTTPS via gh CLI)

**Mai saltare questo setup. Mai aspettare di essere ricordato.**

---

## REGOLA 2 — Memoria di Sessione (CLAUDE.md per ogni progetto)

All'inizio, durante e alla chiusura di ogni sessione:

1. **Apertura sessione**: leggere il `CLAUDE.md` nella root del progetto per recuperare il contesto completo
2. **Durante la sessione**: aggiornare `CLAUDE.md` del progetto ad ogni avanzamento importante
3. **Chiusura sessione**: quando l'utente dice "salva tutto" o simile, eseguire OBBLIGATORIAMENTE:
   - Aggiornare `CLAUDE.md` del progetto con: stato attuale, blocchi completati, prossimi step, decisioni prese, stack usato
   - Commit + push su GitHub
   - Confermare esplicitamente all'utente: "✓ CLAUDE.md aggiornato, ✓ push su GitHub completato"

Il `CLAUDE.md` di progetto deve contenere:
- Descrizione del progetto e obiettivo
- Stack tecnologico
- Struttura blocchi/fasi con stato (completato / in corso / da fare)
- Decisioni architetturali importanti
- Ultimo punto di avanzamento (dove ci siamo fermati)
- Prossimi step

**Questa regola ha priorità assoluta. Non chiudere mai una sessione senza aver completato questo passaggio quando richiesto.**

---

## Git & GitHub Workflow (dettaglio tecnico)

For every new project:
1. Run `git init` in the project folder
2. Create a GitHub repository via `gh repo create` (account: AlessioSerreli)
3. Set the remote origin and push an initial commit
4. Commit at meaningful milestones with clean, descriptive commit messages (imperative mood, concise subject line)
5. Push to GitHub so there is always a saved remote version

Git identity is already configured globally:
- Name: Alessio Serreli
- Email: aseeerreli@gmail.com
- GitHub account: AlessioSerreli (authenticated via gh CLI, HTTPS protocol)

Never skip this setup. Do not wait to be reminded.
