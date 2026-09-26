# Quiz al Contrario — V4

Questa versione contiene **2520 record effettivi**: 12 categorie × 210 domande.

Per rendere il conteggio verificabile in qualsiasi editor:
- `quiz-al-contrario-2520-v4.jsonl` contiene **una domanda per riga** (2520 righe).
- `categories/` contiene 12 JSON + 12 JSONL da **210 domande ciascuno**.
- `QA-REPORT.txt` contiene i conteggi effettuati dopo la scrittura dei file.

Ogni record salva `realAnswer` (vera) e `gameAnswer` (quella da dire nel gioco).
Le alternative precedono sempre il quesito nella stringa `question`.
