# d3js_visualizations

D3.js is a JavaScript library used to create dynamic and interactive data visualizations on web browsers. It employs standards like Scalable Vector Graphics, HTML5, and Cascading Style Sheets.
<br>

D3.js proves beneficial for creating dynamic and interactive data visualizations on web browsers. Its adaptability and reliance on a data-driven approach facilitate a range of visualizations, spanning from uncomplicated charts to intricate graphs. The smooth incorporation with web standards and robust community support further amplifies its efficacy for developers.
<br>

The official website of d3.js can be found [here](https://d3js.org/), and you can read more about the library [here](https://en.wikipedia.org/wiki/D3.js).

In this application, we will be leveraging and trying out different features of the library by creating static and dynamic plots. These plots include network graphs, histograms, tables, and charts.
<br>

For this application, we will use version *7.8.5* of ds.js. The raw source file can be downloaded/linked from:
```
https://d3js.org/d3.v7.min.js
```

<br><br>

### **APPLICATION 1**
<br>

We will focus on the Seattle weather dataset from 2012. The dataset can be found and downloaded using the link: 
```
https://github.com/vega/vega/blob/main/docs/data/seattle-weather.csv
```
<br>

| Filename        | Description |
| --------------- | ----------- |
| seattle_121     | Histogram plot showing distribution of the wind variable (setting number of bins as 10) of the dataset |
| seattle_122     | Histogram plot showing distribution of the wind variable (changing number of bins to 25)               |
| seattle_123     | Pie chart plot showing the distribution of the weather variable with labels and legend annotating each sector                |
| seattle_124     | Line graph showing precipitation distribution |
| seattle_131     | Dynamic histogram plot showing wind variable distribution, with user-settable bin size between 5-25 in increments of 5 |
| seattle_132     | Dynamic histogram plot showing user-selectable parameter distribution such as precipitation, temp_max, temp_min and wind variables, with user-settable bin size between 5-25 in increments of 5 |


<br><br><br>

### **APPLICATION 2**
<br>

We will focus on the Auto mpg dataset. The dataset can be found and downloaded using the link: 
```
https://github.com/plotly/datasets/blob/master/auto-mpg.csv
```
<br>

| Filename        | Description |
| --------------- | ----------- |
| autompg_211     | Table displaying top 5 samples of the dataset |
| autompg_212     | Table displaying count of the number of cars of the dataset |
| autompg_213     | Table displaying total number of cylinders for each model year |
| autompg_214     | Table displaying count of the number of cars of each acceleration |
| autompg_221     | Pie-chart displaying count of the number of cars |
| autompg_222     | Line-chart displaying total number of cylinders for each model year |
| autompg_223     | Histogram displaying count of the number of cars of each acceleration |

<br><br><br>

### **APPLICATION 3**
<br>

We will focus on the Le Miserables dataset. The dataset can be found and downloaded using the link: 
```
https://github.com/benahalkar/d3js_visualizations/blob/main/application3/miserables.json
```
<br>

| Filename        | Description |
| --------------- | ----------- |
| miserables_311  | Network graph showing character co-occurrence in the dataset (without character labels)      |
| miserables_312  | Network graph showing character co-occurrence in the dataset (with character/node labels)    |
| miserables_313  | Adding **fisheye distortion** to the network graph for better visibility                 |

<br><br><br>

### **HOSTING THE APPLICATION**

The application was tested and hosted on Apache, and installed on a local machine. The link to download Apache (on Windows) can be found here:
```
https://www.apachelounge.com/download/
```

<br>

Apache is installed and executed as a service

<br>

The webpage of any application can be accessed via a browser at the URL
```
127.0.0.1/applicationx/filename.html
```
