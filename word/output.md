DRSCBxx

Manuale d’istruzioni

 

DRSCB433

CENTRALE DI COMANDO PER SERRANDE, TAPPARELLE, TENDE DA SOLE E VASISTAS CON RICEVENTE 433 MHz A BORDO

DRSCBMF

CENTRALE DI COMANDO PER SERRANDE, TAPPARELLE, TENDE DA SOLE E VASISTAS CON RICEVENTE MULTIFREQUENZA A BORDO E USCITA AUSILIARIA

Avvertenze importanti

Domotime Srl si riserva il diritto di apportare modifiche tecniche al prodotto senza preavviso; declina inoltre ogni responsabilità per danni a persone o cose dovuti a uso improprio o installazione errata della centralina DRSCBMF o della centralina DRSCB433\.

Questo manuale di istruzioni è destinato esclusivamente a personale tecnico qualificato nel campo delle installazioni di automazione\.

Nessuna delle informazioni contenute in questo manuale è destinata all'utente finale\.

Per chiarimenti tecnici o problemi di installazione, Domotime Srl dispone di un servizio di assistenza clienti, che risponde al numero di telefono 030 9913901\.

Presentazione del prodotto

Le centraline DRSCB433 e DCRSCBMF fanno della semplicità e della sicurezza i loro punti di forza\.

Caratterizzate per il loro design semplice, le loro funzioni essenziali e la struttura del box in ABS, le centraline sono progettate per comandare serrande, tende, tapparelle e vasistas\.

La ricevente che montano a bordo è di altissima qualità: 

\-	DRSCB433: monta una ricevente in grado di apprendere codici fissi e rolling code a 433 MHz

\-	DRSCBMF: monta una ricevente in grado di apprendere codici fissi e rolling code da 433 MHz a 868 MHz

La centralina DRSCBMF ha inoltre un’uscita ausiliaria in grado di comandare una luce di cortesia, un lampeggiante aggiuntivo o qualsiasi altro dispositivo che ha la necessità di essere attivato\.

Dati tecnici

Modello	DRSCB433	DRSCBMF

Tensione di funzionamento	230Vac ± 10% \(50\-60 Hz\)

Tensione di uscita Motore	230Vac

Potenza max\. Motore	1kW

Tensione di uscita Lampeggiante	230Vac

Potenza max\. Lampeggiante	40W

Uscita relè Ausiliario AUX	\-	Contatto pulito

Tensione di uscita per servizi	12Vac

Tempo lavoro	Programmabile \(3s \- 30s\)

Tempo richiusura automatica	Programmabile \(max\. 240s\)

Modulo radio	433,92 MHz	433,92\-868 MHz

Dimensioni box	140x96x50 mm

Grado di protezione	IP56

Temperatura di esercizio	\-20°C / \+70°C

Schema di collegamento

 

Collegamento ingressi\-uscite

\- Collegare ai morsetti L ed N l’alimentazione di rete 230Vac\.

ATTENZIONE: durante la fase di collegamento di ingressi ed uscite la centrale non deve essere alimentata\. 

\- Collegare il motore rispettando gli avvolgimenti di apertura \(OP\) e chiusura \(CLO\), il morsetto centrale è riservato al comune\.

\- Ai morsetti LAMP collegare un lampeggiante 230Vac\. 

Il suo funzionamento è limitato alla durata della manovra di apertura o chiusura del motore\.

Il lampeggiante viene alimentato direttamente dal relè, non è necessario quindi prendere l’alimentazione da altri morsetti\.

\- Ai morsetti AUX \(solo su DRSCBMF\) è possibile collegare un dispositivo \(ad es\. luce di cortesia\)\. 

Consultare i paragrafi successivi per il funzionamento desiderato\.

Il relè è a contatto pulito, per alimentare un dispositivo è necessario prendere l’alimentazione dall’esterno\.

\- I morsetti 12Vac forniscono una tensione alternata per l’alimentazione di dispositivi esterni\.

\- Utilizzare il morsetto C come comune per gli ingressi Pa/C, Sic e Stop\.

\- Al morsetto Pa/C \(NO\) può essere collegato un pulsante per la funzione passo\-passo\.

\-	Al morsetto Sic \(NC\) può essere collegata una sicurezza \(ad es\. fotocellula\)\. In fase di chiusura se il contatto si apre \(fotocellula impegnata\), la centrale inverte il movimento ed effettua un’apertura completa\. In fase di apertura la sicurezza Sic non interviene\.

\- Al morsetto Stop \(NC\) può essere collegata una sicurezza \(ad es\. fungo di emergenza\)\. In caso di intervento \(apertura del contatto\), arresta istantaneamente il movimento del motore\. Dopo l’intervento non è possibile eseguire alcuna manovra fino al corretto ripristino del contatto di Stop\.

Nel caso non vengano utilizzate sicurezze, per il corretto funzionamento della centrale è necessario chiudere i morsetti Sic e Stop col morsetto C mediante ponticello\.

NOTA: all’accensione della centrale il relè AUX chiude il contatto per 5 secondi \(solo su DRSCBMF\)\.

Registrazione telecomandi

