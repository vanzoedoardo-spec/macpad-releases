# PageCave

Qui si scarica **PageCave**, l'app per Mac che tiene insieme note, promemoria e riunioni registrate, tutto sul tuo
computer. Questa repository contiene solo le versioni pubblicate.

## Installazione

1. Scarica **[il file .dmg](https://github.com/vanzoedoardo-spec/macpad-releases/releases/latest/download/MacPad.dmg)**:
   il link porta sempre all'ultima versione. Scaricando PageCave accetti i [termini d'uso](TERMINI.md).
2. Apri il file e trascina PageCave nella cartella **Applicazioni**. Aperta direttamente dal `.dmg` l'app non può
   aggiornarsi.
3. Avviala. La prima volta macOS chiede una conferma: vedi [Primo avvio](#primo-avvio).

Cosa serve:

- macOS 12.3 o successivo;
- un Mac con Apple Silicon o con Intel (il file è uno solo);
- per la dettatura e la registrazione delle riunioni, macOS 26.

## Primo avvio

PageCave non ha ancora la firma Developer ID di Apple e non è notarizzata. Per questo, la prima volta che la apri,
macOS la blocca con un avviso che dice di non poterla verificare.

1. Nell'avviso premi **Fine**, non «Sposta nel Cestino».
2. Apri **Impostazioni di Sistema › Privacy e sicurezza**, scorri in fondo e premi **Apri comunque** accanto a
   PageCave. Conferma con la password o con Touch ID.
3. Da qui in poi si apre normalmente.

Se «Apri comunque» non c'è: compare per circa un'ora dopo il tentativo di apertura. Prova ad aprire di nuovo l'app e
torna in Privacy e sicurezza. Da macOS 15 il tasto destro › Apri non basta più.

Chi preferisce il Terminale può togliere il segno che macOS mette ai file scaricati:

```bash
xattr -dr com.apple.quarantine /Applications/PageCave.app
```

Su un Mac gestito dall'IT dell'azienda, «Apri comunque» può mancare del tutto: in quel caso chiedi all'IT di
consentire l'app.

## Aggiornamenti

PageCave si aggiorna da sola. Controlla all'avvio e ogni 4 ore; quando esce una versione nuova la scarica, ne verifica
la firma e, in fondo alla barra laterale, propone **Riavvia**. Se non riavvii, alla prossima apertura è già
aggiornata. Per controllare subito: Impostazioni › Informazioni › **Controlla ora**.

Le novità di ogni versione sono nelle [release](https://github.com/vanzoedoardo-spec/macpad-releases/releases).

### Se avevi MacPad++

PageCave è la stessa app con il nome nuovo, dalla 1.8.0. L'aggiornamento arriva da solo e tiene note, promemoria e
impostazioni. La cartella in Applicazioni resta `MacPad++.app`: va bene così, e l'avvio al login e gli assistenti AI
continuano a funzionare.

Se vuoi anche la cartella con il nome nuovo: esci con ⌘Q, sposta `MacPad++.app` nel Cestino e installa PageCave dal
`.dmg`. I dati restano. Poi, nelle Impostazioni, premi di nuovo «Aggiungi» per gli assistenti e spegni e riaccendi
l'avvio al login. Non tenere mai le due copie insieme.

## I tuoi dati

Note, promemoria e riunioni registrate restano solo sul tuo Mac, in
`~/Library/Application Support/it.archivagroup.macpad/`. Gli aggiornamenti non li toccano. Non c'è un account e non
c'è un server. I dettagli sono nell'[informativa privacy](PRIVACY.md).

Prima di registrare una riunione avvisa chi partecipa: rispettare le leggi sulle registrazioni spetta a chi registra,
come dicono i [termini d'uso](TERMINI.md).
