Scrivi un programma che stampi in console i numeri da 1 a 100, ma che per i multipli di 3 stampi “Fizz” al posto del numero e per i multipli di 5 stampi “Buzz”. Per i numeri che sono sia multipli di 3 che di 5 stampi “FizzBuzz”.
Prima di partire a scrivere codice poniamoci qualche domanda:
Come faccio a sapere se un numero è divisibile per un altro? Abbiamo visto qualcosa di particolare che possiamo usare?
Consigli del giorno:
Scriviamo sempre prima dei commenti in italiano per capire cosa vogliamo fare
Proviamo ad immaginare le operazioni che vogliamo far svolgere al nostro programma così come lo faremmo "a mano"
Numero minimo di push: 5 (solo parte obbligatoria)
BONUS 1: Crea un container nel DOM , aggiungendo (attraverso la funzione append()) un elemento html con il numero o la stringa corretta da mostrare.
BONUS 2: Applica stili differenti agli elementi aggiunti al DOM nel BONUS 1, a seconda che il valore inserito sia un numero, un fizz, un buzz o un fizzbuzz. Se sei a corto di idee per lo stile, potresti prendere spunto dallo screenshot fornito in consegna.

Pseudocodice
1 creo elemento (lista) nel file html
2 uso il ciclo for in cui imposto, nel file js
2.1 la variabile contatore inizializzandola a 0
2.2 la condizione di fine ciclo, ovvero: variabile <= 100
2.3 l'incremento della variabile contatore, ovvero: variabile++
3 nel ciclo imposto le condizioni:
3.1 IF variabile è multiplo di 3, <li> deve contenere la scritta "Fizz"
3.2 ELSE IF variabile è mltiplo di 5, <li> deve contenere la scritta "Buzz"
3.3 ELSE IF variabile è multiplo di 3 && variabile è multiplo di 5, <li> deve contenere la scritta "Fizzbuzz"