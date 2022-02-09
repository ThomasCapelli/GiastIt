
# GiastIt
Una semplice applicazione per tenere traccia delle ricette e anche consigliarne di nuove sulla base dei tuoi ingredienti.
Progetto da meno di un mese/uomo.


## FUNZIONALITA'


### MACRO - FUNZIONALITA'

- Aggiungere/Eliminare ricetta
- Importare ricetta da internet (es. GialloZafferano)
- Ricette consigliate sulla base di piatti consumati in precedenza o randomicamente presi sempre da internet
- Gestione degli ingredienti (lista di ingredienti, lista della spesa, ingredienti compresi in una ricetta)

- (OPTIONAL 1) Combinare lista di ingredienti per trovare una ricetta ottenibile tramite essi 
- (OPTIONAL 2) Creare (pianificare) una dieta come composizione di ricette 

### MICRO - FUNZIONALITA'

- Gestione real-time della ricetta
	* spunta dei passaggi
	* apertura timer (non per forza automatico)
	* cambiare numero di persone per modificare le dosi
- Sezione ingredienti (aggiunta/rimozione di un ingrediente, creazione lista della spesa)
- Accesso con Google o Login in generale (RICHIEDE DATABASE SU UN SERVER)
- Funzionalità Timer (Multi-thread)
- Parser delle pagine web delle ricette
- Separazione tra ricetta con preparazione (insieme di passi per fare il piatto) e ricetta solo contenente gli ingredienti (senza alcuna indicazione per la preparazione)
- Sistema di consiglio ricette (sceglie in base ad un insieme di fattori: es. ultima volta che è stata consumata, dieta, ingredienti sulla lista della spesa ecc...)

- (OPTIONAL 1) Sistema di combinazione ricette
- (OPTIONAL 2) Sistema di scelta giorni, associazione tra ricetta e giorno.

### INTERFACCE (GRAFICHE) DELL'APPLICAZIONE

- Schermata di login (con google e non)
- Home (ricetta del giorno consigliata e vari menù)
- Lista ricette
- Aggiunta di una ricetta
- Sistema di ricerca ricetta (anche GLOBALE, ovvero su internet)
- Interfaccia del Timer
- Sistema ricetta real time : avvio ricetta, spunte dei passaggi della ricetta
- Pagina ricetta singola
- Lista ingredienti (con pop-up per inserire un nuovo ingrediente)
- Pagina lista della spesa
- (OPTIONAL 1) Pagina per combinare ricette
- (OPTIONAL 2) Pagina creazione della dieta
- (OPTIONAL 2) Pagina gestione della dieta
- (OPTIONAL 2) Pagina associazione giorno/ricetta
