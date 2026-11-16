# Haze Watch

Single-page haze and weather monitor.

- Haze (PSI, PM2.5, PM10): National Environment Agency via data.gov.sg, Singapore only
- Weather for Singapore and 11 ASEAN cities: Open-Meteo

Static site, no build step. Both APIs are called from the browser and refresh every 10 minutes.

## Deploy to Vercel

1. Push this folder to a GitHub repository.
2. In Vercel, choose Add New > Project and import the repository.
3. Framework Preset: Other. Leave Build Command and Output Directory empty. Deploy.

## Run locally

Open `index.html` in a browser, or run `npx serve .`
