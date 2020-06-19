# Potapanje-brodica
Napraviti stranicu uz oslonac na HTML, CSS i JavaScript,
bez ikakvog frameworka, za igranje igrice potapanje
brodova.
● Na početku se bira veličina igračke table (dozvoljeno je
staviti dva window.prompta unutar init funkcije za onload,
po jedan za visinu i širinu table), zatim se generišu tabla i
brodići. Tabla je na početku prazna, tj. izgleda slično
primeru x-o sa vežbi (prazni beli kvadrati).
Kada igrač stisne na određeno polje, u zavisnosti od toga da li se tu
nalazi deo broda, boji se na plavo (promašaj) ili na crveno
(pogodak).
● Brodići su svi veličine jednog polja i ima ih uvek tri puta manje od
broja polja. Npr. za 10x10 tablu imamo 33 brodića (paziti na
preklapanja).
● Igrač ima broj poteza jednak polovini brojeva polja + 10. Npr. za
tablu 10x10 ima 60 poteza i ako pogodi sve brodiće za to vreme,
pobedio je, ako ne, izgubio je.
● Minimalna tabla je 5x5, ako korisnik unese manje, generise se 5x5.
● Za sve nejasnoće javite se meni na mail.
