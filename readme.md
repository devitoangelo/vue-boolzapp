 # Milestone 1
 - ● Replica della grafica con la possibilità di avere messaggi scritti dall’utente (verdi) e
    dall’interlocutore (bianco) assegnando due classi CSS diverse
     - stilizzare in css  le due classi diverse una colore bianco e l'altra verde
 - ● Visualizzazione dinamica della lista contatti: tramite la direttiva v-for, visualizzare
    nome e immagine di ogni contatto
     - aggiungere un ciclo v-for sul container-list in modo tale da ciclare tutti i contatti creati con un array di oggeti 

     
 # Milestone 2
 - ● Visualizzazione dinamica dei messaggi: tramite la direttiva v-for, visualizzare tutti i
    messaggi relativi al contatto attivo all’interno del pannello della conversazione
     - creare un secondo array dove troviamo i messaggi della chat e li facciamo ciclare con un ciclo v-for e gli inseriamo per ogni chat 
 - ● Click sul contatto mostra la conversazione del contatto cliccato
      - con @click sul contatto apriamo la sua chat 
 # Milestone 3
 - ● Aggiunta di un messaggio: l’utente scrive un testo nella parte bassa e digitando
    “enter” il testo viene aggiunto al thread sopra, come messaggio verde
     - inseriamo un v-model in modo tale da inserire il testo nella chat e grazie al tasto enter inviare il messaggio e pulire la stringa di testo dove scrivere 
 - ● Risposta dall’interlocutore: ad ogni inserimento di un messaggio, l’utente riceverà
    un “ok” come risposta, che apparirà dopo 1 secondo
    - impostiamo una risposta automatica all'invio del messaggio l'interlocutore scriverà ok (cou un intervallo di 1 secondo)
 # Milestone 4
 - ● Ricerca utenti: scrivendo qualcosa nell’input a sinistra, vengono visualizzati solo i
    contatti il cui nome contiene le lettere inserite (es, Marco, Matteo Martina -> Scrivo
    “mar” rimangono solo Marco e Martina)
     - inseriamo un v-model all'input del search 
 # Milestone 5 - opzionale
 - ● Cancella messaggio: cliccando sul messaggio appare un menu a tendina che
    permette di cancellare il messaggio selezionato
 - ● Visualizzazione ora e ultimo messaggio inviato/ricevuto nella lista dei contatti


  
 # Consigli utili:
 - ● Si possono trascurare le scrollbar verticali, sia nel pannello dei messaggi, che nella
    lista dei contatti
 - ● I pulsanti e le icone possono non funzionare (a parte l’invio del messaggio)
 - ● Per gestire le date, può essere utile la libreria Luxon
 - ● La struttura dell’array dei contatti potrebbe avere questa forma: