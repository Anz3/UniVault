### Come funziona **`ecall`**?

1. **Imposta il numero della syscall**:
    
    - Prima di invocare `ecall`, devi **caricare un numero identificativo della syscall** nel registro `a7`.
        - Ad esempio, se vuoi stampare una stringa, il numero della syscall è **4**, quindi imposterai `a7` a **4**.
2. **Carica i dati necessari nei registri**:
    
    - A seconda della syscall che vuoi usare, alcuni registri (come `a0`, `a1`, ecc.) vengono usati per passare i **parametri**.
        - Per stampare una stringa, **l'indirizzo della stringa** va caricato nel registro `a0` (ad esempio, `la a0, b`).
3. **Esegui l'istruzione `ecall`**:
    
    - Quando esegui `ecall`, **il sistema operativo (o la simulazione)** guarda il numero di syscall in `a7` e decide quale operazione eseguire.
        - Se `a7 == 4` (che è la syscall per stampare una stringa), il sistema operativo **prende l'indirizzo della stringa da `a0`**, legge la stringa in memoria, e la stampa a schermo.
4. **Esegui l'operazione**:
    
    - La syscall esegue l'operazione e poi il controllo torna al programma.

### IMPORTANTE NB:
**quindi diciamo il contenuto delle syscal deve stare sempre in a0, mentre l istruzione della syscal sempre in a7**