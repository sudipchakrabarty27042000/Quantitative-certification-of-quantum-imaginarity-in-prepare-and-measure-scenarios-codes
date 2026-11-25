# Quantitative certification of quantum imaginarity in prepare-and-measure scenarios

Supplementary code for the article

> S. Chakrabarty, *Quantitative certification of quantum imaginarity in prepare-and-measure scenarios*.

The Jupyter notebook `imaginarity_supplementary.ipynb` reproduces every numerical value, table and figure of the article, in the order of the paper. It is saved with all outputs and figures, so it can be read directly on GitHub without running it.

## Contents

| File | Description |
|------|-------------|
| `imaginarity_supplementary.ipynb` | The notebook, executed, with all outputs and figures |
| `figs/fig1.pdf` ... `figs/fig4.pdf` | The four figures of the article, as produced by the notebook |
| `requirements.txt` | Python packages needed to rerun the notebook |

## Running the notebook

```bash
pip install -r requirements.txt
jupyter notebook imaginarity_supplementary.ipynb
```

A full run takes about 10 to 20 minutes on a laptop. Random seeds are fixed, so the printed numbers are reproducible. The figures use LaTeX with the `txfonts` package when a LaTeX installation is found, and otherwise fall back to matplotlib's built-in Times-like fonts.

The notebook states at its beginning which results are proven analytically in the article and which rest on numerical searches.

## Contact

Sudip Chakrabarty, S. N. Bose National Centre for Basic Sciences, Kolkata, India (sudip27042000@gmail.com)
