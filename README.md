# Shell-C-GitHub
<p align="center">
  <a href="#" target="_blank"><img alt="shell_logo" src="https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white"></a>
  <a href="#" target="_blank"><img alt="git_logo" src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white"></a>
  <a href="#" target="_blank"><img alt="c_logo" src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"></a>
  <a href="#" target="_blank"><img alt="ubuntu_logo" src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"></a>
</p>

## Riscaldamento
### Esercizio 0
- apri una shell dell'emulatore linux su windows (Windows Subsystem for Linux - WSL)
- in generale, per i prossimi esercizi, se non sai quali parametri dare ad un comando, digita: `<nome_comando> --help` oppure `<nome_comando> -h`
- lancia un comando per capire in quale cartella ti trovi (Hint: Print Working Directory)
- lancia un comando per capire come spostarti nella cartella padre (Hint: Change Directory)
- lancia un comando per stampare una lista delle cartelle e dei file contenuti nella cartella corrente (Hint: LiSt)
- crea un nuova directory (cartella, MaKe DIRectory) chiamata "tuo_nome"
- entra nella cartella che hai creato
- controlla che sia stata correttamente creata
- crea un file vuoto chiamato `testo.txt` ( Hint: `touch <nomefile>` )
- controlla che sia stato correttamente creato
- lancia un comando per capire chi è il proprietario del file creato
- spostati nella cartella padre
- elimina la cartella che avevi creato (Hint: ReMove)
- lancia il comando per visualizzare tutti i processi in esecuzione (`htop`)

### Esercizio 1
- crea un file chiamandolo `hello_world.c`
- apri il file creato e scrivi un programma in `c` che mi stampi "Hello World" (Hint: nano)
- - ricordati di mettere in alto
  - - `#include<stdio.h>`
  - - `#include<stdlib.h>`
   
### Esercizio 2
- somma di due numeri
- media tra due numeri
- chiedi due numeri A e B e stampa quale dei due è più grande
- somma N valori, con N dato in input (senza usare vettori)
- riempi un vettore di dimensione N, con N dato in input, e fai un menù che mi permette di 1) stampare la somma di tutti i numeri; 2) la differenza di tutti i numeri; 3) la media; 4) l'indice dell'elemento più grande; 5) l'indice dell'elemento più piccolo; 6) ricerca un elemento dato in input e stampa il suo indice.


## Puntatori
### Es1
Scrivere un programma in C che permetta di 
1) stampare il valore di un variabile puntata dal puntatore,
2) stampare il valore incrementato di 3 SENZA modificare la variabile puntata (utilizzando il puntatore)
3) di stampare l'indirizzo della variabile
Il tutto utilizzando un menù per la scelta dell'opzione da utilizzare.

### Es2
Scrivere un programma in C che permetta di 
1) stampare il valore di un variabile puntata dal puntatore,
2) stampare il valore incrementato di 3 SENZA modificare la variabile puntata (utilizzando il puntatore)
3) di stampare l'indirizzo della variabile
Il tutto utilizzando un menù per la scelta dell'opzione da utilizzare.
Scrivere una funzione per ogni punto richiesto

### Es3
Scrivere un programma in C che stampi il valore puntato dal puntatore.
Il valore a cui punta è un dato di tipo char settato a piacimento

### Es4
Scrivete una funzione con prototipo void scambia( int *p, int *q ) che scambi i valori delle due variabili puntate da p e q.
Utilizzare la funzione all'interno del main.

### Es5
Scrivete una funzione con prototipo void max_secondmax ( int a[], int n, int *max, int *second_max ) che, dato un array a di lunghezza n individui il valore più grande in a e il secondo elemento per grandezza in a, e li memorizzi nelle variabili puntate da max e second_max.
Utilizzare la funzione all'interno del main.

### Es6
Creare un programma in C che:
1) generi un vettore di 10 elementi casuali
2) che mi stampi l'indirizzo della prima cella
3) che setti il puntatore all'indirizzo della cella che contiene il valore più basso nel vettore, e ne stampi l'indirizzo della cella
4) modifichi il valore puntato dal puntatore con un valore inserito dall'utente

Il tutto utilizzando un menù per la scelta dell'opzione da utilizzare.
Utilizzare opportunamente le funzioni ed i passaggi dei parametri alle funzioni

### Es7
Scrivi in linguaggio C la seguente funzione:
void trovaValore(char[] vettore, int dim, char valoreDaTrovare, int* indice)
in modo che ‘indice’ sia uguale alla posizione in cui è presente “valoreDaTrovare” nel vettore

### Es8
Creare un programma in C che:
1) generi un vettore di 10 elementi casuali
2) che mi stampi l'indirizzo della cella i-esima, con i inserito dall’utente
3) che setti il puntatore all'indirizzo della cella che contiene il valore uguale alla
media aritmetica di tutti i valori presenti nel vettore ALTRIMENTI punti alla cella
contenente il valore più alto presente nel vettore
4) modifichi il valore puntato dal puntatore con un valore inserito dall'utente
   
Il tutto utilizzando un menù per la scelta dell'opzione da utilizzare.
Utilizzare opportunamente le funzioni ed i passaggi dei parametri alle funzioni.
Esempio di vettore utile per il punto 3
1, 5, 7, 12, 14, 27, 30, 8, 25, 11

## Struct

### Es1
Definisci una struttura Persona con ALMENO 5 proprietà, chiedi poi all'utente di inserire i dati di una persona e stampa infine un messaggio con tutti i dati della persona inserita con un'unica printf().

### Es2
Definisci una struttura Persona con ALMENO 5 proprietà, chiedi poi all'utente di inserire i dati di 6 persone e stampa infine un messaggio con tutti i dati delle persone inserite.
Definisci una funzione personalizzata che ti permetta, passando come parametro una struct Persona, di fare la stampa di tutte le proprietà della struttura Persona.

### Es3
Definisci una struttura Persona con ALMENO 5 proprietà, chiedi poi all'utente di inserire i dati di 10 persone e conserva tutte le persone all'interno di un vettore.
- Definisci una funzione il cui scopo è quello di chiedere SOLO tutti i dati necessari per inserire UNA persona.
- Definisci una funzione il cui scopo è quello di fare SOLO la stampa di UNA sola struct Persona.
- Definisci una funzione il cui scopo è quello di stampare tutte le persone all'interno di un vettore di qualunque dimensione.
- Definisci una funzione "media_eta" il cui scopo è quello di calcolare la media dell'età di tutte le persone presenti nel vettore.
- Costruisci il main, con un appositò menù, in modo che l'utente possa: 
  1) inserire tutti gli utenti
  2) stampare la Persona nella cella i-esima (chiesta all'utente)
  3) stampare la media delle età


