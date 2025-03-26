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