NOTA: Ogni tasto registrato corrisponde ad un codice\.

Esempio: se si registrano tutti i canali di un trasmettitore a 4 tasti, vengono inseriti nella centrale 4 codici\.

REGISTRAZIONE RADIOCOMANDI PER COMANDO MOTORE:

Per la registrazione di un trasmettitore premere il tasto P una sola volta, il led LD1 inizia a lampeggiare velocemente; tenere premuto il tasto del trasmettitore che si desidera registrare per qualche secondo fino all’accensione di tutti e quattro i led LD1, LD2, LD3 e LD4, quindi rilasciarlo\. 

Ripetere questa operazione per tutti i trasmettitori che si intendono utilizzare per il comando del motore\.

REGISTRAZIONE RADIOCOMANDI PER COMANDO RELE’ AUX \(solo su DRSCBMF\):

Per la registrazione di un trasmettitore premere il tasto P due volte, il led LD2 inizia a lampeggiare velocemente; tenere premuto il tasto del trasmettitore che si desidera registrare per qualche secondo fino all’accensione di tutti e quattro i led LD1, LD2, LD3 e LD4, quindi rilasciarlo\. 

Ripetere questa operazione per tutti i trasmettitori che si intendono utilizzare per il comando del relè AUX\.

Cancellazione telecomandi

RESET RADIOCOMANDI: questa operazione consente di eliminare singolarmente i codici presenti all’interno della centrale\.

Premere il tasto P una sola volta, il led LD1 inizia a lampeggiare, quindi premere il tasto S\. Quando i quattro led restano accesi, tenere premuto il tasto del trasmettitore che si desidera cancellare finché non si spengono i led LD1 e LD2\. Ripetere questa operazione per ogni codice del trasmettitore che si vuole cancellare\.

RESET TOTALE RADIOCOMANDI: questa operazione consente di eliminare tutti i codici presenti all’interno della centrale\. 

Tenere premuti contemporaneamente i tasti P ed S per circa sette secondi fino a un lampeggio simultaneo e veloce dei led LD1, LD2, LD3 e LD4, quindi rilasciare i tasti\.

Stato centrale – segnalazione LED

LD3	LD4	Descrizione

 	 	La serranda sta scendendo

\(Manovra di chiusura\)

 	 	La serranda sta salendo

\(Manovra di apertura\)

 	 	La serranda è bassa \(chiusa\)

 	 	La serranda è alta \(aperta\)

 	 	La serranda si trova in posizione ignota

 	 	La serranda è in attesa di richiusura 

\(solo con chiusura automatica abilitata\)

Fase di apprendimento

Nella fase di apprendimento vengono definiti i tempi di manovra della serranda e il tempo di attesa per la richiusura automatica\.

Portare DIP2 a ON, i quattro led LD1, LD2, LD3 e LD4 si accendono simultaneamente\.

INIZIO APPRENDIMENTO

1\. I quattro led LD1, LD2, LD3 e LD4 sono accesi\.

2\. Verificare che gli ingressi Sic e Stop siano collegati nella configurazione NC\.

3\.	Per le manovre della serranda utilizzare un trasmettitore associato al comando del motore o utilizzare il comando Pa/c\.

4\. Posizionare manualmente la serranda a metà\. 

5\.	Premere il tasto del trasmettitore o dare il comando Pa/c, la serranda si abbassa \(manovra di chiusura\) fino all’intervento dei finecorsa interni o comando manuale\.

Se la serranda sale, sta eseguendo un’apertura: è necessario invertire i collegamenti OP\-CLO del motore e iniziare nuovamente la procedura di apprendimento\.

6\.	Premere il tasto del trasmettitore o del comando Pa/c, la serranda inverte immediatamente il suo movimento \(manovra di apertura\) fino all’intervento dei finecorsa interni o comando manuale\.

7\.	Terminata la manovra di apertura i led LD1, LD2 e LD3 risultano accesi, LD4 lampeggiante\. Il numero di lampeggi \(circa 1 al secondo\) indicano il tempo di attesa per la richiusura automatica, attendere il tempo desiderato\. 

8\. Premere il tasto del trasmettitore o dare il comando Pa/c per bloccare il tempo di richiusura automatica, successivamente la serranda esegue una chiusura\.

9\. Premere il tasto del trasmettitore o dare il comando Pa/c, la serranda esegue un’apertura\.

10\. Non vengono accettate altre manovre, memorizzare i dati come descritto di seguito\.

FINE APPRENDIMENTO: 

Al termine della fase di apprendimento è necessario memorizzare i dati nella centrale\.

Portare il DIP2 a OFF\. I led LD3 e LD4 si accendono, LD1 e LD2 si spengono\.

Terminata la fase di apprendimento e memorizzazione dei dati la centrale risulta installata\.

Funzioni programmabili

Relè ausiliario AUX \(solo su DRSCBMF\): 

\-	La prima funzione è definita “asservito al motore”, nella quale il relè AUX chiude il contatto ad ogni manovra eseguita dal motore \(utilizzabile ad esempio per luce di cortesia\)\. 

