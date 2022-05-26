# *San Francisco Housing Analysis*
---

## San Francisco Housing Analysis
This project covers the use of PyVis and the hvplots library to plot and analyze rent statistics based on location.

>"If you're going to San Francisco be sure to wear some flowers in your hair."

## Technologies 

This project uses Python, Pandas, and the Hvplot library to plot graphical interpretations of data. 

[pandas](https://github.com/pandas-dev/pandas)
[HVplot](https://github.com/holoviz/hvplot)

### Installation Guide

In order to use this program please import and utilize the following libraries and dependencies: 

```python
import pandas as pd
import hvplot.pandas
from pathlib import Path
```

## Usage 
the following blocks of code from the Pandas library are fundamental in executing the program. 

```python 
pd.read_csv(Path("../"))
```
This imports a local csv file for integration. 

```python
pd.groupby("")
```
This command groups the output of a pandas DataFrame by a specfic string. 
```python
df.hvplot.bar("")
```
This is a plot code using the HVplot "Bar" graph type. It will output your data in a standard bar graph. 

```python
df.hvplot.line(xlabel="",ylabel="")
```
This is a plot that uses a line(s) for graphing data. You can specify labels for the X and Y axes. 
```python
df.hvplot.points("")
```
This code will plot a graph using points across a geographical overlay. You may be required to specify a "geo" parameter in boolean "True" or "False" logic. Additionally you will likely need to specify "Longitude" and "Lattitude" as parameters for the graph to plot. 

![<alt text>](https://postimg.cc/jwh9mFNG)

## Contributors

Jeffrey J. Wiley Jr

## License

MIT



