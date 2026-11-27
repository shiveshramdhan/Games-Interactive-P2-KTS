# Games-Interactive-P2-KTS
Games & Interactive 2: User stories
Sprintplanning
Hieronder staan de verplichte user stories voor het project.

Als team bepalen jullie zelf in welke sprint je iedere user story uitvoert. Verdeel de user stories over de drie sprints en houd daarbij rekening met de technieken die je op dat moment hebt geleerd.

Aan het einde van Sprint 3 moeten alle verplichte user stories afgerond zijn.

Bonusfeatures
Kies als team 2 bonusfeatures uit de projecteisen.

Voor iedere gekozen feature schrijf je zelf een user story met acceptatiecriteria.

Je bepaalt als team in welke sprint je deze uitvoert. Aan het einde van Sprint 3 moeten beide bonusfeatures afgerond zijn.


User Story 1 – Startscherm
Als speler wil ik een startscherm zien, zodat ik een nieuw spel kan beginnen.

Acceptatiecriteria:

Het startscherm bevat een duidelijke titel en een startknop

De startknop begint een nieuwe speelsessie

Bij het starten worden de spelwaarden ingesteld op de beginwaarden

De speler komt terecht op het speelscherm


User Story 2 – Navigatie
Als speler wil ik tussen verschillende schermen kunnen navigeren, zodat ik gemakkelijk onderdelen van het spel kan bekijken.

Acceptatiecriteria:

Het spel gebruikt React Router

Er zijn aparte routes voor het startscherm, speelscherm en kaartenoverzicht

Iedere pagina heeft een eigen URL

Navigeren gebeurt zonder dat de volledige website opnieuw wordt geladen

De speler kan vanuit het kaartenoverzicht terug naar het speelscherm


User Story 3 – Speelveld
Als speler wil ik een overzichtelijk speelveld zien, zodat ik tijdens een gevecht kan zien wat er gebeurt.

Acceptatiecriteria:

Het speelveld toont de speler en de huidige vijand

De HP van de speler en vijand zijn zichtbaar

De energie en verdediging van de speler zijn zichtbaar

Er is een duidelijk herkenbare plek voor de handkaarten

Het speelveld heeft een consistente visuele stijl

Belangrijke informatie is duidelijk herkenbaar


User Story 4 – Handkaarten weergeven
Als speler wil ik mijn handkaarten kunnen bekijken, zodat ik weet welke kaarten ik tijdens mijn beurt kan spelen.

Acceptatiecriteria:

De kaarten in de hand worden weergegeven op het speelveld

Iedere kaart toont een naam, beschrijving en energiekosten

Iedere kaart wordt weergegeven met dezelfde herbruikbare Card-component

Kaartgegevens worden via props doorgegeven

De handkaarten worden dynamisch als lijst weergegeven

De hand bevat alleen de kaarten die op dat moment beschikbaar zijn


User Story 5 – Kaarten trekken
Als speler wil ik kaarten kunnen trekken, zodat ik nieuwe kaarten in mijn hand krijg.

Acceptatiecriteria:

De speler heeft een trekstapel met kaarten

Aan het begin van een gevecht worden handkaarten getrokken

Getrokken kaarten worden toegevoegd aan de hand

De getrokken kaarten verdwijnen uit de trekstapel

De hand en trekstapel worden bijgehouden in state

De nieuwe hand wordt direct zichtbaar op het speelveld


User Story 6 – Kaarten afleggen
Als speler wil ik gebruikte kaarten kunnen afleggen, zodat mijn hand en trekstapel correct worden beheerd.

Acceptatiecriteria:

Gespeelde kaarten verdwijnen uit de hand

Gespeelde kaarten worden toegevoegd aan een aflegstapel

Overgebleven handkaarten kunnen aan het einde van een beurt worden afgelegd

Wanneer de trekstapel leeg is, wordt de aflegstapel geschud en opnieuw gebruikt

De aflegstapel wordt bijgehouden in state

Kaarten gaan niet verloren bij het verplaatsen tussen de stapels


User Story 7 – Energie gebruiken

Als speler wil ik energie gebruiken om kaarten te spelen, zodat ik moet kiezen welke kaarten ik inzet.

