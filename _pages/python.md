---
permalink: /python projects/
title: "Python Projects"
---

## Project: Data Cleaning
**Goal**: Clean Excel data for analysis  
**Techniques**: Python Pandas and Numpy Libraries.  
**Results**: A new short database with updated and removed unnecessary information.  

```python
import pandas as pd
import numpy as np
df = pd.read_excel('/Users/iamnoterik/Documents/Pandas DA/Data Cleaning/Customer Call List.xlsx')
df

df = df.drop_duplicates()
df
