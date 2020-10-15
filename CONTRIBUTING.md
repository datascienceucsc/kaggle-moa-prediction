# Contribution guidelines 

## Code formatting

Code should be formatted using [black](https://black.readthedocs.io/en/stable/?badge=stable).
Github Actions continuous integration will automatically formats your code when you push.

## Typing

We encourage you to add [type annotations](https://docs.python.org/3/library/typing.html) 
to your code (especially function arguments!). This helps a lot with code readability.

## Jupyter notebooks

All jupyter notebooks live under `src/notebooks`. Notebooks should be individual only - git does not
handle merging notebooks well. If your code needs collaboration, factor it out into a script!
Notebooks should follow the naming convention `name-purpose-xx.ipynb`, e.g.
-   `apoirel-exploration-01.ipynb`

## Pushing changes 

Except for exploratory notebooks, do your work on a feature branch and open a pull request 
from there. This gives us the chance to verify that your code is compatible with the 
rest of our data pipeline for model ensembling.