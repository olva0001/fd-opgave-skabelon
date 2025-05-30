# Opgaveskabelon til Frontend Design tema på Frontend-valgfaget

Se opgavebeskrivelsen på Fronter.

## Medfølgende API

Der medfølger en simpel API, som du kan bruge til at hente data til din opgave. Det er ikke et krav til opgaven, men det kan gøre det nemmere og hurtigere at få tekst og billeder ind i dit projekt.

Dokumentationen til API'et finder du på: [https://frontend-design-theme.netlify.app/](https://frontend-design-theme.netlify.app/).

Her er et eksempel på, hvordan du kan hente data fra API'et:

```astro
const employeesData = await fetch(
  "https://frontend-design-theme.netlify.app/api/employees"
).then((response) => response.json());

console.log(employeesData);
```

## Herunder deler jeg mine egne tanker under opgave forløbet:

Hero: Hero delen af hjemmesiden var enormt frustrerende for mig. Jeg brugte rigtig lang tid på at finde ud af hvordan grid skulle sættes op, og jeg havde ligeledes frustrationer med at få billederne til at vise sig - hvilket skyldes forkert mappe struktur. Så lærte jeg det...
Efter at jeg ligesom fik layoutet på plads, var opgaven ikke så uoverskuelig igen. Men det tog lidt tid at få styr på det hele, og det er klart den sværeste opgave jeg har mødt på studiet indtil videre.

Jeg har slet ikke kunne få billede til at fungere på netlify, så når i kigger der, så virker mange af dem altså ikke, og jeg ved ikke hvorfor. De virker fint på local server, som i også vil se i mit GitHub repository...

Specifikke kodestykker jeg gerne vil fremhæve:

- Questions.astro // Her er det vidst første gang at jeg prøver at lave javascript inde i en komponent, så det føltes meget godt.
- Casestudytext.astro // Jeg syntes selv at den mest tekst-tunge del af sitet ser forholdsvis nem ud at læse, så der er jeg stolt af mine line heights, fonts etc.

CSS: Stort set al min CSS er komponent specifikt - det er bare mest overskueligt syntes jeg. Det er kun font størrelse jeg har som variable, og så ligger mit grid i global styles også, men det er det.
