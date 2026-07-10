# Vibe Coding Samples — Digital History Tools

NER visualizations of Putin's presidential article **"On the Historical Unity of Russians and Ukrainians"** (July 2021).

## Disclaimer
The NER data set is based on an article that represents an attempt by the author to politically instrumentalize the shared history between Ukraine and Russia. The content of the article should not be taken at face values but reflected critically. To fully understand the visualizations refer to tutorials published on ym personal website: johannajaschik.com

## Files

- **`index.html`** / **`ner_article46_viz.html`** — Interactive Chart.js visualization: entity type donut chart, entity count bar chart, top 20 entities ranked by mention count. Hover for tooltips.
- **`ner_article46_data_humanism.html`** — Data Humanism visualization (inspired by Giorgia Lupi): hand-drawn aesthetic, warm paper-toned background, each entity mention as an individual dot mark organized into five thematic clusters.

## What's visualized

- **426 named entity mentions** from Putin's essay
- **176 distinct entities** (persons, places, organizations)
- **Thematic clusters**: The Contested Present, Historical States & Empires, Wider Region, Persons, Organizations

## Source

Article 46 from a corpus of 52 Kremlin.ru presidential articles (2000–2024).
NER performed using DeepSeek V4 Flash via OpenRouter.
