# Ombrello App README

L'app Umbrella è un'applicazione elegante e intuitiva progettata per fornire agli utenti previsioni meteo in tempo reale e suggerimenti intelligenti per aiutarli a rimanere preparati per qualsiasi condizione meteorologica. Che si tratti di una giornata soleggiata, di un pomeriggio piovoso o di una serata nevosa, l'app Umbrella ti ha coperto!

## Tabella dei contenuti

- [Caratteristiche](#features)
- [Installazione](#installation)
- [Utilizzo](#usage)
- [Tecnologie Usate](#technologies-used)
- [Contribuire](#contributing)

## Caratteristiche

- **Previsioni meteo in tempo reale:** Ottieni informazioni meteo aggiornate per la tua posizione attuale o per qualsiasi posizione tu scelga.
- **Previsioni orarie e giornaliere:** Visualizza le previsioni orarie e di 7 giorni per pianificare le tue attività in anticipo.
- **Smart Suggestions:** Ricevi raccomandazioni basate sul tempo, come portare un ombrello nelle giornate piovose o indossare la protezione solare nelle giornate di sole.
- **Avvisi personalizzabili:** Imposta avvisi personalizzati per specifiche condizioni meteorologiche in modo da non essere mai presi fuori controllo.
- **Mappa Interattiva:** Visualizza i modelli meteo e traccia le tempeste con mappe interattive.
- **Design minimalista:** Goditi un'interfaccia pulita e user-friendly che fornisce informazioni meteorologiche essenziali a colpo d'occhio.

## Installazione

1. Clona il repository: `git clone https://github.com/yourusername/umbrella-app.git`
2. Vai alla directory del progetto: `cd umbrella-app`
3. Installa dipendenze: `npm install`
4. Configura Chiavi Api:
   - Rinomina `.env.example` in `.env`
   - Ottieni chiavi API da [Weather API Provider](https://weatherapi.com) e [Map Service Provider](https://mapsapi.com)
   - Sostituisci `YOUR_WEATHER_API_KEY` e `YOUR_MAPS_API_KEY` nel file `.env` con le tue chiavi API.
5. Esegui l'app: `npm start`

## Utilizzo

1. Apri l'app Umbrella sul tuo dispositivo.
2. Consenti l'accesso alla posizione per un meteo locale accurato o inserisci manualmente una posizione.
3. Esplora il tempo attuale, le previsioni orarie e le prospettive settimanali.
4. Ricevi suggerimenti intelligenti in base alle condizioni meteorologiche.
5. Imposta avvisi personalizzati per scenari meteorologici specifici.
6. Interagisci con le mappe per visualizzare i modelli meteorologici e gli incidenti.

## Tecnologie Usate

- React: libreria Frontend per costruire interfacce utente.
- Redux: Gestione dello Stato per le applicazioni React.
- Axios: client HTTP basato sulla promessa per fare richieste API.
- Leaflet: libreria JavaScript per mappe interattive.
- Moduli CSS: organizzazione e incapsulamento del foglio di stile.

## Contribuire

I contributi sono benvenuti! Ecco come puoi essere coinvolto:

1. Fork il repository.
2. Crea un nuovo ramo per la tua funzionalità: `git checkout -b feature-new-feature`.
3. Fai le tue modifiche e commetterli: `git commit -m "Aggiungi nuova funzionalità"`.
4. Premere al ramo: `git push origin feature-new-feature`.
5. Crea una pull request nel dettaglio delle tue modifiche.
