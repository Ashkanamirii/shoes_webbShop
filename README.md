# shoes_webbShop
JAVA20, Databasteknik och Java, inlämningsuppgift 1.
OBS, läs hela uppgiften noga innan du börjar jobba på din lösning.
Du driver en webbshop som säljer skor på nätet och nu är det dags att göra den databas som
beskriver din verksamhet.
I databasen behöver du hålla koll på vilka skor som ska finnas i shoppen. Varje vara har en viss
storlek, färg, pris och är av ett visst märke. Du behöver också hålla reda på dina kunder och deras
beställningar. En beställning sker ett visst datum och kan innehålla flera varor och även flera varor av
samma typ. Dessutom ingår varorna i en eller flera kategorier (t.ex sportskor, promenadskor,
barnskor m.fl) så att de lätt kan presenteras på nätet.
Uppgiften är att skapa följande:
• Ett ER-diagram som beskriver din verksamhet. Samtliga entitetstyper, sambandstyper och
attribut ska finnas i diagrammet. (dokumentera detta i en PDF)
• En relationsmodell som beskriver databasen. (en text-fil går bra)
• Ett DDL-script som skapar upp databasen och fyller den med efterfrågat data. (en SQL-fil)
• Ett DML-script som besvarar frågorna nedan. (en SQL-fil)
Alla delar i uppgiften måste beskriva samma databas.
Datat som behövs i databasen är minst följande (välj det så att det passar med frågorna nedan):
• Minst 8 produkter
• Minst 5 kategorier
• Minst 5 kunder
• Minst 6 beställningar
Följande frågor skall kunna ställas mot din databas och returnera minst ett svar (du måste alltså ha
lagt in data som ”platsar” i frågorna):
• Lista antalet produkter per kategori. Listningen ska innehålla kategori-namn och antalet
produkter.
• Skapa en kundlista med den totala summan pengar som varje kund har handlat för. Kundens
för- och efternamn, samt det totala värdet som varje person har shoppats för, skall visas.
• Vilka kunder har köpt svarta sandaler i storlek 38 av märket Ecco? Lista deras namn.
• Skriv ut en lista på det totala beställningsvärdet per ort där beställningsvärdet är större än
1000 kr. Ortnamn och värde ska visas. (det måste finnas orter i databasen där det har
handlats för mindre än 1000 kr för att visa att frågan är korrekt formulerad)
• Skapa en topp-5 lista av de mest sålda produkterna.
• Vilken månad hade du den största försäljningen? (det måste finnas data som anger
försäljning för mer än en månad i databasen för att visa att frågan är korrekt formulerad)
Betygskriterier:
För att bli Godkänd (G) krävs följande:
• Ett ER-diagram som beskriver databasen och uppfyller alla krav i texten
• En relationsmodell som beskriver databasen och uppfyller alla krav i texten
• Ett DDL-script (SQL) som skapar upp databasen och datat. Primärnycklar och foreign keys
måste finnas med.
• Ett DML-script (SQL) med minst 4 av de SQL-frågor som ger de önskade sökningarna ovan.
För att bli Väl Godkänd (VG) måste lösningen uppfylla följande:
• Alla krav för att få G måste vara uppfyllda.
• Ett DML-script (SQL) med alla 6 av de SQL-frågor som ger de önskade sökningarna ovan.
• ER-modellen ska vara på 3NF. Om du medvetet väljer att frångå 3NF för någon eller några
tabeller ska detta motiveras med en bra anledning varför, i en kommentar.
• Det måste finnas minst ett index för en kolumn som känns relevant att söka på. Motivera
ditt val av kolumn i en kommentar.
• Visa att du förstår och kan använda dig av de olika varianter av referens-integritet som
MySQL erbjuder. Motivera dina val i kommentarer.
• Dessutom ska databasen utökas med funktionalitet som möjliggör att kunder kan sätta
betyg och kommentera på olika produkter. Till att börja med ska en kund kunna betygsätta
en vara med ett av följande betyg; ”Mycket nöjd”, ”Nöjd”, ”Ganska nöjd”, ”Missnöjd” men
det ska finnas möjlighet att senare lägga till fler betygssteg utan att ändra schemat i
databasen. Skapa de tabeller som behövs för att kunder ska kunna ge betyg och sätta
kommentarer på produkter.
All kod i denna uppgift ska skrivas manuellt – ingen automatgenererad kod får förekomma!
Pga att vi är så många i klassen får halva klassen redovisa för Sigrun, resten blir bedömda ”i tysthet”
utefter sina lösningar. Alla ska lämna in sina lösningar på Portalen, vare sig de demar för Sigrun
eller inte. Filerna ska lämnas senast morgonen den 9 februari, redovisningarna sker samma dag.
Denna uppgift görs enskilt eller i par. Lycka till!
