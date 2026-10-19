# Miscela Facile

[English](README.md) · [Italiano](README.it.md)

**Un calcolatore semplice e offline per preparare la miscela benzina e olio su Android.**

Scegli quanta benzina vuoi utilizzare, inserisci la percentuale d'olio indicata nel manuale del motore e scopri quanto olio aggiungere nell'unità scelta.

## Funzioni

- Unità separate per benzina e olio: L, mL, galloni e once fluide USA o imperiali. Preset della lingua, scelta manuale memorizzata e ripristino automatico.

- Quantità rapide da **0,5 a 5 litri**, comprese le mezze misure.
- Quantità di benzina e percentuale d'olio personalizzate.
- Risultato immediato nell'unità scelta per l'olio.
- Cronologia locale degli ultimi **20 calcoli salvati**, riutilizzabili e cancellabili.
- Indicazioni di sicurezza prima del calcolo, incluso l'uso di benzina pulita.
- Tema chiaro **arancione**, caratteri morbidi e campi personalizzati coordinati.
- Lingua del dispositivo e selettore alfabetico con icona a forma di globo.
- Inglese come riserva quando manca una traduzione.
- Suono e piccola vibrazione dei pulsanti, secondo le impostazioni del telefono.
- Funzionamento offline, senza account e senza pubblicità.

## Scarica per Android

[Scarica Miscela Facile 1.5.0 APK](https://github.com/devfaxpro/miscela-facile/raw/refs/heads/main/downloads/Miscela-Facile-1.5.0.apk)

Versione **1.5.0** · codice versione **11** · pacchetto `it.miscelafacile.app`.

Apri il file APK scaricato sul telefono Android per installarlo. Se richiesto da Android, autorizza l'installazione dal browser o dal gestore file utilizzato. Questo download diretto è separato da Google Play.

[Impronta SHA-256](downloads/SHA256SUMS.txt)

La versione 1.5.0 aggiunge unità separate per benzina e olio, preset automatici e scelte manuali memorizzate. Le impostazioni locali con regione USA usano galloni e once fluide USA; le altre usano litri e millilitri. Puoi sempre cambiare le unità manualmente.

**Requisito minimo:** Android 8.0. Non è disponibile una versione iOS.

## Come si usa

1. Leggi le indicazioni di sicurezza.
2. Scegli la benzina dai pulsanti oppure inserisci una quantità personalizzata.
3. Imposta la percentuale d'olio richiesta dal tuo motore.
4. Leggi la quantità di olio da aggiungere nell'unità scelta.
5. Se vuoi, salva il calcolo nella cronologia.

**Esempio:** con 2,5 L di benzina e il 2% servono **50 mL di olio**.

```text
Olio in mL = litri di benzina × percentuale d'olio × 10
```

La quantità indicata è quella della benzina prima di aggiungere l'olio. Non esiste una percentuale valida per ogni motore: segui sempre le istruzioni del produttore.

## Sicurezza

Usa benzina pulita, senza acqua o sporco, e un contenitore pulito adatto al carburante. Lavora all'aperto, lontano da fiamme e sigarette. Rifornisci solo a motore spento e raffreddato.

**L'olio per la catena della motosega non è olio da miscela.** Usa il tipo d'olio e la percentuale prescritti per il tuo motore.

## Lingue

L'interfaccia comprende **78 dizionari di base**, preparati con assistenza automatica e ancora in attesa di revisione linguistica indipendente. I nuovi controlli delle unità includono testi in italiano, inglese, spagnolo, portoghese brasiliano, francese, tedesco, cinese semplificato, giapponese, coreano e russo. La copertura varia secondo la funzione; i messaggi non tradotti vengono mostrati in inglese. Non si tratta di una certificazione di traduzioni complete o revisionate.

Il progetto accoglie contributi per lingue di tutti i continenti: è un obiettivo, non una dichiarazione che tutte le lingue siano già disponibili o verificate. I nomi nativi rimangono visibili nel selettore per ritrovare facilmente la propria lingua dopo una scelta errata.

## Privacy

[Leggi l’informativa sulla privacy (italiano / inglese)](https://devfaxpro.github.io/miscela-facile/privacy.html). La versione 1.5.0 contiene anche una copia offline nell’app.

Impostazioni e cronologia restano sul dispositivo. L'app Android non richiede permessi, account o connessione a Internet.

## Sviluppo e contributi

Il progetto preparato usa JavaScript per l'interfaccia condivisa e un'app Android Java con WebView. Il pacchetto sorgenti comprende script di compilazione, test e istruzioni per contribuire alle traduzioni.

Sono benvenuti revisioni linguistiche, segnalazioni sull'accessibilità e problemi riproducibili. Indica versione dell'app, dispositivo e lingua selezionata, senza inserire password o dati personali.

I controlli automatici verificano calcoli, scelta della lingua, cronologia e layout su schermi piccoli. Non certificano le traduzioni e non sostituiscono le prove su un telefono Android.

## Licenza

Non è ancora stata adottata una licenza open source per l'applicazione. La licenza MIT è stata proposta, **non applicata**. Il carattere Nunito mantiene la propria licenza **SIL Open Font License 1.1**.
