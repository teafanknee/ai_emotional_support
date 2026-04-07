# AI Emotional Support — Survey Takeaways

A single-page data visualization report summarizing survey findings on how people use AI for emotional support (n=7, April 2026).

## File structure

```
ai_emotional_support_takeaways (1).html   # The entire report — one self-contained HTML file
```

Everything lives in one file:

| Section | What it is | Where in the file |
|---|---|---|
| Styles | CSS variables, layout, responsive breakpoints | `<style>` block, lines 9–254 |
| Header | Title, eyebrow label, date/sample metadata | `.header` div, ~line 259 |
| At a Glance | 4 key metric cards (n, %, avg scores) | `.metrics` div, ~line 272 |
| Key Insight callout | Highlighted pull quote | `.insight` div, ~line 291 |
| Usage patterns charts | Doughnut (frequency) + bar (topics) via Chart.js | `.chart-grid` div, ~line 296 |
| Emotional ratings | Horizontal bar rows for 6 avg. scores | `.ratings` div, ~line 320 |
| Quote cards | Verbatim responses, color-coded by theme | `.quotes-section` divs, ~lines 356–389 |
| Chart logic | Chart.js initialization for both charts | `<script>` block, ~lines 398–451 |

## How to view locally

Just open the HTML file in any browser — no server or dependencies needed. All fonts load from Google Fonts and the chart library loads from a CDN.


