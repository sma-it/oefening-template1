# Oefenreeksen Maken
Elke reeks oefeningen krijgt zijn eigen repository. Op die manier kunnen de leerlingen de oefening dadelijk openen in visual studio. Met deze stappen maak je een nieuwe oefenreeks.

* Maak een nieuw repository binnen sma-it. Om alles overzichtelijk te houden begint de naam best met 'oefening-' met daarna een beschrijvende naam voor de oefening. Bij de opties kan je de README.md aanduiden en een .gitIgnore file toevoegen voor visual studio. Dat laatste is belangrijk: zo komen gecompileerde bestanden niet in het repository terecht.

* Clone repository: dit kan via github desktop of visual studio. Download de zip file van dit repository [hier](https://github.com/sma-it/oefening-template1/archive/master.zip) en plaats de directory 'oefening' in je nieuwe repository.

* Open de solution file oefening/oefening.sln in visual studio en schrijf de code voor de oefening en de testen.

* Om je testen te controleren open je de test explorer (test => Windows => Test Explorer). Je testen worden automatisch geladen na de eerste compilatie.

* Als de oefening klaar is, dan open je in visual studio de team explorer. Je klikt bovenaan om het huisje, en kiest changes. Daar doe je een commit (omschrijving verplicht) en vervolgens krijg je de suggestie om een sync uit te voeren. Klik op sync en dan op push.

# Hoe leerlingen een oefening openen
We kunnen in de cursus een directe link zetten om de oefening te openen in Visual Studio. Daar kiezen de leerlingen een directory om de oefening op te slaan en zo maken ze een lokale kopie. (Er zijn wellicht de eerste keer wat afspraken nodig zodat de leerlingen elk een eigen directory gebruiken.)

# Opmerkingen
De template gebruikt drie nuget packages om testen te kunnen uitvoeren: NUnit, NUnit3TestAdapter en NUnitLite. Als alles goed gaat, dan worden deze packages automatisch geladen bij het openen van het project. Dit kan wel even duren wanneer de packages nog niet op de computer geinstalleerd zijn. (Enkel bij de eerste oefening dus).  

