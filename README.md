# 🤖 Esercitazione - L’account giusto per quel compito

**L’account giusto per quel compito** è un’esercitazione interattiva per capire quando utilizzare un assistente IA, quando adattare la richiesta e quando fermarsi o chiedere autorizzazione.

Il punto centrale non è il marchio dello strumento né il tipo di abbonamento, ma il **governo dell’uso**: chi governa lo strumento, quali dati sono coinvolti e quali funzioni sono effettivamente autorizzate.

## 🎯 A chi è rivolto

L’esercitazione è pensata per dipendenti della Pubblica Amministrazione e per percorsi formativi sull’uso consapevole, sicuro e governato dell’IA generativa.

È particolarmente utile per:

- funzionari ed esecutori che utilizzano o valutano strumenti di IA;
- direttori e dirigenti coinvolti nella governance digitale;
- referenti ICT, privacy, sicurezza e trasformazione digitale;
- formatori che vogliono proporre un laboratorio breve e operativo.

## 🕹️ Come funziona

L’esercitazione è individuale e dura circa **8–10 minuti**.

1. **Leggi il caso**: osserva account, tipo di documento, funzione richiesta e dati coinvolti.
2. **Prendi posizione** scegliendo una delle tre opzioni:
   - `PROCEDO`
   - `ADATTO`
   - `MI FERMO / CHIEDO`
3. **Motiva la scelta**, in modo facoltativo ma consigliato.
4. **Confronta la risposta** con il feedback operativo.
5. **Consulta il riepilogo finale**, scaricabile in TXT o stampabile in PDF.

L’app non richiede login, non invia dati a un server e non conserva le risposte tra le sessioni.

## 🧩 I tre casi

| Caso | Contesto | Decisione attesa |
|---|---|---|
| **A — L’avviso già pubblicato** | Sintesi di un avviso pubblico già online, con account di lavoro autorizzato e verifica umana prima della pubblicazione. | `PROCEDO` |
| **B — La pratica con dati sanitari** | Tentativo di caricare una pratica con dati sanitari e identificativi in un chatbot privato non autorizzato. | `MI FERMO / CHIEDO` |
| **C — La casella email collegata all’IA** | Nuovo connettore in grado di leggere la casella email, non incluso nelle autorizzazioni già concesse all’assistente istituzionale. | `MI FERMO / CHIEDO` |

## ✅ Le tre decisioni possibili

| Scelta | Quando applicarla |
|---|---|
| **PROCEDO** | Strumento, compito, funzione e dati rientrano nelle condizioni autorizzate. |
| **ADATTO** | È possibile ridurre il compito o eliminare informazioni non necessarie, restando nel perimetro autorizzato. |
| **MI FERMO / CHIEDO** | Manca un’autorizzazione, esiste un’incompatibilità oppure bisogna coinvolgere un referente. |

Una regola sempre valida: **un account istituzionale o “Enterprise” non autorizza automaticamente qualsiasi funzione o contenuto**.

## 🧠 Criterio guida

Prima di usare un assistente IA, porsi quattro domande:

- Lo strumento è autorizzato?
- I dati sono consentiti?
- Anche quella specifica funzione è compresa nell’autorizzazione?
- Chi devo coinvolgere se qualcosa non è chiaro?

Il punteggio finale è un **feedback formativo**, non una certificazione di competenze.

## 💻 Come usare l’app

Il progetto è una **web app statica**, senza librerie esterne, database, analytics o connessioni a servizi esterni.

### Aprire l’esercitazione

1. Scarica o clona il repository.
2. Apri `index.html` con un browser moderno.
3. Avvia l’esercitazione e completa i tre casi.

In alternativa, se il repository è pubblicato con GitHub Pages, basta condividere il link della pagina.

### Clonare il repository

```bash
git clone https://github.com/gigicogo/AI-L-account-giusto-per-quel-compito.git
cd AI-L-account-giusto-per-quel-compito
```

