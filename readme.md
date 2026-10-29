# Oefeningen: Lussen (Loops)

## Niveau 1: Basis en Algoritmes

### Oefening 1: Even getallen filteren

Schrijf een lus die alle even getallen tussen 1 en 50 afdrukt in de console.

### Oefening 2: De tafel van 7

Schrijf een programma dat de tafel van 7 afdrukt (van `1 x 7 = 7` tot `10 x 7 = 70`).

### Oefening 3: Som van een reeks

Bereken met een lus de som van alle getallen van 1 tot en met 100 en toon het eindresultaat.

### Oefening 4: Aftellen voor lancering

Laat een lus aftellen van 10 naar 1 en druk daarna de melding `"Launch sequence initiated!"` af.

### Oefening 5: Gemiddelde berekenen van een array

Gegeven een array met behaalde testresultaten: `[14, 18, 8, 12, 15, 11]`. Gebruik een lus om het gemiddelde van deze cijfers te berekenen.

### Oefening 6: Wachtwoord controle (Validation loop)

Simuleer een inlogpoging met een `while`-lus. Blijf de gebruiker om een wachtwoord vragen totdat de invoer gelijk is aan `"Admin2026!"`. Toon bij succes `"Toegang verleend"`.
Je loopt door een array met wachtwoorden `["test123","123test","KarelKleintjes","Admin2026","Admin2025"]`

### Oefening 7: Welk getal is het grootst?

Gegeven een array van ongesorteerde getallen: `[45, 12, 89, 32, 97, 23]`. Zoek met behulp van een lus het hoogste getal op zonder gebruik te maken van ingebouwde sorteer- of `Math.max()` functies.

---

## Niveau 2: Array- en Dataverwerking

### Oefening 8: Zoeken in een gebruikerslijst

Gegeven een lijst met gebruikersnamen: `["jan", "pieter", "laura", "sam", "elena"]`. Doorloop de array en controleer of de naam `"sam"` aanwezig is. Geef de indexpositie terug als de naam gevonden is.

### Oefening 9: Voorraadcontrole (Stock check)

Je hebt een array met de stock van verschillende producten: `[12, 0, 5, 0, 18, 3]`. Tel met een lus hoeveel producten een voorraad van exact `0` hebben en geef een waarschuwing voor die items.

### Oefening 10: Prijzen inclusief btw

Gegeven een array met prijzen exclusief btw: `[10.0, 25.5, 40.0, 5.99]`. Maak een nieuwe array waarin elke prijs is verhoogd met 21% btw.

### Oefening 11: String omkeren

Schrijf een lus die een string (bijvoorbeeld `"Applicatie"`) van achter naar voor doorloopt en de omgekeerde string afdrukt (`"eitacilppA"`).

### Oefening 12: E-mailadressen valideren

Gegeven een lijst met e-mailadressen: `["test@school.be", "ongeldig.be", "user@domain.com", "fout@"]`. Lus door de lijst en druk enkel de adressen af die een `@`-teken én een punt `.` bevatten.

### Oefening 13: Gebruikersaccount statussen tellen

Gegeven een array van status-strings: `["active", "inactive", "active", "pending", "active", "inactive"]`. Tel hoeveel accounts de status `"active"` hebben.

### Oefening 14: Dubbele waarden opsporen

Gegeven een array van ID's: `[101, 102, 103, 102, 104, 101]`. Gebruik lussen om te bepalen welke ID's meer dan één keer voorkomen in de lijst.

---

## Niveau 3: Geavanceerde toepassingen en Nested Loops

### Oefening 15: Databaseresultaten formatteren (Master/Detail)

Gegeven een verzameling van rollen:

```javascript
const rollen = ["Admin", "Developer", "Tester"];
```

Gebruik een nested loop (nesting van lussen) om voor elke rol 3 fictieve testaccounts te genereren (bijv. `"Admin_1"`, `"Admin_2"`, ...).

### Oefening 16: Vaste kosten indexeren

Een jaarlijks serverabonnement kost momenteel €1500. De prijs stijgt elk jaar met 3%. Bereken met een lus de prijs voor elk jaar over een periode van 5 jaar en druk het overzicht af.

### Oefening 17: CSV-data parsen

Je krijgt een string binnen die lijkt op een CSV-export van een databank: `"Jan;Janssens;25,Pieter;Peeters;30,Laura;Lammens;22"`. Splits deze string en gebruik een lus om elke persoon netjes af te drukken als: `"Naam: Jan Janssens - Leeftijd: 25"`.

### Oefening 18: FizzBuzz voor ontwikkelaars

Doorloop de getallen van 1 tot 30.

- Als het getal deelbaar is door 3, druk af: `"App"`.
- Als het getal deelbaar is door 5, druk af: `"Data"`.
- Als het getal deelbaar is door zowel 3 als 5, druk af: `"AppData"`.
- In alle andere gevallen druk je gewoon het getal af.

### Oefening 19: Batch verwerking van records (Pagination/Chunking)

Je hebt een lijst van 23 database-records (voorgesteld als getallen 1 t.e.m. 23). Verwerk deze records met een lus in batches van maximaal 5 records per keer. Druk bij elke batch af: `"Batch gestart: records X tot Y"`.

### Oefening 20: Transactielog met stop-conditie

Gegeven een reeks financiële transacties: `[250, -50, -100, -400, 150, -50]`. Het startsaldo is €300. Lus door de transacties en pas het saldo aan. Stop de lus onmiddellijk (gebruik `break`) zodra het saldo onder €0 zou zakken, en geef een foutmelding met de index van de geweigerde transactie.
