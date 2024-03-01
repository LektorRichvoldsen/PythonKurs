# If-tester

## Oppgave 1
Lag en kodesnutt som tar inn alderen til brukeren med `input()`. Sjekk om brukeren er eldre eller yngre enn 16 år, og bruk en if-setning til å gi tilbakemelding til brukeren. 

## Oppgave 2
1. Bruk `random.randint(0,10)` og generer to tilfeldige tall mellom 0 og 10. Kall dem `tall1` og `tall2`. 
2. Oppdater koden sånn at brukeren får beskjed om hvorvidt tall1 er størst, tall2 er størst, eller om tall1 og tall2 er like. 
3. Utvid koden sånn at den gir beskjed om hvorvidt summen av tallene er større enn, mindre enn, eller lik 10. 

## Oppgave 3
I denne oppgaven skal du ta inn en alder og gi beskjed om hvorvidt man er barn, ungdom, voksen, eller gammel. Fordelingen er som følger:
- 0-12 år: Barn 
- 13-19 år: Ungdom
- 20-59 år: Voksen
- 60 år og eldre: Gammel

Du skal altså:
1. Ta inn alderen med `input()`.
2. Bruk if-setninger til å avgjøre hvilken kategori personen hører til. 
3. Bruk `print()` til å gi tilbakemelding til brukeren. 

## Oppgave 4
I denne oppgaven skal du lage en kodesnutt som sjekker om et år er skuddår. Et år er skuddår dersom:
- Det er delelig med 4, men **ikke** 100
- Det er delelig på 4, 100, **og** 400


For eksempel:
- 2024 er delelig på 4, men ikke 100. Derfor er det skuddår
- 2100 er delelig på 4 og 100, men ikke 400. Derfor er det ikke skuddår. 


**Hint:** For å sjekke om et tall er delelig på et annet, kan du bruke *heltallsdivisjon* med %-tegnet. Resultaret blir resten etter å ha delt et tall på et annet, uten å tillate desimaltall. Dersom et tall er delelig på et annet, blir dette resultatet 0. For eksempel:
- `9 % 3` gir resultatet 0, ettersom 9 er delelig på 3
- `9 % 2` gir ikke resultatet 0, ettersom 9 ikke er delelig på 2