Acceptatiecriteria:

De speler heeft een vaste hoeveelheid energie aan het begin van een beurt

Iedere kaart heeft eigen energiekosten

Bij het spelen van een kaart wordt de juiste hoeveelheid energie afgetrokken

Een kaart kan niet gespeeld worden wanneer de speler onvoldoende energie heeft

Kaarten die niet gespeeld kunnen worden zijn visueel herkenbaar

De beschikbare energie wordt bijgehouden in state

De energiewaarde wordt direct bijgewerkt


User Story 8 – Aanvalskaarten
Als speler wil ik aanvalskaarten kunnen spelen, zodat ik schade kan toebrengen aan een vijand.

Acceptatiecriteria:

Aanvalskaarten brengen schade toe aan de huidige vijand

De hoeveelheid schade is afhankelijk van de gespeelde kaart

De HP van de vijand wordt bijgehouden in state

De HP wordt direct bijgewerkt wanneer schade wordt toegebracht

HP kan niet lager worden dan 0

De speler krijgt zichtbare feedback wanneer de vijand schade ontvangt


User Story 9 – Verdedigingskaarten
Als speler wil ik verdedigingskaarten kunnen spelen, zodat ik mezelf kan beschermen tegen vijandelijke aanvallen.

Acceptatiecriteria:

Verdedigingskaarten voegen verdedigingspunten toe aan de speler

De hoeveelheid verdediging is afhankelijk van de gespeelde kaart

Verdedigingspunten worden bijgehouden in state

Verdedigingspunten worden zichtbaar weergegeven

Verdedigingspunten vangen schade op voordat HP wordt verminderd

De verdediging wordt direct bijgewerkt


User Story 10 – Speciale kaarten
Als speler wil ik kaarten met speciale effecten kunnen gebruiken, zodat ik verschillende strategieën kan toepassen.

Acceptatiecriteria:

Het spel bevat minimaal één kaart met een speciaal effect

Het effect verschilt van een gewone aanval of verdediging

Een speciaal effect kan bijvoorbeeld HP herstellen, energie aanvullen of extra kaarten trekken

Het effect wordt uitgevoerd wanneer de kaart wordt gespeeld

Het effect heeft direct invloed op de spelstatus

De speler krijgt zichtbare feedback bij het uitvoeren van het effect


User Story 11 – Beurt beëindigen
Als speler wil ik mijn beurt kunnen beëindigen, zodat de vijand aan de beurt komt.

Acceptatiecriteria:

Het speelveld bevat een knop om de beurt te beëindigen

Bij het beëindigen worden overgebleven handkaarten afgelegd

De spelstatus verandert naar de vijandelijke beurt

Tijdens de vijandelijke beurt kan de speler geen kaarten spelen

De interface maakt duidelijk dat de vijand aan de beurt is


User Story 12 – Nieuwe beurt starten
Als speler wil ik na de vijandelijke beurt opnieuw kaarten kunnen spelen, zodat het gevecht doorgaat.

Acceptatiecriteria:

Na de vijandelijke actie begint automatisch een nieuwe spelersbeurt, zolang het gevecht niet afgelopen is

De energie wordt aangevuld tot de beginwaarde

De speler trekt nieuwe handkaarten

De verdediging wordt gereset volgens de gekozen spelregels

De spelstatus verandert naar de spelersbeurt

De speler kan opnieuw kaarten spelen


User Story 13 – Verschillende vijanden
Als speler wil ik tegen verschillende vijanden kunnen vechten, zodat ieder gevecht een andere uitdaging biedt.

Acceptatiecriteria:

Het spel bevat minimaal 3 verschillende vijanden

Iedere vijand heeft een eigen naam, afbeelding en HP

Iedere vijand heeft minimaal één eigen aanval of eigenschap

Vijandgegevens worden opgeslagen als objecten in een array

Iedere vijand wordt weergegeven met dezelfde herbruikbare Enemy-component

Vijandgegevens worden via props doorgegeven


User Story 14 – Vijandelijke acties
Als speler wil ik kunnen zien welke actie een vijand gaat uitvoeren, zodat ik mijn strategie daarop kan aanpassen.

