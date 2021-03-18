# Linee guida

## Tesi

1. Template [Latex](https://www.overleaf.com/project/5ddfe508fea6d40001ef6d7d)
    - NB: è a carico del tesista verificare che il template sia allineato con le specifiche della consegna
    - E.g., link di riferimento per elaborato tesi https://corsi.unibo.it/magistrale/IngegneriaScienzeInformatiche/volume-pdf-e-deposito-online-dellelaborato
2. Consegna dei capitoli
    - Ogni capitolo va consegnato una sola volta, uno per volta
    - Prima di consegnarlo, metterlo "nel cassetto" 2-3 giorni e rileggerlo
    - Dopo avere ricevuto le correzioni di un capitolo, verificare se le correzioni possono essere propagate sugli altri
3. Linguaggio
    - Evitare sempre commenti non oggettivi/superficiali/informali (o sono supportati da citazioni o non si mettono). Ad esempio: banale, semplice, facile, difficile, molto, troppo, poco, impossibile
    - Concisione: Non scrivere frasi più lunghe di *due* righe
        - Esempio No: L'idea di traiettoria si delinea nell'abilità di catturare gli spostamenti di un oggetto
        - Esempio Sì: La definizione di traiettoria è: "testo quotato" [citazione]
    - **Evitare** l'abuso di **grassetto** e *corsivo*
4. Inglesismi
    - Se le tesi è in Italiano è bene scrivere in Italiano e limitare l'uso dell'inglese il più possibile (e.g., "Trajectory Mining" -> "Mining di traiettorie")
        - Ovviamente non tutto può essere tradotto in Italiano (e.g., clustering, mining, deploy, etc.)
    - Usa un termine inglese se questo si ripete ma spiegalo una sola volta.
    - Un acronimo in inglese rimane in inglese: GPS (Global Positioning System) e non si usa il plurale
    - La prima volta in assoluto che il termine compare scrivilo in corsivo. Esempio "I *layer* (livelli) di un GIS (*Geographic Information System*)"
5. Struttura
    - Convenzione nomi
        - Titolo: 
            - Prima lettera maiuscola in tutti i nomi, pronomi, aggettivi, verbi, avverbi
            - Tutto maiuscolo acronimi
            - In minuscolo articoli e congiungzioni 
        - Sezioni: tutto minuscolo eccetto la prima lettera e acronimi (e.g., "Questa è una sessione OLAP")
    - Abstract (sommario): singolo paragrafo tra 150 e 250 parole
    - Usare il package cleveref e `\Cref{}` (e non `\ref{}`) di Latex per fare riferimento a label di capitoli/sezioni/sottosezioni/immagini
    - Quando si descrive un argomento è bene averlo già introdotto. Se non indispensabili, evitare le *forword reference* (riferimento a capitoli/sezioni/sottosezioni che appaiono dopo essere referenziati)
    - Non creare sezioni con singola sottosezione
    - Evita di disperdere le informazioni: definizione, dettagli e implicazioni stanno nello stesso paragrafo
    - Esiste differenza tra `.` e `. a capo`: `. a capo` si usa per cambiare discorso
    - Non aggiungere come "Conclusioni e sviluppi futuri" i dettagli implementativi (e.g., "rimane da implementare il metodo `foo()`")
6. Citazioni e copia/incolla
    - Non citare Wikipedia (su https://scholar.google.it/ esiste un oceano di letteratura)
        - Se necessario, sfruttare Wikipedia per trovare le citazioni a paper/libri
    - Non copiare testi troppo lunghi, è meglio riassumerli ed elaborarli
    - Non copiare traduzioni troppo lunghe, è meglio riassumerle ed elaborarle
    - Esplicita la parte di testo copiata inserendola tra virgolette e aggiungi la citazione finale
        - Esempio: "Aggiungere inglesismi random non improva le vostre skills" [[Questa è una cit]](http://www.lercio.it/ricerca-aggiungere-inglesismi-random-non-improva-le-vostre-skills/)
    - La citazione precede il `.`: Testo citato [citazione]. (e non: Testo citato. [citazione]
7. Figure:
    - Se una figura è copiata/rielaborata indica la sorgente con apposita citazione
    - Utilizzare figure in formato vettoriale (.pdf, .svg)
    - In caso di screenshot, attenzione alle dimensioni (in MB) della figura
8. Punteggiatura, elenchi (e coerenza)
    - No punti nei titoli
    - Non `E'` ma `È` (È = Alt + 0200)  
    - In Latex si virgolette si fanno \`\`così'' (\` = Alt + 96) e non "così"
    - Elenchi puntati iniziano con Maiuscola, finiscono con `;` o con `.` (l'importante è usare la stessa convenzione). Di solito si usa `;` per terminare frasi di senso non compiuto, e `.` per terminare frasi di senso compiuto
    - No `...`, sì "etc." 

## Slides

1. Quanto dura la sessione? Verificare
    - Se la discussione dura 15 min, 10/12 minuti sono da dedicare alle slide (gli altri rimangono per eventuali domande)  
2. Non ci sono vincoli sull'utilizzo di Latex o Powerpoint
3. Circa una slide per minuto
4. Scaletta generica (e.g., per 10 minuti): 10 minuti -> ~10 slides
    - Motivazione (1/2 slide)
    - Collocazione rispetto alla related (1 slide)
    - Intuizione dell'approccio studiato (1 slide)
    - Esempio di funzionamento (1 slide)
    - Come funziona l'approccio (2 slide)
    - Test (1/2 slide)
    - Conclusioni e sviluppi futuri (1 slide)
5. Inviare le slide il prima possibile, cioè quando avete una bozza completa
