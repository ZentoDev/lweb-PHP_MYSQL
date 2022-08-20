   # Esercizio PHP-MYSQL    

Svolto da: Giuseppe D'Alia, 1711488

Estensione del precedente esercizio xhtml-css.

Ho aggiunto una sezione per la gestione delle prenotazioni di visite all'interno di posti dell'organizzazione. La base di dati è composta da due tabelle: una contiene i dati degli utenti, neccessaria per il login e l'altra contenente i dati delle prenotazioni.
Dal sito ogni utente può aggiungere, eliminare o visualizzare le proprie prenotazioni. 

Per default connection.php e install.php accedono ad un database locale con un utente "root" senza password. È possibile modificare le credenziali di accesso sovrascrivendo i valori nelle variabili $DB_user e $DB_pass presenti all'interno dei due file.

Nuove pagine:
- prenotazione.php consente l'aggiunta di nuove prenotazioni.
- disdici.php consente l'eliminazione delle prenotazioni fatte dall'utente fino a quel momento.
- visualizzavisite.php consente di visualizzare le prenotazioni attive.
- login.php permette l'accesso agli utenti.
- logout.php cancella i dati di sessione.
- install.php inizializza il database ed aggiunge alcune voci di prova.
- connection.php consente l'accesso al database.

Queste sono pagine presenti dal precedente esercizio:
- index.php svolge il ruolo di pagina principale è contiene i collegamenti ipertestuali per le altre pagine.
- pag1.html, pag2.html, pag3.html, pag4.html sono pagine secondarie che contengono alcune informazioni inerenti la NASA.
- css_xhtml1.css definisce lo stile delle pagine.
- una cartella contenente le immagini utilizzate nel sito.

Indirizzo repository Github: https://github.com/ZentoDev/lweb-PHP_MYSQL