Acceptatiecriteria:

De volgende actie van de vijand wordt zichtbaar weergegeven

De vijand voert zijn actie uit tijdens de vijandelijke beurt

Een vijandelijke aanval vermindert de verdediging en/of HP van de speler

De hoeveelheid schade is afhankelijk van de vijand

De HP en verdediging van de speler worden na de actie bijgewerkt

De volgende actie van de vijand wordt bepaald en weergegeven

De speler krijgt zichtbare feedback bij een vijandelijke actie


User Story 15 – Gevecht winnen
Als speler wil ik een melding krijgen wanneer ik een vijand versla, zodat ik weet dat ik het gevecht heb gewonnen.

Acceptatiecriteria:

Een gevecht eindigt wanneer de HP van de vijand 0 bereikt

Bij een gewonnen gevecht verschijnt een duidelijke overwinningmelding

Na het winnen kunnen er geen kaarten meer worden gespeeld

Als er nog een gevecht volgt, kan de speler doorgaan naar de kaartbeloning

Als alle gevechten zijn voltooid, gaat de speler naar de eindoverwinning


User Story 16 – Gevecht verliezen
Als speler wil ik een verliesscherm zien wanneer mijn HP op is, zodat ik weet dat mijn speelsessie is afgelopen.

Acceptatiecriteria:

De speler verliest wanneer zijn HP 0 bereikt

Bij verlies verschijnt een duidelijk verliesscherm

Na verlies kunnen er geen kaarten meer worden gespeeld

De huidige speelsessie wordt beëindigd

De speler kan vanuit het verliesscherm terug naar het startscherm


User Story 17 – Kaartbeloning kiezen
Als speler wil ik na een gewonnen gevecht een nieuwe kaart kunnen kiezen, zodat ik mijn deck kan verbeteren.

Acceptatiecriteria:

Na een gewonnen gevecht, behalve het laatste, worden minimaal 2 kaarten als beloning aangeboden

De speler kan één kaart kiezen

De gekozen kaart wordt toegevoegd aan het deck

De nieuwe kaart blijft beschikbaar tijdens volgende gevechten

De speler krijgt een bevestiging van de gekozen kaart

De speler kan na het kiezen verdergaan


User Story 18 – Opeenvolgende gevechten
Als speler wil ik meerdere gevechten achter elkaar kunnen spelen, zodat ik steeds verder kan komen in het spel.

Acceptatiecriteria:

Het spel bevat minimaal 3 opeenvolgende gevechten

Na het kiezen van een kaartbeloning begint het volgende gevecht

Ieder gevecht bevat een andere vijand

De resterende HP van de speler blijft behouden

Het uitgebreide deck blijft behouden

Bij ieder nieuw gevecht worden de trekstapel, hand en aflegstapel voorbereid

De huidige voortgang wordt bijgehouden in state

De speler kan zien bij welk gevecht hij is


User Story 19 – Eindoverwinning
Als speler wil ik een eindoverwinning zien wanneer ik alle gevechten heb gewonnen, zodat ik weet dat ik het spel heb uitgespeeld.

Acceptatiecriteria:

Na het winnen van het derde gevecht verschijnt een eindoverwinningsscherm

Het scherm maakt duidelijk dat alle gevechten zijn voltooid

De speler ziet een duidelijke overwinningsmelding

Er wordt geen volgend gevecht gestart

De speler kan vanuit het eindscherm terug naar het startscherm


User Story 20 – Kaartenoverzicht
Als speler wil ik alle kaarten in mijn deck kunnen bekijken, zodat ik weet welke kaarten ik tijdens het spel kan tegenkomen.

Acceptatiecriteria:

Het spel bevat een apart kaartenoverzicht

Het deck bevat bij de start minimaal 10 verschillende speelkaarten, verdeeld over minimaal 3 soorten

Alle kaarten in het huidige deck worden weergegeven

Dezelfde Card-component wordt gebruikt als op het speelveld

Nieuwe kaarten die als beloning worden gekozen, verschijnen in het overzicht

De speler kan vanuit het kaartenoverzicht terug naar het speelscherm
