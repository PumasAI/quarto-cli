All changes included in 1.10:

## Engines

### `julia`

- Update Julia engine extension to v0.2.0 (QuartoNotebookRunner 0.18.1). Adds `keep-ipynb` support, `fig-format: retina`, `execute-dir`, shared worker processes, improved cache invalidation, and cached worker environments.

## Formats

### `typst`

- ([#14261](https://github.com/quarto-dev/quarto-cli/issues/14261)): Fix theorem/example block titles containing inline code producing invalid Typst markup when syntax highlighting is applied.

