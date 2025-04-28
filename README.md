# Space_Invaders
Navicella Spaziale (Invaders Clone - Boss Fight!)
Un semplice clone del classico gioco Space Invaders, arricchito con combattimenti contro i boss alla fine di ogni livello. Realizzato interamente con HTML, CSS e JavaScript vanilla.


 Descrizione
Questo progetto è un omaggio ai classici giochi arcade shoot em up. 
Il giocatore controlla una navicella spaziale alla base dello schermo e deve distruggere ondate di alieni che scendono dallalto. Ogni livello culmina in una battaglia contro un boss più resistente. Il gioco tiene traccia del punteggio e salva il miglior punteggio locale nel browser.

 Funzionalità Principali
   Gameplay classico stile Space Invaders.
   Livelli multipli con difficoltà crescente.
   Combattimenti contro Boss alla fine di ogni livello.
   Due modalità di difficoltà (FACILE / DIFFICILE).
   Sistema di punteggio e salvataggio del miglior punteggio (Best Score) tramite Local Storage.
   Sistema di vite per il giocatore.
   Effetti visivi: esplosioni, particelle, animazioni "hit".
   Effetti sonori per spari, movimento alieni, esplosioni, game over, ecc.
   Funzionalità di Pausa (tasto ESC o pulsante mobile).
   Controlli ottimizzati sia per Desktop (mouse/tastiera) che per Mobile (pulsanti touch).
   Schermata iniziale per selezione difficoltà e avvio.
   Schermata di Game Over con punteggio finale.
   Schermata di istruzioni.
   Estetica retrò/pixelata con font "Press Start 2P".
 

Come Giocare

 Obiettivo

Distruggi tutte le ondate di alieni e sconfiggi il boss di fine livello. Evita i proiettili nemici e impedisci agli alieni (o al boss) di raggiungere la linea verde alla base dello schermo.

 Controlli

Desktop:
   Muovi il mouse: Sposta la navicella orizzontalmente.
   Barra Spaziatrice / Click Sinistro del mouse: Spara un proiettile.
   Tasto ESC: Metti in pausa / Riprendi il gioco.

Mobile:
   Pulsante ← (Sinistra): Sposta la navicella a sinistra.
   Pulsante → (Destra): Sposta la navicella a destra.
   Pulsante SPARA: Spara un proiettile.
   Pulsante II (Pausa - in alto a sinistra): Metti in pausa / Riprendi il gioco.

 Come Eseguire il Gioco

1.  Scarica i file:
Navicella_Spaziale.html
Le immagini: 
La mia arma.png, 
Navicella madre aliena.png
I file audio: 
shoot.wav, 
fastinvader1.wav,
 boss_entry_sound.wav, 
Esplosione_Navicella_Madre_Aliena.wav, 
Game_Over_Partita_Persa.wav

2.  Organizza i file: Assicurati che tutti i file scaricati (HTML, immagini, audio) si trovino nella stessa cartella.

3.  Apri il file HTML: Fai doppio clic sul file Navicella_Spaziale.html o aprilo con un browser web moderno (come Chrome, Firefox, Edge, Safari).
Il gioco dovrebbe avviarsi direttamente nel browser.

 Tecnologie Utilizzate

HTML5: Struttura della pagina e degli elementi di gioco.
CSS3: Styling, layout (Flexbox), animazioni (@keyframes), effetti visivi, font personalizzati.
 JavaScript (ES6+): Logica del gioco, gestione degli input, manipolazione del DOM, collision detection, gestione dello stato (punteggio, vite, livelli, pausa, game over), audio (Web Audio API), salvataggio punteggio (Web Storage API - localStorage).

 Possibili Miglioramenti Futuri

Aggiungere power-up (es. scudi temporanei, fuoco rapido, laser).
Introdurre diversi tipi di alieni con pattern di movimento e attacco unici.
Rendere i pattern di attacco dei boss più complessi e vari.
Implementare barriere/scudi difensivi per il giocatore (come nelloriginale Space Invaders).
Migliorare ulteriormente la reattività e lesperienza su mobile (es. controllo tramite trascinamento del dito).
Refactoring del codice per una migliore organizzazione (es. utilizzo di Classi o Moduli JavaScript).
Aggiungere una leaderboard online.
