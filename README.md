# Experiment Eleventy

Dit project is een experiment met Eleventy en haalt content op via Github pages.  
Het doel is om een statische website te ontwikkelen en te onderzoeken hoe de User Experience, Developer Experience en Content Management Experience is van deze techstack.

## User Experience (UX)

- UX van deze stack is over het algemeen goed voor zowel desktop als telefoon en ipad.
- Toegankelijkheid werkt over het algemeen zoals gebruikelijk. Maak gebruik van focus states en (als het moet) ARIA labels.  
- Pagina’s laden snel dankzij statische generatie.  
- Kleine verbeteringen mogelijk voor oudere apparaten of trage netwerken (CSS fallbacks en minimale JS gebruiken).  
- Geschikt voor content gedreven websites met overzichtelijke structuur.

[Uitgewerkt in Gist ](https://gist.github.com/ambersr/8a297c701fb0aa6a7c6f5ab4564c0c8e)

## Developer Experience (DX)

- Templates zijn flexibel en herbruikbaar.  
- Vooraf gegenereerde pagina’s zijn eenvoudig te debuggen.  
- Vereist weinig instellingen waardoor je snel aan de slag kunt met het project.

[Uitgewerkt in Gist](https://gist.github.com/ambersr/1a159c588132643c27122d8d8773e3df)

## Content Management Experience (CMX)

- Content kan opgehaald worden via Markdown, JSON of een headless CMS (Directus, Netlify CMS, etc.).  
- Beheerders kunnen content toevoegen of aanpassen zonder technische kennis van Eleventy.
- Voor standaard contentbeheer is het gemakkelijk te begrijpen en overzichtelijk.  
- Contentbeheerders kunnen zelfstandig werken onafhankelijk van de developers.  

[Uitgewerkt in Gist  ](https://gist.github.com/ambersr/67c7f3d116754619460ef167f9416e68)

## Conclusie gebruik techstack

Eleventy is ideaal voor content gedreven websites die snel, overzichtelijk en onderhoudsvriendelijk moeten zijn. Developers hebben een flexibele workflow. Contentbeheerders kunnen eenvoudig en zelfstandig content beheren via Markdown of een headless CMS. Voor websites die veel interactieve elementen bevatten is Eleventy minder handig omdat zulke functies niet standaard aanwezig zijn en handmatig toegevoegd moeten worden.
