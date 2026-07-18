# PR screenshot assets

This orphan branch stores static screenshot assets that are referenced from
pull requests I have submitted to microsoft/flint-chart. Each image is a
side-by-side comparison render showing the same Flint `ChartAssemblyInput`
compiled through multiple rendering backends (Vega-Lite, ECharts, Chart.js,
and Plotly where applicable), so reviewers can verify visual parity without
checking out the branch and building the demo site locally.

## Usage

Images are embedded in PR bodies via raw URLs of the form:

```
https://raw.githubusercontent.com/zl190/flint-chart/assets/lollipop-screenshots/<file>.jpg
```

This branch is intentionally detached from the source tree: it contains no
code, is never merged, and exists only so the screenshots have a stable,
publicly readable home for the lifetime of the pull requests.

## Index

- `lollipop-3backends.jpg` — Lollipop Chart template PR (#59)
- `bump-3backends.jpg` — Bump Chart template PR
