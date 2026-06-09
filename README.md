# Friends — Éxito de la Serie y Curiosidades / Show Success & Behind-the-Scenes Data

> 🇪🇸 [Español](#español) · 🇬🇧 [English](#english)

---

## Español

### Descripción

Análisis visual de una de las series más exitosas de la historia de la televisión. El proyecto combina datos reales de audiencia, dirección y producción con datasets generados mediante IA generativa para responder preguntas que las fuentes oficiales no pueden: ¿quién gasta más en café? ¿cuánto tiempo pasan los personajes en el Central Perk? ¿quién dice más veces su frase icónica?

El resultado son cuatro dashboards interactivos en Tableau Public, con una paleta de color personalizada inspirada en el universo visual de la serie.

🔗 [Ver proyecto en Tableau Public](https://public.tableau.com/app/profile/micaela.lafratta/viz/Friends_Exitoserieycuriosidades/CentralPerk?publish=yes)

---

### Dashboards

| Dashboard | Contenido |
|---|---|
| **Central Perk** | Gasto en café por personaje, tiempo en el local, Cafémetro |
| **Éxito de la serie** | KPIs, top directores por episodios y rating, visualizaciones por episodio |
| **¿Quién habla más?** | Líneas por personaje, nube de palabras, treemaps por frase icónica |
| **Estrellas invitadas** | Tabla de cameos, top 5 apariciones, tipos de cameo |

---

### Origen de los datos

| Dataset | Fuente |
|---|---|
| Episodios, directores, rating IMDb | Datos reales (IMDb / fuentes públicas) |
| Audiencia por episodio (millones) | Datos reales (Nielsen) |
| Gasto en café por personaje | Generado con IA generativa a partir de fuentes reales |
| Tiempo en el Central Perk | Generado con IA generativa a partir de fuentes reales |
| Apariciones de estrellas invitadas | Generado con IA generativa a partir de fuentes reales |

> Los datasets generados con IA fueron construidos recopilando información real dispersa en múltiples fuentes y estructurándola en CSV. El criterio editorial — qué datos son razonables, verificables o inferibles — forma parte del proceso.

---

### Decisiones técnicas destacadas

- **Medidas calculadas en Tableau** para filtrar y cuantificar frases icónicas específicas por personaje y temporada.
- **Filtros visuales** en el panel de frases célebres: la foto de cada actor funciona como selector interactivo.
- **Paleta personalizada** con tonos café, ocre y verde oscuro del Central Perk, con borgoña como acento — consistente en los cuatro dashboards.
- **Custom markers** en el gráfico de barras de Central Perk: el logo de la cafetería reemplaza las barras convencionales.

---

### Stack

`Tableau Public` · `IA Generativa (generación de datasets)` · `Paleta de color personalizada`

---

## English

### Description

Visual analysis of one of the most successful shows in television history. The project combines real viewership, production, and directing data with AI-generated datasets to answer questions official sources can't: who spends the most on coffee? How long do the characters actually spend at Central Perk? Who says their iconic catchphrase the most?

The result is four interactive Tableau Public dashboards with a custom color palette inspired by the show's visual world.

🔗 [View on Tableau Public](https://public.tableau.com/app/profile/micaela.lafratta/viz/Friends_Exitoserieycuriosidades/CentralPerk?publish=yes)

---

### Dashboards

| Dashboard | Content |
|---|---|
| **Central Perk** | Coffee spending per character, time at the coffee shop, Coffeemeter |
| **Show Success** | KPIs, top directors by episode count and rating, viewership per episode |
| **Who Talks the Most?** | Lines per character, word cloud, treemaps by iconic phrase |
| **Guest Stars** | Full cameo table, top 5 appearances, cameo type breakdown |

---

### Data sources

| Dataset | Source |
|---|---|
| Episodes, directors, IMDb rating | Real data (IMDb / public sources) |
| Viewership per episode (millions) | Real data (Nielsen) |
| Coffee spending per character | AI-generated from real sources |
| Time spent at Central Perk | AI-generated from real sources |
| Guest star appearances | AI-generated from real sources |

> AI-generated datasets were built by gathering real but scattered information from multiple sources and structuring it into CSVs. Editorial judgment — determining what data is reasonable, verifiable, or defensibly inferred — is part of the process.

---

### Notable technical decisions

- **Calculated measures in Tableau** to filter and quantify specific iconic phrases by character and season.
- **Visual filters** in the catchphrase panel: each actor's photo works as an interactive selector.
- **Custom color palette** using warm browns, ochre, and Central Perk dark green with burgundy as an accent — consistent across all four dashboards.
- **Custom markers** on the Central Perk bar chart: the coffee shop logo replaces conventional bars.

---

### Stack

`Tableau Public` · `Generative AI (dataset generation)` · `Custom Color Palette`

---

*Proyecto desarrollado como parte de un portfolio de análisis de datos y visualización. / Developed as part of a data analysis and visualization portfolio. Proyecto realizado conjuntamente con Mayka Durán*
