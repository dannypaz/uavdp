Different kinds of variables:

Numerical (Quantitative)
2 different sub types
Continuous - like time or height or something
Discrete - set number of countable values amount of kids in family (can never be decimal)

Categorical (Qualitative) - Classifies individuals into items/groups
Ordinal - ranking, class ranking
Nominal - names, no ranking


Comparative vs Non-Comparative

AB testing vs. forcasting stocks

Numerical or Quantitative means, taking the mean makes sense :)

### Python Pandas

Syntax for imports in python3
import pandas as pd

```python
df = pd.read_csv("csv.file.name")
# view the top few rows of csv
df.head()
# viewing columns in the data se
df.columns
```

df.loc
df.iloc

the only difference between loc and iloc is that iloc is mean for integers of column names where loc you specifiy the column names.

```python
df.loc(1:2, ["mycolumn", "names"])
df.iloc(1:2, 1:2)
```

Seeing the types of columns is pretty easy too

```python
df.dtypes
```