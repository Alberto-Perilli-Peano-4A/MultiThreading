# MultiThreading
## Teoria nel Multithreading:

Il multithreading è un modello di programmazione che permette di eseguire più sottoprocessi nello stesso momento.
Il multithread è un metodo per poter risparmiare del tempo.

In laboratorio Abbiamo creato un programma di test per verificare quanto spiegato in teoria.
Il programma manda in output una serie di "Hi" e "Hello" per 10 volte ciascuno.
L'ordine dell'output non è regolare,poichè i thread operano in modo indipendente l'uno dall'altro. Ecco alcuni esempi:

>Esempio output 1: Hi Hi Hi Hi Hello Hello Hello Hello Hello Hello Hello Hello Hello Hello Hi Hi Hi Hi Hi Hi

>Esempio output 2: Hi Hi Hi Hi Hi Hi Hi Hi Hi Hi Hello Hello Hello Hello Hello Hello Hello Hello Hello Hello

>Esempio output 3: Hi Hi Hello Hello Hello Hello Hello Hello Hello Hello Hello Hello Hi Hi Hi Hi Hi Hi Hi Hi

 Durante l'esperienza, abbiamo apportato diverse modifiche al programma; inizialmente si era partiti con due calssi differenti : Hi ed Hello, ognuna che doveva dare in output 10 volte il proprio ouput, mentre nella seconda parte abbiamo creato una singola classe, la classe say, che riceveva in output le due stringhe da mandare in output. Il vantaggio nel secondo caso è sia di tempo poiche si dovrà scrivere un singolo metodo, inoltre è piu veloce anche per il computer
