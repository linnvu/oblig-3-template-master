# Obligatorisk oppgave 3 i Algoritmer og Datastrukturer

Denne oppgaven er en innlevering i Algoritmer og Datastrukturer. 
Oppgaven er levert av følgende student:

Ngoc Linn Vu Huynh, s364523, s364523@oslomet.no


# Oppgavebeskrivelse

I oppgave 1 så gikk jeg frem ved å kopiere programkode 5.2.3 a) fra kompendiet. I koden sjekkes hver node om vrdien som blir lagt inn er mindre, større eller lik den gjellende nodens verdi.

er verdien mindre flyttes den til høyre barnet, er den større flyttes den til venstre barnet.
Når den gjellende noden er null, lages det en ny node som peker til den forrige noden og den forrige noden pekes på den nye noden.

I oppgave 2 teller den antall forekomster det er i treet. den teller også i tillegg duplikater hvis det er flere av samme verdi. det returneres i antallVerdi når det ikke lenger er noen flere forekomster.

I oppgave 3 leter førstePostorden() etter den første noden med postorden gjennom while-løkken. den starter ved å sjekke nodene som ligger på venstre side, og helt rundt treet til den finner den første noden med postorden.
nestePostorden() sjekker om startnoden er rotnoden, videre returnerer den neste postnoden som kommer etter den først postnoden p.

I oppgave 4 lages det hjelpemetoder som gjør oppgaven, andre metoder blir kaldt i koden for både venstre og høyre barn hvis de finnes. så kalles oppgave.utførOppgave(p.verdi);.