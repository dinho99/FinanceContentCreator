# Content Creation Crew

## Descrizione

Questo progetto utilizza la libreria **CrewAI** per automatizzare la creazione di contenuti, combinando diversi agenti AI specializzati. Il sistema è progettato per monitorare le notizie di mercato, analizzare i dati finanziari, generare contenuti e garantire la qualità del risultato finale.

## Struttura del Progetto

- **main.py**: File principale che avvia l'esecuzione della Crew AI e gestisce l'intero flusso di lavoro.
- **helper.py**: Contiene funzioni di supporto, come il caricamento delle variabili di ambiente.
- **requirements.txt**: Elenco delle dipendenze richieste per eseguire il progetto.
- **config/agents.yaml**: Configurazione degli agenti AI utilizzati nel progetto.
- **config/tasks.yaml**: Configurazione dei task assegnati agli agenti.

## Prerequisiti

- Python 3.9 o superiore
- Ambiente virtuale (opzionale, ma consigliato)

## Installazione

1. Clonare il repository:
   ```sh
   git clone <repository_url>
   cd <repository_directory>
   ```
2. Creare ed attivare un ambiente virtuale (opzionale, ma consigliato):
   ```sh
   python -m venv venv
   source venv/bin/activate  # Su macOS/Linux
   venv\Scripts\activate  # Su Windows
   ```
3. Installare le dipendenze:
   ```sh
   pip install -r requirements.txt
   ```
4. Creare un file `.env` nella root del progetto e inserire le credenziali API necessarie:
   ```env
   ANTHROPIC_API_KEY=your_api_key_here
   ```

## Esecuzione

Per avviare il sistema:

```sh
python main.py
```

Il sistema analizzerà le notizie di mercato e genererà contenuti strutturati, inclusi post per i social media.

## Struttura degli Agenti e Task

Il progetto utilizza diversi agenti AI con specifici compiti:

- **Market News Monitor Agent**: Monitora le notizie finanziarie.
- **Data Analyst Agent**: Analizza i dati di mercato.
- **Content Creator Agent**: Genera contenuti basati sui dati raccolti.
- **Quality Assurance Agent**: Verifica la qualità dei contenuti prodotti.

I task assegnati agli agenti includono:

1. Monitoraggio delle notizie finanziarie.
2. Analisi dei dati di mercato.
3. Creazione di contenuti (articoli e post per social media).
4. Controllo qualità del contenuto generato.

## Output del Sistema

Il risultato dell'elaborazione include:

- Un **articolo** formattato in Markdown.
- Una serie di **post per social media** pronti per essere pubblicati.

## Contributi

Se vuoi contribuire al progetto:

1. Fai un fork del repository.
2. Crea un nuovo branch per le modifiche.
3. Manda una pull request con le migliorie proposte.

## Licenza

Questo progetto è distribuito sotto la licenza MIT. Per maggiori dettagli, consulta il file LICENSE.

---

Questo README fornisce tutte le informazioni necessarie per comprendere e avviare il progetto. Se hai bisogno di ulteriori dettagli o personalizzazioni, fammelo sapere!

