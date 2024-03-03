# Innhold
[Variabler](#variabler)
[If-tester](#bare-if)
[Løkker](#løkker)

# Variabler

```python 
tekst = "Her er det tekst"
tall = 12
desimaltall = 3.14
boolsk_variabel = True
```
# If-test
## bare if
```python 
alder = 20

if(alder > 17 ):
    print("Du er gammel nok til å kjøre bil")

# alternativ med større eller lik 18
if(alder >= 18 ):
    print("Du er gammel nok til å kjøre bil")
```
## if med else

```python 
alder = 15

if(alder > 17 ):
    print("Du er gammel nok til å kjøre bil")
else:
    print("Du må nok sykle enn så lenge")

```
## if med elif (if else) og else
```python 
alder = 15

if(alder > 17 ):
    print("Du er gammel nok til å kjøre bil")
elif(alder > 15):
    print("Du er gammel nok til å kjøre moped")
else:
    print("Du må nok sykle enn så lenge")
```
## Eksempel med flere elif-er
```python 
himmelretning = "E"

if(himmelretning == "N" or himmelretning == "n"):
    print("Du går nordover")
elif(himmelretning == "S" or himmelretning == "s"):
    print("Du går sørover")
elif(himmelretning == "E" or himmelretning == "e"):
    print("Du går østover")
elif(himmelretning == "W" or himmelretning == "w"):
    print("Du går vestover")
else:
    print("Du har valgt en ugyldig himmelretning. Har du gått oppover eller nedover, kanskje?")
```
# Løkker

Bla bla bla
