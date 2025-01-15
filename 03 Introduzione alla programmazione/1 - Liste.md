>![info] Liste


![[Struttura lista.png]]



### Definiamo il tipo di ogni elemento nella lista (cella):
```
	Struct cell{
	T info: // <--- T = tipo noto
	cell *next;
	};
```


![[Cancellazione liste.png]]

### Inserimento:
ci sono 3 tipi diversi di inserimento:
1. Alloco nella nuova cella sullo heap
2. se va 
3. 
4. Se va inserito tra 2 celle esitenti: 
	- allora si localizza la cella che deve precederlo
	- si mette nel campo next della nuova cella il puntatore alla cella che deve essere seuizrlo?(che p il campo next della cella che lo precede)
	- si mette nel capo next della cella che lo precede il puntatore alla nuova cella
5. Se va inserito come prima elemento ma in una lista non vuota:
	-  si copia nel campo next del nuovo elemento il puntatore che c'è nella testa
	- si mette nella testa il puntatore alla nuova cella


Immagine inserimento grafico guarda foto telefono 5 dicembre


