# Generalized Maximum Entropy: When and Why You Need It — code

Code reproducing the numerical results of Ferro, Pos & Somazzi,
*Generalized Maximum Entropy: When and Why You Need It*.

## Contents
- `numerical_example.ipynb` — Figure 2 (single-sample fit: histogram +
  inferred distribution, and the log-likelihood contour around the MLE).
- `figures_3_and_4.ipynb` — Figure 3 (sensitivity of the inferred parameters
  to n, N, d) and Figure 4 (parameter recovery across generating q).

## Requirements
Python 3.9+ with the packages in `requirements.txt`:

    pip install -r requirements.txt

## Reproducing the figures
Open each notebook and run all cells. Figures are written as both `.pdf` and
`.png`. In `figures_3_and_4.ipynb`, `R_FIG3` and `R_FIG4` set the number of
repetitions; they are 300 and 200 in the paper, and can be lowered for a quick
preview.
