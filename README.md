# Experiment Eleventy

Dit project is een experiment met Eleventy en haalt content op via Github pages.  
Het doel is om een statische website te ontwikkelen en te onderzoeken hoe de User Experience, Developer Experience en Content Management Experience is van deze techstack.

## User Experience (UX)

- UX van deze stack is over het algemeen goed voor zowel desktop- als mobiele apparaten.  
- Toegankelijkheid is grotendeels op orde bij statische content; interactieve componenten vereisen extra aandacht (toetsenbordnavigatie, focus states, ARIA).  
- Pagina’s laden snel dankzij statische generatie en caching van assets.  
- Kleine verbeteringen mogelijk voor oudere apparaten of trage netwerken (CSS-fallbacks, minimale JS).  
- Geschikt voor content-gedreven websites met overzichtelijke structuur en snelle prestaties.  

[Uitgewerkt in Gist ](https://gist.github.com/ambersr/8a297c701fb0aa6a7c6f5ab4564c0c8e)

## Developer Experience (DX)

- Templates en includes zijn flexibel en herbruikbaar.  
- Statistische builds zijn betrouwbaar en eenvoudig te debuggen.  
- Minimale configuratie vereist, waardoor je snel kunt werken.  
- Voor interactieve componenten of moderne JS/CSS-features moet extra tooling worden toegevoegd (PostCSS, Vite, Webpack).  

[Uitgewerkt in Gist](https://gist.github.com/ambersr/1a159c588132643c27122d8d8773e3df)

## Content Management Experience (CMX)

- Content kan beheerd worden via Markdown, JSON/YAML of een headless CMS (Directus, Netlify CMS, etc.).  
- Beheerders kunnen content toevoegen of aanpassen zonder technische kennis van Eleventy of templating.  
- Voor standaard contentbeheer is het intuïtief en overzichtelijk.  
- Complexere workflows of realtime collaboration vereisen vaak een externe CMS-integratie.  
- De techstack stelt contentbeheerders in staat zelfstandig te werken, onafhankelijk van developers.  

[Uitgewerkt in Gist  ](https://gist.github.com/ambersr/67c7f3d116754619460ef167f9416e68)

## Algemene conclusie

Eleventy is ideaal voor content gedreven websites die snel, overzichtelijk en onderhoudsvriendelijk moeten zijn. Developers hebben een flexibele workflow terwijl contentbeheerders eenvoudig zelfstandig content kunnen beheren via Markdown of een headless CMS. Voor projecten met veel interactieve of realtime functies is Eleventy minder geschikt, omdat die functionaliteit handmatig toegevoegd moet worden.
