
# Backendutveckling och API:er #6: Debuggning & Loggning

👋 Se Linus Rudbecks föreläsning från 8 maj ✅ 


### Innehåll denna workshop:

* Förså syftet och varför man debuggar eller loggar sin backendapplikation. 
* Testa på olika verktyg för debugging och loggning 


# 👩🏽‍💻 Övning 1: Använd Morgon för loggning

Du ska använda Morgan som är ett middleware för expressapplikationer. 

1. Sätt upp Morgan på din nuvarande Node.js/Express/REST API app. [Dokumentation om middleware Morgan
](https://expressjs.com/en/resources/middleware/morgan.html). Loggningen som spottas ut ska du skriva till fil! 

2. Analysera loggfilen för att se om rätt statuskod skrivs ut till rätt tillfälle.

Enligt följande statuskoder: 

Create:

* 201 Created: Returneras när en ny resurs skapats
* 400 Bad Request: Returneras när begäran inte kan bearbetas.
* 500 Bad Request: Returneras när ett fel har skett på servern.

Read:

* 200 OK: Returneras när begäran bearbetas framgångsrikt.
* 404 Not Found: Returneras när begäran inte kan slutföras.
* 500 Bad Request: Returneras när ett fel har skett på servern

Update:

* 200 OK: Returneras när begäran bearbetas framgångsrikt.
* 400 Bad Request: Returneras när begäran inte kan bearbetas.
* 404 Not Found: Returneras när begäran inte kan slutföras.
* 500 Bad Request: Returneras när ett fel har skett på servern.

Delete:

*  204 No Content: Returneras när begäran bearbetas framgångsrikt.
* 404 Not Found: Returneras när begäran inte kan slutföras.
* 500 Bad Request: Returneras när ett fel har skett på servern.

# 👩🏽‍💻 Övning 2: Debugging i Express

Sätt upp debugging i Express för din applikation enligt:

[https://expressjs.com/en/guide/debugging.html]()

Testa denna debugger så att du kan få ut en komplett logg vid körning av en expressapplikation.


# 👩🏽‍💻 Övning 3: Debugging och breakpoints i VS Code med Auto Attach

Sätt upp Auto Attach i VS Code och prova att debugga i din applikation med att sätta breakpoints.

# 👩🏽‍💻 Övning 4: Prova Express Application Generator

Prova att sätt upp ett projekt med Express Application Generator. 

```npx express generator```

Vilka delar känner du igen sedan tidigare? Vilka är nya?


# 💬 Diskutera Debuggning & Loggning	

* Vilka olika delar/faser innehåller debugging?
* Diskutera de olika verktygen övning 1 - 3. Vad är syftet med varje, när vill man använda vilket, i vilken situation?


### Redovisning:
* Visa att du testat på de olika debug- & loggverktygen samt test express-generator och kan resonera om skillnaden mellan verktygen.

***Om du inte kan delta på workshopen, redovisar du ovanstående nästkommande workshop***


