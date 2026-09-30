# Europe's Battery Cost Gap

**Can Europe build a cost-competitive battery cell?** An interactive model that rebuilds the cost gap between European and Chinese lithium-ion cells (NMC811 and LFP) from public data, and splits it into the levers a gigafactory controls.

**Live page:** https://YOUR-USERNAME.github.io/battery-cost-gap/

## Key findings (2025 baseline)

- A European NMC811 cell costs about **$41/kWh more** than a best-in-class Chinese cell ($97 vs $57/kWh).
- **Scrap rate is the biggest single lever.** Cutting scrap from 20% to 5% is worth about $13/kWh; the entire electricity-price gap is worth about $1.50/kWh.
- At China's manufacturing efficiency, the gap narrows to about **$15/kWh**, in line with T&E's 2030 estimate of $14/kWh.
- A plant on Sweden's clean grid barely beats China's carbon footprint while scrap stays at 20%.

## What's inside

1. Cost bridge from a European to a Chinese cell, one lever at a time
2. Cost stack by region, cell to pack (China, US, EU)
3. Sensitivity of EU cell cost to scrap rate
4. Cradle-to-gate carbon footprint by plant location
5. EU value pools in 2030 by value-chain step

Sliders let you change the European plant's scrap rate, labour productivity, utilisation, capex, electricity price and energy use.

## Method

Cell cost = materials + scrap loss + labour + energy + capital recovery + overhead, per kWh of good cells. Capital is recovered at 8% over 10 years. The model is calibrated to BloombergNEF BattMan figures published by Transport & Environment (March 2026). Material cost splits, US parameters, wages and pack integration costs are my own assumptions, set to match those anchors. Full assumptions and sources are listed on the page.

## Sources

- Transport & Environment (2026), *The falling cost gap between EU and Chinese batteries*
- BloombergNEF (2025), *Lithium-ion battery price survey*
- IEA (2026), *Global EV Outlook 2026*
- Roland Berger (2025), *Two outlooks for the future of battery manufacturing in Europe*
- Ember (2025), grid carbon intensity data
- Transport & Environment (2023), *Battery carbon footprint position paper*

## Tech

A single self-contained HTML file with plain JavaScript and hand-drawn SVG charts. No build step and no dependencies apart from Google Fonts. Built with Claude Code.

---

Jaabili Tummala · Munich · [LinkedIn](https://www.linkedin.com/in/jaabili/)
