# Innhold
- [Variabler](#variabler)
- [If-tester](#bare-if)
- [Løkker](#løkker)
- [Funksjoner](#funksjoner)
- [Lister/arrays](#lister)

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
## While-løkker
```python 
antall_runder = 3

while(antall_runder > 0):
    print("Nå er det " +  str(antall_runder) + " runder igjen av løkka")
    antall_runder = antall_runder - 1
```
```python 
number_of_bottles = 99

while(number_of_bottles > 0):
    print(f"{number_of_bottles} bottles of beer on the wall, {number_of_bottles} bottles of beer.")
    number_of_bottles = number_of_bottles-1
    print(f"Take one down and pass it around, {number_of_bottles} bottles of beer on the wall.")

print("No more bottles of beer on the wall, no more bottles of beer.")
print("Go to the store and buy some more, 99 bottles of beer on the wall.")
```
## For-løkker
```python 
for tall in range(6):
  print(tall)
```
```python 
frukt_liste = ["eple", "banan", "kiwi"]
for frukt in frukt_liste:
  print(frukt)
```
```python 
for bokstav in "Hele denne setningen.":
  print(bokstav)
```
# Funksjoner

## Enkel funksjon uten returverdi og uten parameter/input
```python 
def enkel_funksjon():
    print("Nå kjører jeg")

enkel_funksjon()
```
## Funksjon med parameter/input (uten returverdi)
```python 
def funksjon_med_parameter(parameter):
    print("Nå skriver jeg ut argumentet som blir sendt inn: " + parameter)

funksjon_med_parameter("JEG ER ET ARGUMENT")
```
## Funksjon med returverdi (uten parameter)
```python 
def funksjon_med_returverdi():
    return "Jeg sendes tilbake. Putt meg i en variabel."

ta_imot_svar = funksjon_med_returverdi()
print(ta_imot_svar)
```
## Funksjon med parameter/input og returverdi
```python 
def funksjon_som_dobler_et_tall(tall):
    dobbelt = 2*tall
    return(dobbelt)

svar = funksjon_som_dobler_et_tall(4)
print(svar)
```
# Lister
