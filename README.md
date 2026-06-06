<p align="center">
  <img src="./assets/hero.svg" width="100%" alt="Antonio Rico · Desarrollador web full-stack">
</p>

<p align="center">
  <a href="https://antonioricotech.com"><img src="./assets/pill-web.svg" height="40" alt="Sitio web"></a>&nbsp;
  <a href="https://wa.me/34634600286"><img src="./assets/pill-whatsapp.svg" height="40" alt="WhatsApp"></a>&nbsp;
  <a href="mailto:info@antonioricotech.com"><img src="./assets/pill-email.svg" height="40" alt="Email"></a>&nbsp;
  <a href="https://cal.com/antoniorico/agendar-llamada"><img src="./assets/pill-agenda.svg" height="40" alt="Reservar 10 min"></a>
</p>

<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="">
</p>

<img src="./assets/header-about.svg" width="200" alt="Sobre mí">

<p align="justify">
Hago que la tecnología trabaje para tu negocio. Soy <b>Antonio</b>, desarrollador <b>full-stack</b> con base en Barcelona: construyo sitios y aplicaciones web a medida que no solo lucen bien, sino que dan resultados. Mi herramienta principal es <b>Astro</b>, con la que creo sitios estáticos ultrarrápidos y optimizados para SEO; cuando el proyecto lo pide, sumo React, Next.js y TypeScript, con Node, Express y PostgreSQL en el back. Integro lo que un producto real necesita: pagos, IA y automatizaciones. Vengo del soporte técnico, así que entiendo los problemas del día a día y los explico sin jerga. Mi forma de trabajar es simple: presupuesto claro, sin letra pequeña y un resultado que habla por sí solo.
</p>

<p align="center">
  <img src="./assets/about-features.svg" width="700" alt="Desarrollo full-stack · Soporte y digitalización · De la idea al despliegue · Presencial y remoto · Rendimiento y SEO · Español e inglés">
</p>

<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="">
</p>

<img src="./assets/header-stack.svg" width="360" alt="Stack & herramientas">

<p align="center"><img src="./assets/label-stack.svg" height="18" alt="Stack"></p>

<p align="center">
  <img src="./assets/tech-astro.svg" height="40" alt="Astro">
  <img src="./assets/tech-nextjs.svg" height="40" alt="Next.js">
  <img src="./assets/tech-react.svg" height="40" alt="React">
  <img src="./assets/tech-typescript.svg" height="40" alt="TypeScript">
  <img src="./assets/tech-tailwind.svg" height="40" alt="Tailwind CSS">
  <img src="./assets/tech-nodejs.svg" height="40" alt="Node.js">
  <img src="./assets/tech-express.svg" height="40" alt="Express">
  <img src="./assets/tech-postgresql.svg" height="40" alt="PostgreSQL">
  <img src="./assets/tech-sqlite.svg" height="40" alt="SQLite">
  <img src="./assets/tech-supabase.svg" height="40" alt="Supabase">
  <img src="./assets/tech-stripe.svg" height="40" alt="Stripe">
  <img src="./assets/tech-openai.svg" height="40" alt="OpenAI / Anthropic">
  <img src="./assets/tech-shadcn.svg" height="40" alt="shadcn/ui">
  <img src="./assets/tech-s3.svg" height="40" alt="S3 / R2">
</p>

<p align="center"><img src="./assets/label-tools.svg" height="18" alt="Herramientas"></p>

<p align="center">
  <img src="./assets/tool-vscode.svg" height="40" alt="VS Code">
  <img src="./assets/tool-cursor.svg" height="40" alt="Cursor">
  <img src="./assets/tool-claude.svg" height="40" alt="Claude">
  <img src="./assets/tool-github.svg" height="40" alt="Git + GitHub">
  <img src="./assets/tool-docker.svg" height="40" alt="Docker">
  <img src="./assets/tool-githubactions.svg" height="40" alt="GitHub Actions">
  <img src="./assets/tool-onepassword.svg" height="40" alt="1Password / Doppler">
</p>

<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="">
</p>

<img src="./assets/header-projects.svg" width="235" alt="Proyectos">

### [places-api-lead-finder](https://github.com/4ntonio024/places-api-lead-finder)

Google Apps Script que convierte la **Places API (New)** en una lista filtrable de negocios locales **sin página web**, directamente en **Google Sheets**. No es un scraper: usa la API oficial y cuesta **~0 €/mes**.

![Google Apps Script](https://img.shields.io/badge/Google%20Apps%20Script-4285F4?logo=google&logoColor=white)
![Language: JavaScript](https://img.shields.io/badge/Language-JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Places API: New](https://img.shields.io/badge/Places%20API-New-34A853)
![Cost: ~$0/month](https://img.shields.io/badge/cost-~%240%2Fmonth-success)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

**Flujo general**

```mermaid
flowchart LR
  A["Google Places API (New)"] --> B["Google Apps Script (filtros y lógica)"]
  B --> C["Google Sheets (lista de leads)"]
```

**Cómo clasifica cada negocio**

```mermaid
flowchart LR
  A["Config sheet<br/>areas × niches"] --> B["Places API<br/>searchText (New)"]
  B --> C{"websiteUri?"}
  C -- "empty" --> D["NO WEBSITE"]
  C -- "social / builder" --> E["WEAK WEBSITE"]
  C -- "real domain" --> F["HAS WEBSITE<br/>(skipped by default)"]
  D --> G["Leads sheet"]
  E --> G
```

<details>
<summary><b>Cómo funciona y por qué es útil</b></summary>
<br>
<ul>
<li><b>Busca</b> negocios por tipo y zona con la Places API oficial de Google.</li>
<li><b>Filtra</b> automáticamente los que no tienen web, justo los que más la necesitan.</li>
<li><b>Vuelca</b> los resultados en Google Sheets: nombre, teléfono, dirección y más.</li>
<li><b>Coste</b>: prácticamente 0 € al mes gracias a la capa gratuita de la API.</li>
<li><b>Caso de uso</b>: prospección comercial para quien ofrece desarrollo web o servicios digitales.</li>
</ul>
</details>

<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="">
</p>

<p align="center"><img src="./assets/label-it.svg" height="16" alt="También · IT y Soporte"></p>

<p align="center"><sub>Ordenadores a medida · Home labs · Redes y servidores · Mantenimiento y soporte · <a href="https://antonioricotech.com">antonioricotech.com</a></sub></p>

<p align="center">
  <img src="./assets/divider.svg" width="100%" alt="">
</p>

<img src="./assets/header-contact.svg" width="200" alt="Contacto">

¿Tienes una idea, un proyecto o algo que mejorar? Cuéntamelo y te doy un presupuesto claro, sin compromiso.

<p align="center">
  <a href="https://antonioricotech.com"><img src="./assets/pill-web.svg" height="40" alt="Sitio web"></a>&nbsp;
  <a href="https://wa.me/34634600286"><img src="./assets/pill-whatsapp.svg" height="40" alt="WhatsApp"></a>&nbsp;
  <a href="mailto:info@antonioricotech.com"><img src="./assets/pill-email.svg" height="40" alt="Email"></a>&nbsp;
  <a href="https://cal.com/antoniorico/agendar-llamada"><img src="./assets/pill-agenda.svg" height="40" alt="Reservar 10 min"></a>
</p>

<p align="center"><sub>Tecnología en tus manos, sin los costes de una multinacional.</sub></p>
