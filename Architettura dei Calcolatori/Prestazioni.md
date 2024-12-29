

trhugput: quanti dati riesco a trasmettere in un dato di tempo

bandwith il tempo che ci metto a trasferire un dato 

latency quanto tempo ci metto a trasmettere un singol9 byte


## Definizioni:
Le prestazioni sono in unità di "oggetti per secondo "
more is better.

Se siamo interessati al tempo di risposta:
- Px = 1/Ex
- Px= prestazioni della macchina X
- tempo di esecuzione della macchina X
Speed up rispetto a una macchina di riferimento 
TODO

Tj = Tempo totale (Tempo trascorso) --> tempo necessario per completare il lavoro compreso delle interferenze di altri programmi

Tcpu: Tempo di CPU(Tempo di esecuzione del programma)-> tempo in cui il processore a eseguito il programma quindi il tempo vero e proprio di esecuzione.
e può essere suddiviso in:
Tu= tempo CPU relativo all utente 
Tk= tempo di CPU realtivo al sistema operativo (K-Kernel)


**In questa immagine vediamo come con il comando time otteniamo i valori sopracitati**
![[Pasted image 20241127093707.png]]

### equazione delle prestazioni:
![[Pasted image 20241127093927.png]]
Dove:
- <u>Tc</u> è il periodo di clock
- <u>fc</u> è la frequenza di clock == 1/Tc
- <u>Ccpu</u> sono i cicli di clock
- <u>Ncpu</u> è il numero di istruzione eseguite **Dinamicamente**
- <u>CPI</u> è il numero di cicli per istruzione (medio)