## 🛠️ Aggiornare i casi

I casi didattici sono definiti nell’array JavaScript `cases` dentro `index.html`.

Per ogni caso puoi modificare:

- `title`: titolo del caso;
- `sub`: ufficio e attività;
- `scenario`: situazione da valutare;
- `correct`: decisione attesa;
- `explanation`: spiegazione operativa;
- `checks`: punti di controllo da considerare.

Non è necessaria alcuna compilazione o configurazione aggiuntiva.

## 🔐 Sicurezza e privacy

L’app funziona interamente nel browser.

- Non memorizza né invia le risposte a server esterni.
- Non conserva i dati tra le sessioni.
- Il riepilogo resta nel browser fino alla chiusura della pagina.
- Gli scenari sono fittizi.

Durante il laboratorio, utilizzare soltanto esempi inventati. Non inserire dati personali, pratiche reali o informazioni riservate nelle motivazioni.

## 🖨️ Riepilogo e debrief

Al termine dell’esercitazione è possibile:

- visualizzare il punteggio e l’esito di ciascun caso;
- confrontare la scelta effettuata con quella didatticamente attesa;
- rileggere la propria motivazione;
- scaricare un riepilogo in `.txt`;
- stampare o salvare il risultato in PDF;
- ripetere l’esercitazione.

## 🧪 Possibili evoluzioni

- Aggiunta di nuovi casi su ricerca, traduzione, bozze, analisi documentale e interazione con i cittadini.
- Versione per gruppi, con confronto delle scelte e discussione guidata.
- Esportazione del riepilogo in Markdown o PDF.
- Modalità docente con proiezione dei casi e debrief collettivo.
- Versione in inglese.
- Integrazione con checklist organizzative e materiali normativi.

## 🤝 Contribuire

Sono benvenuti suggerimenti su nuovi scenari, formulazioni più efficaci, miglioramenti di accessibilità e materiali di supporto.

1. Apri una Issue per proporre una modifica.
2. Oppure apri una Pull Request con un nuovo caso o una correzione.
3. Mantieni la struttura dei casi: scenario, decisione attesa, spiegazione e punti di controllo.

---

## Contesto del progetto

L’app nasce come esercitazione nel percorso operativo **“L’IA nella Pubblica Amministrazione — Percorso operativo per l’uso consapevole, sicuro e governato dell’IA generativa”** (20 ore: percorso base per funzionari ed esecutori + modulo governance per direttori e dirigenti).

---

## 📄 Licenza e riuso

Puoi usare, copiare, modificare e condividere questo progetto, anche per attività formative, professionali e commerciali, senza chiedere un’autorizzazione preventiva.

Salvo diversa indicazione, il codice è distribuito con licenza [MIT](https://opensource.org/license/mit), mentre i testi e i materiali didattici sono distribuiti con licenza [Creative Commons Attribuzione 4.0 Internazionale](https://creativecommons.org/licenses/by/4.0/deed.it).

Nel riuso, conserva gli avvisi previsti dalla licenza MIT; per testi e materiali didattici, cita **Gianluigi Cogo**, inserisci un collegamento al progetto originale e alla licenza e indica eventuali modifiche. Gli eventuali materiali di terzi mantengono le rispettive licenze.

## 👤 Autore e contesto

**Gianluigi Cogo** — Content creator e technical writer interessato ad AI generativa, automazioni, viaggi e strumenti digitali. Consulente e docente sui temi dell’IA generativa, dell’innovazione e della comunicazione.

- 📮 Newsletter: [gigicogo.substack.com](https://gigicogo.substack.com)
- 📝 Blog: [medium.com/webeconoscenza](https://medium.com/webeconoscenza)
- ▶️ YouTube: [youtube.com/@gigicogo](https://www.youtube.com/@gigicogo)
- 💼 LinkedIn: [linkedin.com/in/gigicogo](https://it.linkedin.com/in/gigicogo)
