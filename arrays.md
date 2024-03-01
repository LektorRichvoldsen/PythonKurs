# Lister

## Oppgave 1

1. Lag listen minListe som inneholder navnet på fem programmeringsspråk

2. Bruk `print()`-funsjonen til å skrive ut det første elementet i listen. Gjør det samme for resten av elementene. 

3. Bruk funskjonen `minListe.pop()` og deretter `print(minListe)` for å se hvordan listen ser ut nå. 
- Hva gjør `pop()`-funksjonen? 
- Hva skjer hvis du putter et tall inni parantesene, f.eks. `minListe.pop(2)`?

4. Legg til et element i listen med `minListe.append()`. Inni parentesene skriver du elementet som skal legges til. 

5. Bytt om det første og siste elementet i listen. 

- Hint: du kan bruke en variabel til midlertidig lagring 
- Hint 2: ved å skrive `minListe[2] = "kotlin"`  settes verdien til elementet på indeks 2 til "kotlin". 

## Oppgave 2
Lag en liste med tilfeldige tall. 
1. Skriv en kodesnutt som teller hvor mange av tallene som er lik 5. 
2. Skriv en ny kodesnutt som teller hvor mange av tallene som er *større enn* 5. 

## Oppgave 3
Du har følgende liste: 
`valutaKurser= [['USD', 10.6], ['EUR', 11.5], ['SEK', 1.0]]` 
1. Bruk `print(valutaKurser[0])` til å skrive ut elementet på plass 0(indeks 0). Hvilken type elementer inneholder listen valutaKurser?
2. Skriv `print(valutaKurser[0][0])`. Hva får du ut da?
3. Listen inneholder valutakoden for amerikanske dollar(USD), euro(EUR) og svenske kroner(SEK), og hvor mange norske kroner(NOK) hver av dem tilsvarer. Bruk listeindeksering til å hente ut hvor mange NOK en EUR er verdt. 
4. Bruk listeindeksering til å hente ut verdien av en USD. Regn ut hvor mye 20 USD tilsvarer i NOK. 
5. En indisk rupi(INR) tilsvarer 0.13 NOK. Legg til verdien for INR i valutaKurser. 