\-	La seconda funzione è definita “non asservito al motore”, nella quale tramite un trasmettitore associato l’utente può aprire e chiudere il contatto di AUX indipendentemente dalle manovre del motore\.

In entrambe le funzioni AUX è configurabile bistabile, impulsivo, timer secondi e timer minuti\.

NOTA: nel caso in cui il relè AUX è asservito al motore, nelle modalità bistabile e impulsivo il contatto resta chiuso per 60 secondi dall’ultima manovra eseguita\.

Richiusura automatica: 

\-	se attiva, abbassa la serranda \(manovra di chiusura\) in modo automatico dopo un tempo di attesa stabilito dall’installatore durante la fase di apprendimento\. Se disattiva, la chiusura avverrà soltanto manualmente tramite trasmettitore o comando Pa/c\.  

Comando di sola apertura: 

\-	questa funzione è anche detta “condominiale”\. Se attiva si possono eseguire solo comandi di apertura, la chiusura è possibile tramite trasmettitore o comando Pa/c quando la serranda si trova completamente aperta oppure con richiusura automatica attiva dopo il tempo di attesa stabilito in fase di apprendimento\.

DIP	Posizione	Funzione	Descrizione

1 OFF	 	Relè ausiliario AUX	Il relè AUX non è asservito al funzionamento del motore

1 ON	 		Il relè AUX è asservito al funzionamento del motore

2 OFF	 	Apprendimento	Al termine dell’apprendimento impostare DIP2 OFF

2 ON	 		Impostare DIP2 ON per accedere alla fase di apprendimento

3 OFF	 	Richiusura automatica	La richiusura automatica è disabilitata

3 ON	 		La richiusura automatica è abilitata

4 OFF	 	Comando di sola apertura	Il comando di sola apertura è disabilitato

4 ON	 		Il comando di sola apertura è abilitato

Configurazione relè ausiliario AUX \(solo su DRSCBMF\)

Il relè AUX è configurabile per funzionare in quattro diverse modalità: bistabile, impulsivo, timer secondi e timer minuti\. Esse possono essere modificate e impostate in qualsiasi momento\.

NOTA: Il tasto S permette di entrare nella modalità di configurazione del relè, il tasto P ne modifica le impostazioni\.

Per procedere alla configurazione del relè AUX: 

Tenere premuto il tasto S fino all’accensione del led LD2, quindi rilasciarlo\.

Di fabbrica il relè è configurato in modo impulsivo\. Per modificare la modalità del relè premere il tasto P, il led LD2 lampeggia secondo la modalità impostata \(vedi tabella sottostante\); ad ogni nuova pressione di P la configurazione passa alla modalità successiva in modo ciclico\. Impostata la modalità di funzionamento desiderata attendere che il led smetta di lampeggiare\.

1 Lampeggio	☼	BISTABILE

2 Lampeggi	☼ \- ☼	IMPULSIVO

3 Lampeggi	☼ \- ☼ \- ☼	TIMER SECONDI

4 Lampeggi	☼ \- ☼ \- ☼ \- ☼	TIMER MINUTI

Modalità Bistabile: ad una pressione del trasmettitore associato il contatto del relè si chiude, alla pressione successiva si apre\. Lo stato del relè viene mantenuto finché non arriva un’altra pressione del trasmettitore\. ATTENZIONE: l’assenza di alimentazione riporta l’uscita al suo stato di riposo, ovvero contatto aperto\.

Modalità Impulsiva: il contatto del relè resta chiuso per tutta la durata della pressione del trasmettitore associato, una volta rilasciato si apre\. 

ATTENZIONE: eventuali disturbi possono aprire il contatto anche se il tasto del trasmettitore è ancora premuto\.

Modalità Timer secondi: in questa modalità è possibile impostare un tempo in secondi dopo il quale il contatto del relè viene aperto\. Di fabbrica il timer ha un’impostazione di 30 secondi\. 

ATTENZIONE: il timer viene ricaricato ogni volta che viene premuto un trasmettitore associato\.

Modalità Timer minuti: in questa modalità è possibile impostare un tempo in minuti dopo il quale il contatto del relè viene aperto\. Di fabbrica il timer ha un’impostazione di 30 minuti\. 

ATTENZIONE: il timer viene ricaricato ogni volta che viene premuto un trasmettitore associato\.

Impostazioni del timer

Mentre si è in modalità timer \(secondi o minuti\) tenere premuto il tasto S per circa 2 secondi e attendere che il led LD2 lampeggi in modo regolare \(un lampeggio al secondo\)\. 

Mantenere premuto il tasto S e contare il numero di lampeggi del led a seconda dei secondi o minuti che si desidera impostare\. Esempio: conto 5 lampeggi del led per impostare 5 secondi/minuti a seconda della modalità precedentemente selezionata\. 

Contati i lampeggi che si desidera impostare, rilasciare il tasto S\.

Smaltimento RAEE

Lo smaltimento del dispositivo va eseguito rispettando le normative vigenti riguardanti le apparecchiature elettriche ed è opportuno separarli dai rifiuti domestici rivolgendosi ai centri di raccolta rifiuti locali\. 

DRSCBxx
