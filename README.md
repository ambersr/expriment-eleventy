# Expriment Eleventy
Een experiment met het CMS Eleventy om statische websites te bouwen en automatisch te deployen via GitHub Pages.

## Inhoudsopgave
- [Over dit project](#over-dit-project)
- [Projectstructuur](#projectstructuur)
- [Installatie en gebruik](#installatie-en-gebruik)

## Over dit project
Dit project is opgezet om te experimenteren met Eleventy. Het doel is om Markdown-content eenvoudig te kunnen beheren en automatisch te laten publiceren als een website.

- Markdown-bestanden in `src/` worden door Eleventy omgezet naar HTML in de `public/` map.
- Eleventy ondersteunt verschillende template engines zoals Nunjucks en Liquid.
- Continuous Deployment wordt geregeld via GitHub Actions: elke push naar de `main` branch bouwt de site en zet deze live op GitHub Pages.

## Installatie en gebruik

1. Clone de repository:
```
```bash
git clone https://github.com/ambersr/Expriment-Eleventy.git
```

2. Installeer independencies

```
npm install
```

3. Start de local server

```
npm start
```
