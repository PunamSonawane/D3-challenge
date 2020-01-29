# Data Journalism and D3 (D3 challenge)

This project uses D3.js to visualize some state-level data about population health based on 2014 U.S. Census data. 
It similates an on-line newpaper article with an interactive visualization. Three risk factors (obesity, smoking, and uninsurance rates) 
are plotted against three perhaps underlying factors (income, poverty rate, and age).

* [Background](#background)
* [File Structure](#file)
* [Running](#run)
* [Technologies Used](#technologies)

##  <a name="background"></a>Background
Using the D3 techniques created a scatter plot between two of the data variables such as `Healthcare vs. Poverty` which represents each state abbreviation with circle elements.
 * Healthcare vs. Poverty scatter plot
	![4-scatter](Images/4-scatter.jpg)

## <a name="file"></a>File Structure

 * The base webpage template is index.html.
 * The assets folder contains everything else of relevance
 * assets/css holds two styling files, styles.css and d3style.css
 * data holds the data set in data.csv
 * assets/js holds app.js, the latter of which runs the javascript code that contains the visualization

##  <a name="Run"></a>Running the project

Due to loading in a csv file, many browsers will fail to load this unless run on an http server. This project was developed with the python -m http.server method.

##  <a name="technologies"></a>Technologies Used

* Javascript 
* HTML\CSS
* D3 library
