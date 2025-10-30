# nextjs
### User eXperience
Nextjs word vaak gebruikt voor wat complexere applicaties. Nexjs is gebouwd op react.
Doordat nextjs meer javascript gebruikt dan astro kan het langer duren om te laden. 
In mijn test zie je dit ook terug:
In mijn test haalde de nextjs inlogpagina een lighthouse performance van 68 en de pagina waar data uit supabase werd geladen een score van 76. Dit is lager dan dezelfde test in astro. Dit verschil komt doordat nextjs standaard meer javaScript inlaadt.

Navigeren tussen pagina's is bij nextjs wat directer. Dit gebeurd namelijk zonder te herladen. Hierdoor is het makkelijker om een gebruiker een soort app gevoel te geven.
### Developer eXperience
Nextjs heeft file-based routing, waardoor pagina's automatisch routes worden op basis van bestandnamen.
Ook kan je zelf bepalen hoe data wordt opgehaald wat weer invloed heeft op de ux en performance.
- Static site generator: pagina's worden 1 keer gegenereerd (blog, portflio etc).
- Server-side generator: pagina's worden bij elk nieuwe request opnieuw gegenereed (berichten, inlogstatus etc).

### Content Management eXperience
Ik gebruikte hier ook weer supabase. Dit was opzich niet heel lastig (met tutorial). Dit is hetzelfde bij astro.

<img width="2880" height="1624" alt="image" src="https://github.com/user-attachments/assets/47da2ec3-471b-4691-994a-6f69bdd21702" />

<img width="2880" height="1626" alt="image" src="https://github.com/user-attachments/assets/4a96c8e9-11dc-400c-9f59-3840a762ebd2" />
