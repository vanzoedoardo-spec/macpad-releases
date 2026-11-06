# Informativa privacy di PageCave

Ultimo aggiornamento: 6 novembre 2026

## In breve

Lo sviluppatore di PageCave (Edoardo Vanzo, a titolo personale) non raccoglie, non riceve e non conserva dati
personali: né tuoi, né delle persone che registri. PageCave non ha account, server, statistiche d'uso o pubblicità.
Tutto quello che scrivi o registri resta sul tuo Mac.

## Cosa resta sul tuo Mac

Nella cartella `~/Library/Application Support/it.archivagroup.macpad/`:

- note, promemoria e impostazioni, in un database SQLite;
- l'audio delle riunioni registrate, nella sottocartella `recordings`, e la loro trascrizione, dentro la nota.

Eliminando una nota registrata si elimina anche il suo audio. Disinstallare l'app non cancella questa cartella: se
vuoi togliere tutto, cancellala tu.

## Microfono e riconoscimento vocale

Dettatura e trascrizione delle riunioni usano il riconoscimento vocale di Apple, che lavora sul Mac: l'audio non
viene mandato allo sviluppatore. La prima volta può servire scaricare da Apple il modello della lingua; quello scambio
avviene tra il Mac e Apple, secondo l'informativa di Apple. I permessi per microfono, riconoscimento vocale e
notifiche li chiede macOS, e li togli quando vuoi in Impostazioni di Sistema › Privacy e sicurezza.

## Le connessioni che fa l'app

- **Aggiornamenti.** All'avvio e ogni 4 ore PageCave chiede a GitHub se c'è una versione nuova e, se c'è, la scarica.
  Come per ogni download, GitHub vede l'indirizzo IP e i dati tecnici della richiesta e li tratta secondo la propria
  informativa. Lo sviluppatore vede solo quante volte sono stati scaricati i file delle versioni.
- **Assistenti AI.** Solo se li colleghi e accendi l'accesso nelle Impostazioni, Claude Desktop, Claude Code o Codex
  leggono note e promemoria quando chiedi loro qualcosa, e li mandano al loro fornitore (Anthropic, OpenAI), che li
  tratta secondo la propria informativa. Se le note contengono dati di altre persone, per esempio la trascrizione di
  una riunione di lavoro, assicurati di poterli condividere con quel servizio.

Non ci sono altre connessioni.

## Le persone che registri

Lo sviluppatore non è titolare del trattamento delle registrazioni e delle trascrizioni: lo è chi registra (o, se
registra per lavoro, la sua organizzazione). Informare le persone registrate e rispondere alle loro richieste, per
esempio di cancellazione, spetta a chi registra. Vedi anche i [termini d'uso](TERMINI.md).

## Modifiche e contatti

Se l'app cambierà il modo in cui tratta i dati, questa pagina verrà aggiornata prima, con la data in alto. Per
domande apri una segnalazione nella [pagina Issues](https://github.com/vanzoedoardo-spec/macpad-releases/issues) di
questa repository.
