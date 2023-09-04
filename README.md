#  Disagio SMP: 68% completato
  Di seguito, tutte le modifiche effettuate/introdotte durante lo sviluppo del server e delle sue funzionalità:
  
### - GENNAIO 2022 -
- Creazione server e configurazione primi plugin

### - FEBBRAIO 2022 -
- Introduzione del plugin della cronologia modifiche ai blocchi [ADMIN]

### - MARZO 2022 -
- Creazione sistema Anti-Xray

### - APRILE 2022 -
- Introduzione del plugin delle abilità (/skills)
- Creazione del sistema di creazione di case, warp e del randomtp (/home, /warp, /tpr) 

### - MAGGIO 2022 -
- Creazione sistema AFK (/afk)
- Creazione del MOTD del server personalizzato
- Creazione meccanica del "fuoco" nei biomi caldi
- Creazione del sistema dei punti e della reputazione (/punti e /rank)
- Creazione dei messaggi di ingresso e uscita dal server personalizzati
- Creazione degli annunci
- Creazione della visualizzazione del ping personale o altrui (/ping)
- Creazione del cestino (/trash)
- Creazione colori chat in base al giocatore che scrive in chat
- Creazione della crafting table rapida (/crafting)
- Creazione della visualizzazione a schermo della vita dei mob con click destro
- Creazione delle action bar per AFK
- Creazione del sistema di segnalazione bug (/bug)
- Personalizzazione visiva e funzionale del comando /msg 

### - GIUGNO 2022 -
- Creazione comando per visualizzare l'orario del mondo di gioco (/time)

### - LUGLIO 2022 -
- Introduzione delle medaglie (/medals)
- Creazione GUI selezione messaggi di ingresso e uscita personalizzati (/chatmessage o /chatm)

### - AGOSTO 2022 -
- Pausa.

### - SETTEMBRE 2022 -
- Pausa.

### - OTTOBRE 2022 -
- Correzione di bug e migliorie varie alle prestazioni

### - NOVEMBRE 2022 -
- Risoluzione dei problemi e migliorie delle prestazioni

### - DICEMBRE 2022 -
- Creazione sistema degli obiettivi a livelli e creazione delle prime GUI dei "blocchi da costruzione"
- Il blocco di ardesia rinforzata, quando distrutto, dropperà se stesso (in Minecraft Vanilla, alla distruzione, questo evento non succede)
- Creazione del profilo SMP e creazione della GUI 

### - GENNAIO 2023 -
- Aggiunta una stella del Nether cliccabile (che apre la GUI del profilo SMP) la quale non è possibile spostare o droppare (slot 8 del giocatore)
- Bacche luminose che danno luminescenza al giocatore per un periodo limitato di tempo una volta consumate
- Creazione delle impostazioni del giocatore con RIempimento GUI, Selezione messaggi e Selezione del sesso
- Creazione delle emoji in chat (/emoji help)
- Modifiche a varie funzioni
- Creazione del sistema di messaggi di aiuto per il server in chat
- Ordinamento di tutte le funzioni del server e riorganizzazione dei file
- Creazione del comando /sleep
- Ri-creazione sistema Anti-Xray
- Ottimizzazione dei vari sistemi e bug fixes 

### - FEBBRAIO 2023 -
- Proseguimento del sistema Anti-Xray
- Creazione e completamento dei soprannomi (comando /nick)
- Creazione della sezione della Gestione del Server con scorciatoie annesse
- Ri-creazione e ottimizzazione del sistema dei punti e delle reputazioni
- Aggiunta dei Tab Completer ad alcuni comandi
- Aggiunta della notifica dell'inventario pieno
- Aggiunta della difficoltà "Hardcore" con titolo annesso
- Aggiunto il titolo che avvisa della difficoltà aumentata dei mob durante la notte
- Modificato il prefisso dei messaggi: da "INFO" a "SMP"
- Ottimizzati "GodMode", "FlyMode" e "GamemodeCommands" con alcune migliorie delle prestazioni

### - MARZO 2023 -
- Aggiunto il comando interno "/nothing" all'interno dello script dell'Anti-Xray
- Modifiche minori ad alcuni script
- Ri-creazione delle medaglie con 15 nuove sfide da compiere per ottenerle
- Ricreata la GUI del Profilo SMP
- Ricreato e rivisitato il sistema dell'AFK con l'inserimento di messaggi personalizzati basati sul genere del giocatore e con vari bugfixes
- Introdotta la possibilità di tornare al punto precedente dopo aver eseguito il comando /sleep al risveglio (se la medaglia "Suicida" è stata sbloccata!)
- Adesso il server controllerà se ci sono soprannomi attivi con la frequenza di un secondo
- Aggiustata l'assegnazione dei punti, dei ruoli e del prefisso del nome per quanto riguarda il primo accesso al server
- Unificato e ottimizzato lo script del PvP
- Da adesso, i danni provocati dall'Ender Pearl non saranno più controllati dal PvP (ad esempio, se il PvP è disabilitato, il giocatore prenderà comunque danno)
- Rimossa la GUI della selezione del sesso in gioco
- Disabilitato il comando /tell: adesso quando si prova ad eseguirlo il server consiglierà al giocatore di utilizzare il comando /msg
- Aggiunto il comando /wiki, che permette di ottenere il link della Wiki della Disagio SMP, così da poterla consultare in modo facile e veloce
- Aggiunta la Tablist e la Scoreboard (con comando /sb che consente di attivarla o disattivarla)
- Rimosse le action bar dal file "ActionBar" e riallocate nei rispettivi script (ad esempio, l'action bar della FlyMode è stata spostata nel file "FlyMode")
- Ottimizzazione di tutti i file

### - APRILE 2023 -
- Ri-creazione dei pacchetti di messaggi di ingresso e uscita dal server con aggiunta di alcuni pacchetti già selezionabili dal giocatore
- Modifica di alcune parti del codice del contatore delle sessioni di gioco
- Modifica ad una stringa del codice per le impostazioni del giocatore

### - MAGGIO 2023 -
- Correzioni delle prime GUI del sistema degli obiettivi
- Miglioramento delle prestazioni

### - GIUGNO 2023 -
- Completati gli eventi "on break", "on place" e "on pickup" della categoria "Blocchi da costruzione"
- Completate le GUI rimanenti dei blocchi da costruzione
- Creazione e ottimizzazione della Tablist e della Scoreboard
- Creazione dei testi animati leggibili sulla Tablist e sulla Scoreboard
- Aggiunto il sistema della rimozione automatica dei drop dopo un certo lasso di tempo
- Risolto un problema del sistema dei soprannomi, il quale poteva assegnare un soprannome anche ai giocatori offline
- Introdotti il sistema di rimborso dei materiali (valido soltanto per barche, armi, armature e attrezzi - per le barche verranno restituiti i blocchi del rispettivo tipo di legno, per armi, armature e attrezzi verranno restituiti dalla pietra alla netherite -)
- Introdotti due nuovi crafting: il totem dell'immortalità e la mela d'oro incantata
- Da adesso, i giocatori con un soprannome, quando scriveranno in chat, avranno un * prima del soprannome
- Aggiunto il comando "/feedback" nello stesso script del comando "/bug"
- Ottimizzazione delle prestazioni e rimozioni dei bug

### - LUGLIO 2023 -
- Aggiunte le stagioni.
- Sostituito "Livello di luce" con "Stagione" nella Scoreboard.

### - AGOSTO 2023 -
- Aggiunte le notifiche personali nelle impostazioni del giocatore.