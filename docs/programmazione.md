### Fase di apprendimento

Nella fase di apprendimento vengono definiti i tempi di manovra della serranda e il tempo di attesa per la richiusura automatica\.

*Portare DIP2 a ON, i quattro led LD1, LD2, LD3 e LD4 si accendono simultaneamente\.*
<br><br>
#### Inizio apprendimento

1. I quattro led LD1, LD2, LD3 e LD4 sono accesi\.

2. Verificare che gli ingressi Sic e Stop siano collegati nella configurazione NC\.

3.	Per le manovre della serranda utilizzare un trasmettitore associato al comando del motore o utilizzare il comando Pa/c\.

4. Posizionare manualmente la serranda a metà\. 

5.	Premere il tasto del trasmettitore o dare il comando Pa/c, la serranda si abbassa \(manovra di chiusura\) fino all’intervento dei finecorsa interni o comando manuale\.<br>Se la serranda sale, sta eseguendo un’apertura: è necessario invertire i collegamenti OP\-CLO del motore e iniziare nuovamente la procedura di apprendimento\.

6.	Premere il tasto del trasmettitore o del comando Pa/c, la serranda inverte immediatamente il suo movimento \(manovra di apertura\) fino all’intervento dei finecorsa interni o comando manuale\.

7.	Terminata la manovra di apertura i led LD1, LD2 e LD3 risultano accesi, LD4 lampeggiante\. Il numero di lampeggi \(circa 1 al secondo\) indicano il tempo di attesa per la richiusura automatica, attendere il tempo desiderato\. 

8. Premere il tasto del trasmettitore o dare il comando Pa/c per bloccare il tempo di richiusura automatica, successivamente la serranda esegue una chiusura\.

9. Premere il tasto del trasmettitore o dare il comando Pa/c, la serranda esegue un’apertura\.

10. Non vengono accettate altre manovre, memorizzare i dati come descritto di seguito\.

#### Fine apprendimento: 

Al termine della fase di apprendimento è necessario memorizzare i dati nella centrale\.

- Portare il DIP2 a OFF\. 
- I led LD3 e LD4 si accendono, LD1 e LD2 si spengono\.

Terminata la fase di apprendimento e memorizzazione dei dati la centrale risulta installata\.
