## React test api

#### API endpoints;

<ul>
<li> Users: <code>https://jsonplaceholder.typicode.com/users </code> </li>
<li>Albums <code>https://jsonplaceholder.typicode.com/albums </code> </li>
<li>photos: <code>https://jsonplaceholder.typicode.com/photos </code> </li>
</ul>

### Beskrivelse

For denne opgave skal der laves et UI, ved at bruge de forskellige endpoints, der er listet for ovenfor. Nedenfor er et eksempel på hvordan det User Interfacet skal se ud

#### Hovedside <code> / </code>

På hovedsiden skal alle brugere renderes. Der skal implementeres pagination, så UI'et kan vise henholdsvise 10, 20 og 30 brugere af gangen. Hovedsiden skal vise brugerens først billede <i>(kan fås i gennem photos endpoint, ved at bruger userId). </i> Samt brugerens navn, addresse og website.

Der skal følgende sortering og grupperings muligheder:

<ul>
<li> Sorting per firma (alle bruger skal sorteres efter firma) </li>
<li> Sortering i alfabetisk rækkefølge (foranvn og derefter efternavn) </li>
<li> Søge funktion, der kan søge efter både fornavn og efternavn  </li>
</ul>
#### Profil side <code>/profile/:userId </code>

På profisiden skal det kunne være muligt at se helæe brugerens profil. Her skal al information vises. Det skal samtidig være muligt at navigere igennem alle brugerens albums og billeder inde i hvert album. Det skal være muligt at like brugerens profilbillede, hvilket viser et hjerte / thumbs up ud fra hvert billede (Dat skal persistes I localstorage, redux eller anden metode efter dit valg).

#### UI / Design

Der er ingen krav i forhold til design eller UI. Du er vellkommen til at style applikationen som du har lyst til. Benyt dig geren af UI libraries som Chakra eller Material UI, eller lav din egen CSS, hvis du føler dig mere kreativ :)

<b> God fornøjelse og happy coding 🖥️ </b>
