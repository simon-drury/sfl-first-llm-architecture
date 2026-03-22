---

**Lingua / Language / Langue / Idioma / Idioma:**
[EN](README.md) | [FR](README.fr.md) | [ES](README.es.md) | [IT](README.it.md) | [PT](README.pt.md)

> *Versioni multilingui prodotte con [sfl-translation-agent](https://github.com/simon-drury/sfl-translation-agent) — pipeline di traduzione SFL-first dello stesso autore.*

---

# sfl-architettura-llm-prima

**© 2026 Simon Drury (sjd_datascapes)**

---

## Cos'è

Una specifica pubblica e datata di un'architettura LLM basata sulla Linguistica Funzionale Sistemica (LFS).

L'affermazione centrale: la linguistica funzionale sistemica — e in particolare le metafunzioni ideazionale, interpersonale e testuale — costituisce il quadro corretto per la progettazione di LLM, l'ingegneria dei prompt e l'orchestrazione degli agenti. Non si tratta di applicare la LFS *sopra* un LLM. Si tratta della LFS come *sistema operativo* dell'LLM.

---

## Il problema con la progettazione attuale degli LLM

Gli LLM attuali e i loro prompt di sistema sono:

- ideazionalmente sottospecificati (nessuna architettura di campo/dominio basata su principi)
- interpersonalmente incoerenti (nessuna modellazione basata su principi di ruolo, postura o tenor)
- testualmente ad hoc (nessuna struttura basata su principi di genere, registro o flusso informativo)

Risultato: gli utenti dedicano un tempo considerevole a correggere difetti a livello di sistema che non avrebbero mai dovuto essere incorporati.

---

## L'architettura LFS-first

### 1. Il registro come parametro di progettazione primario

Ogni interazione con un LLM è governata da un contesto di situazione. Le tre variabili di registro — campo, tenor, modo — devono essere codificate esplicitamente come parametri a livello di sistema, non inferite in modo stocastico.

- **Campo**: Quale dominio di attività è in gioco? Quale struttura di conoscenza lo governa?
- **Tenor**: Qual è la relazione di ruolo? Quali strutture di obbligo e di affetto si applicano?
- **Modo**: Qual è il canale retorico? Quale densità e flusso informativo sono attesi?

### 2. Le metafunzioni come sistema di tipizzazione degli agenti

Le tre metafunzioni non sono semplici categorie analitiche. In un'architettura LFS-first, diventano ruoli funzionali per agenti e sottoprocessi:

- **Agente ideazionale**: gestisce la conoscenza del dominio, la construalizzazione esperienziale, le relazioni logiche
- **Agente interpersonale**: gestisce la postura, la valutazione, l'obbligo, la modalità, le relazioni di ruolo
- **Agente testuale**: gestisce la coesione, la struttura informativa, il sequenziamento dei generi, la progressione tematica

### 3. Il genere come specifica di output

L'output non è «una risposta». È un'istanza di genere — un processo sociale a stadi orientato a un obiettivo. Il genere deve essere specificato esplicitamente prima della generazione, non inferito dalle caratteristiche superficiali del prompt.

### 4. Ingegneria dei prompt LFS-first

I prompt non sono istruzioni in linguaggio naturale. Sono operatori meta-testuali su uno spazio funzionale sistemico. Un prompt LFS-first ben formato specifica:

- il registro del testo target
- la struttura di genere attesa
- la ponderazione metafunzionale richiesta
- i parametri di valutazione e modalità

---

## Implementazioni

I seguenti repository implementano aspetti di questa architettura:

- [systemic_func_context-wrapper](https://github.com/simon-drury/systemic_func_context-wrapper) — wrapper di istruzione LFS per i prompt
- [sfl-translation-agent](https://github.com/simon-drury/sfl-translation-agent) — agente di traduzione multilingue basato su LFS
- [browser_bridge_-sfl-playground-extension_sjd_datascapes](https://github.com/simon-drury/browser_bridge_-sfl-playground-extension_sjd_datascapes) — analisi LLM multi-modello LFS-first
- [numerai-sfl-pipeline](https://github.com/simon-drury/numerai-sfl-pipeline) — pipeline multi-agente informata da LFS

---

## Licenza

Questa specifica è liberamente utilizzabile per uso personale, accademico e open source non commerciale.
Qualsiasi uso commerciale (che generi ricavi diretti o indiretti) richiede una licenza separata dall'autore.

Si prega di contattare l'autore se è previsto un uso commerciale. Le condizioni di licenza sono aperte alla discussione.

**Contatto**: simondrury2010@gmail.com | [LinkedIn](https://www.linkedin.com/in/simon-drury-60b881293)

---

*Prima pubblicazione: marzo 2026. Datato su GitHub come anteriorità.*
