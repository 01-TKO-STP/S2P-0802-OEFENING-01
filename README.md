# S2P-0802-OEFENING-01

**Inleiding**

Laten we beginnen met een eenvoudig voorbeeld...  We halen er het woordje **AETYRZ** bij.  Dit woordje is op dezelfde manier verstrengeld als in de opdracht, alleen is het heel wat korter !

- eerste letter: A
- laatste letter: Z
- tweede letter: E
- voorlaatste letter: R
- derde letter: T
- derdelaatste letter: Y

resultaat: AZERTY

Dit moeten we nu vertalen naar Python-code.

We starten met de string en de omgekeerd string

```python
AETYRZ  
ZRYTEA
```

We houden de eerste drie karakters van elke string over

```python
AET  
ZRY
```

Doorloop nu de drie kolommen rij-na-rij en je bekomt AZERTY.

**Opdracht**

Voor deze opdracht maak je gebruik van de tekst in het tekstbestand 'geheimbericht.txt' met volgende inhoud.

```textile
TEMNSEYO IL AKSLWYLSF RTII H
```

De string bevat de titel van een bekende sketch van '*Monty Python's Flying Circus*'.  Aan jou om de string te ontrafelen en de naam van de sketch te ontdekken.

Maak een Python-script waarmee je de inhoud van dit tekstbestand inleest.  Om de tekst te ontcijferen moet je de letters in een andere volgorde zetten.  Je gaat als volgt tewerk:

- eerste letter titel = eerste karakter string
- tweede letter titel = laatste karakter string
- derde letter titel = tweede karakter string
- vierde letter titel = voorlaatste karakter string
- vijfde letter titel = derde karakter string
- zesde letter titel = derde laatste karakters tring
- ...  ga zo door tot je alle karakters uit de string hebt gebruikt ...

Schrijf het resultaat weg naar het bestand 'ontcijfertbericht.txt'.

Het ligt voor de hand dat er niet één maar vele Python-scripts mogelijk zijn die de juiste oplossing leveren.  Geef de voorkeur aan  een korte, efficiënte script, misschien als tweede of derde versie ! Maak gebruik van de string-functies.
