# Prime specifiche del progetto

I punti fondamentali da rispettare sono:
- HTML facile da auto-generare con un computer
- HTML che ha una buona resa di stampa
- Il tutto dovrà essere stampato su carta, teniamolo il più semplice possibile


Per passare da HTML ad un documento stampabile (pdf) al momento penso di affidarmi a [DocRaptor](https://docraptor.com/), quindi è necessario essere certi che docraptor riesca a generare un buon pdf.

DocRaptor dovrebbe essere in grado di generare pdf di forma quadrata, più info [qui](http://www.princexml.com/doc/9.0/page-size/).

Pensado al progeto, in un ottica di produzione, penso che sia meglio generare un html continuo , senza divisioni tra pagina e pagina (in una pagina tutti i testi, nell'altra le foto ad esempio <--- questo NO)ma uno stream continuo di div che riempiono la pagina.

Comunque sia la parte davvero fondamentale è che il pdf generato da DocRaptor sia esteticamente bello.

Docraptor non è un punto fisso, ma può essere sostituito da qualunque alternativa valida, comunque sia mi DocRaptor mi pare un prodotto valido, soprattutto se mettiamo un pò di attenzione nello sviluppo del HTML.

DocRaptor usa [Price](http://www.princexml.com/) come backend, [qui](http://www.princexml.com/doc/9.0/), la documentazione di Price da seguire come referenza.