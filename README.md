
# Progetto - Dashboard - INFO 

**Il progetto consiste nella creazione di una dashboard interattiva che permetterà l'utilizzo di bot telegram e bot discord all'interno di un sito web con l'utilizzo di framework avanzati come: next.js e fastapi e tanto altro...**

## Tecnologie utilizzate

 **- Next.js**
 
 **- FastAPI**


## Layout

Il layout sarà inspirato a quello di Pterodactyl:
![](https://cdn.pterodactyl.io/site-assets/carousel/screenshot-3.png)questo perché è il più vicino possibile ad un bot manager-like dashboard, di conseguenza le parti del sito saranno divise da una sidebar laterale sinistra con un insieme di opzioni, le quali saranno suddivisi in sezioni come: Account, Servizi e Documentazione

 - Account: avrà dei pulsanti che permetteranno l'accesso ai propri dati personali in cui alla destra del sito web si generà una tab navigation + un container che permetterà la visione delle impostazioni. Quest'ultimo sarà l'unico responsabile per effettuare cambio password, cambio email e infine distruzione account (danger zone)
 - Servizi: avrà dei pulsanti che permetteranno l'accesso ai propri bot disponibili (e non). Un pulsante si chiamerà "Bots" che alla sua destra genererà un container che avrà una lista che sarà più o meno popolata. Nella lista nel caso di popolazione, sarà mostrato una cosa del genere:
	 - Nome server
	 - Package
	 - Status
	 - Azioni
    
premendo su uno dei bot che verrà mostrato dalla lista, ci farà accedere ad una pagina che mostrerà alla sua destra una console live-preview di cosa accade + metriche di uptime ed utilizzo di risorse (CPU Load, Memoria, Disco, Network Inbound e Network outbound) con al di sotto ulteriori grafici. Inoltre, vi saranno delle funzioni DEDICATE per il tipo di bot che è  stato messo online. Ciò significa che le pagine saranno dinamiche e ritorneranno dei pulsanti, testi, dati in base al tipo bot (Discord o Telegram).
	 
Nella sezione "Servizi" vi saranno ulteriori due pulsanti, di nome: **Impostazioni** e **Attività**. Quest'ultimi sono piuttosto auto-esplicativi.

Una sezione che avrà una maggiore importanza sarà **Database**, quest'ultimo permetterà la visualizzazione e manipolazione del database in tempo-reale, questo renderà il tutto più veloce all'utente finale la manipolazione di dati in caso di necessità o di controllo.

