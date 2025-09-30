🌿 Leverkost Dashboard
Välkommen till Leverkost Dashboard – ett personligt verktyg för att spåra kost, hydrering, aktivitet och hälsomått med fokus på leverhälsa. Applikationen är utformad för att hjälpa användare att visualisera hur deras dagliga val påverkar deras närings- och hälsomål.
Funktioner
* Flerspråkig UI: Stödjer Svenska (SV), Engelska (EN), Spanska (ES) och Italienska (IT).
* Måltidsloggning: Lägg till måltider baserat på näringsvärden (Protein, Fett, Kolhydrater, Kalorier) och markera om de är Levervänliga.
* Leverhälsorapport: Få lokaliserad, automatisk feedback baserat på andelen levervänliga kalorier i din dagliga kost.
* Aktivitets- och Hydreringstracking: Spåra vattenintag och träningsminuter mot anpassade dagliga mål.
* Journal och Mätvärden:
   * Skriv journalanteckningar och logga dagligt humör.
   * Spåra medicinska journalvärden (t.ex. ALAT, Kolesterol) och se trender över tid i diagram.
* Dataöversikt och Diagram: Se kalorifördelning, makronutrientfördelning och 7-dagarstrender för kaloriintag och aktivitet.
* Datasäkerhet: Exportera, importera och nollställ all data via localStorage-baserade verktyg.
* Administratörslås: Lås upp farliga funktioner (Dataverktyg och Lägg till eget livsmedel) med ett lösenord (admin).
Tekniker
Detta är en helt fristående (standalone) webbapplikation.
* HTML, CSS (Custom CSS): För struktur och design.
* JavaScript (Vanilla JS): För all applikationslogik, dataläsning/skrivning och DOM-manipulation.
* Chart.js: Används för att rendera alla diagram och visualiseringar av data.
* localStorage: Används som databas för att spara måltider, journaler och inställningar lokalt i webbläsaren.
Så här använder du applikationen
1. Växla Språk: Använd rullistan högst upp för att ändra UI-språket (SV/EN/ES/IT).
2. Välj Datum: Använd kalendern i sidomenyn för att välja vilken dag du vill logga data för.
3. Sätt Mål (Översikt): På fliken Översikt anger du dina dagliga kalorimål, makromål samt mål för vattenintag och aktivitet. Klicka på Spara Mål för att aktivera spårningen.
4. Logga Mat (Måltider): Använd Måltider-fliken för att logga livsmedel. Se omedelbart näringsförhandsgranskningen innan du lägger till.
Datalåsning och Verktyg
För att skydda mot oavsiktlig radering/ändring är funktionerna för att Lägga till eget livsmedel och Dataverktyg låsta som standard:
* Lås upp: Klicka på "Låst"-knappen i sidomenyn och ange lösenordet admin.
* Dataexport: Använd knappen Exportera data för att ladda ner en JSON-backupfil. Denna fil kan användas för att flytta din data till en annan enhet eller för säkerhetskopiering.
Denna app är utvecklad som ett personligt verktyg. Den utgör inte medicinsk rådgivning. Rådgör alltid med läkare eller specialist vid hälsoproblem.
