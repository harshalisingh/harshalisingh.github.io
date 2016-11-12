---
published: true
layout: post
date: 2016-11-11T00:00:00.000Z
categories: visualization
tags: homework hw4 data-visualization brushing linking d3.js
comments: true
analytics: true
---
## CS 7280: Special Topics in Information Visualization
### Homework 4 - Part 2: Brushing and Linking

The idea of linking and brushing is to combine different visualization methods to overcome the shortcomings of single techniques. Interactive changes made in one visualization are automatically reflected in the other visualizations. Two of these several techniques are **Brushing** and **Linking**.

**Brushing** refers to several interaction techniques that allow the user to select a subset of data in a visualization. By **Linking**, we mean showing how a point, or set of points, behaves in each of the plots. This is accomplished by highlighting these points in some fashion.

- **Dataset**

      I have selected the GDP information of Top 7 countries (by GDP) during the year 2013, 2015 and 2016.

      <p>Data Source: <a href="http://statisticstimes.com/economy/countries-by-projected-gdp.php" target="_blank">List of Countries by Projected GDP</a></p> 

      Dataset snapshot:
      <p><img src="../../assets/images/gdp_dataset.png" alt="projected-gdp.png" /></p>

- **Cleaning Dataset**
  
      The inital cleaning steps involved selecting the date and the GDP column from the dataset. Then, the dataset was filtered to capture data for Top 7 countries. The format of the date column was changed to Year and the GDP column was changed to numeric. Preliminary exploration of the data was performed in Excel. I have rounded the GDP value to the closest 500 multiple for ease of use.

      <p><img src="../../assets/images/brushing_bar_pie.png" alt="gdp_brushing.png" /></p> 
  
- **Interactive Visualizations**

 1. An interactive visualization using Bar Chart, Pie Chart

      <p><img src="../../assets/images/brushing_bar_pie.png" alt="brushing_and_linking.png" /></p>

      <p>Brush and Zoom: <a href="https://htmlpreview.github.io/?https://github.com/harshalisingh/harshalisingh.github.io/blob/master/_posts/hw4-part2/brushing_bar_pie.html" target="_blank">GDP Visualization</a></p>

      </br>


Source Code of Interactive Visualizations: [Brushing and Linking](https://github.com/harshalisingh/harshalisingh.github.io/tree/master/_posts/hw4-part2)

Author: Harshali Singh