#### Relè ausiliario AUX \(solo su DRSCBMF\): 

-	La prima funzione è definita “asservito al motore”, nella quale il relè AUX chiude il contatto ad ogni manovra eseguita dal motore \(utilizzabile ad esempio per luce di cortesia\)\. 

-	La seconda funzione è definita “non asservito al motore”, nella quale tramite un trasmettitore associato l’utente può aprire e chiudere il contatto di AUX indipendentemente dalle manovre del motore\.

In entrambe le funzioni AUX è configurabile bistabile, impulsivo, timer secondi e timer minuti\.

NOTA: nel caso in cui il relè AUX è asservito al motore, nelle modalità bistabile e impulsivo il contatto resta chiuso per 60 secondi dall’ultima manovra eseguita\.

#### Richiusura automatica: 

-	se attiva, abbassa la serranda \(manovra di chiusura\) in modo automatico dopo un tempo di attesa stabilito dall’installatore durante la fase di apprendimento\. <br>Se disattiva, la chiusura avverrà soltanto manualmente tramite trasmettitore o comando Pa/c\.  

#### Comando di sola apertura: 

-	questa funzione è anche detta “condominiale”\. <br>Se attiva si possono eseguire solo comandi di apertura, la chiusura è possibile tramite trasmettitore o comando Pa/c quando la serranda si trova completamente aperta oppure con richiusura automatica attiva dopo il tempo di attesa stabilito in fase di apprendimento\.

| DIP |	Posizione |	Funzione |	Descrizione |
| - | - | - | - |
| 1 | OFF |	 	Relè ausiliario AUX	| Il relè AUX non è asservito al funzionamento del motore |
| 1 | ON |	 Relè ausiliario AUX	|		Il relè AUX è asservito al funzionamento del motore
| 2 | OFF |	 	Apprendimento	| Al termine dell’apprendimento impostare DIP2 OFF
| 2 | ON | Apprendimento |		Impostare DIP2 ON per accedere alla fase di apprendimento
| 3 | OFF |	 	Richiusura automatica |	La richiusura automatica è disabilitata
| 3 | ON | Richiusura automatica |	 		La richiusura automatica è abilitata
| 4 | OFF |	 	Comando di sola apertura|	Il comando di sola apertura è disabilitato
| 4 | ON | Comando di sola apertura |	 		Il comando di sola apertura è abilitato


#### Configurazione relè ausiliario AUX \(solo su DRSCBMF\)

Il relè AUX è configurabile per funzionare in quattro diverse modalità: bistabile, impulsivo, timer secondi e timer minuti\. Esse possono essere modificate e impostate in qualsiasi momento\.

NOTA: Il tasto S permette di entrare nella modalità di configurazione del relè, il tasto P ne modifica le impostazioni\.

Per procedere alla configurazione del relè AUX: 

- Tenere premuto il tasto S fino all’accensione del led LD2, quindi rilasciarlo\.

Di fabbrica il relè è configurato in modo impulsivo\. 
<br>Per modificare la modalità del relè premere il tasto P

- Il led LD2 lampeggia secondo la modalità impostata \(vedi tabella sottostante\)
- Ad ogni nuova pressione di P la configurazione passa alla modalità successiva in modo ciclico\. 
- Impostata la modalità di funzionamento desiderata attendere che il led smetta di lampeggiare\.

| Lampeggi | Modalità |
| - | - |
| 1 Lampeggio|	**BISTABILE**
| 2 Lampeggi |	**IMPULSIVO**
| 3 Lampeggi | **TIMER SECONDI**
| 4 Lampeggi | **TIMER MINUTI**

- Modalità Bistabile: ad una pressione del trasmettitore associato il contatto del relè si chiude, alla pressione successiva si apre\. <br>Lo stato del relè viene mantenuto finché non arriva un’altra pressione del trasmettitore\. **ATTENZIONE: l’assenza di alimentazione riporta l’uscita al suo stato di riposo, ovvero contatto aperto\.**

- Modalità Impulsiva: il contatto del relè resta chiuso per tutta la durata della pressione del trasmettitore associato, una volta rilasciato si apre\. <br>
**ATTENZIONE: eventuali disturbi possono aprire il contatto anche se il tasto del trasmettitore è ancora premuto\.**

- Modalità Timer secondi: in questa modalità è possibile impostare un tempo in secondi dopo il quale il contatto del relè viene aperto\. Di fabbrica il timer ha un’impostazione di 30 secondi\. <br>**ATTENZIONE: il timer viene ricaricato ogni volta che viene premuto un trasmettitore associato\.**

- Modalità Timer minuti: in questa modalità è possibile impostare un tempo in minuti dopo il quale il contatto del relè viene aperto\. Di fabbrica il timer ha un’impostazione di 30 minuti\.<br>**ATTENZIONE: il timer viene ricaricato ogni volta che viene premuto un trasmettitore associato\.**

#### Impostazioni del timer

Mentre si è in modalità timer \(secondi o minuti\) 

- Tenere premuto il tasto S per circa 2 secondi e attendere che il led LD2 lampeggi in modo regolare \(un lampeggio al secondo\)\. 

- Mantenere premuto il tasto S e contare il numero di lampeggi del led a seconda dei secondi o minuti che si desidera impostare\. <br>Esempio: conto 5 lampeggi del led per impostare 5 secondi/minuti a seconda della modalità precedentemente selezionata\. 

- Contati i lampeggi che si desidera impostare, rilasciare il tasto S\.