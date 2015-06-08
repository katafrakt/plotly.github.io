---
layout: new_layout
title: Continuous, Filled Error Bars
subtitle: A Step by Step Guide to Making a Heat Map
permalink: /continuous-filled-error-bars
imageurl: https://plot.ly/~chris/10173.png
state: active
tags: statistical
meta_description: Make graphs with filled area bars to denote confidence intervals. Plotly is the easiest way to graph your data online.
popularity: 
actioncall: Draw Filled Confidence Error Bars
---

<div>
    <a href="https://plot.ly/~TestBot/20387/" target="_blank" title="wt vs mpg" style="display: block; text-align: center;"><img src="https://plot.ly/~TestBot/20387.png" alt="wt vs mpg" style="max-width: 100%;"  onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
    <script data-plotly="TestBot:20387" src="https://plot.ly/embed.js" async></script>
</div>

### Enter your data
Include the confidence intervals upper and lower bound as the 3rd and 4th columns.
![image](https://cloud.githubusercontent.com/assets/1280389/7815735/3be3d9fc-0398-11e5-9fff-01ce6c16f2fd.png)

### Make the graph
![image](https://cloud.githubusercontent.com/assets/1280389/7815746/4ee7b1b8-0398-11e5-83fc-5856e6f6f76b.png)

### "Fill" the second-to-last trace to the last trace
![image](https://cloud.githubusercontent.com/assets/1280389/7815806/a143dc02-0398-11e5-938b-a774c2be0fc1.png)

### Update the style
Remove the confidence interval's border line.
![image](https://cloud.githubusercontent.com/assets/1280389/7815849/eb370654-0398-11e5-9d0e-863c0e6be5b4.png)

Make the other border line transparent.
![image](https://cloud.githubusercontent.com/assets/1280389/7815886/1fa1a458-0399-11e5-8883-a749e36b722a.png)

Make the center trace a scatter plot.
![image](https://cloud.githubusercontent.com/assets/1280389/7815922/5aa089fc-0399-11e5-8928-e15bcf2a4797.png)

Hide the lower lower border trace from the legend. 
![image](https://cloud.githubusercontent.com/assets/1280389/7816051/10c9579a-039a-11e5-9bdd-6d97b699ceeb.png)

Update the legend
![image](https://cloud.githubusercontent.com/assets/1280389/7816069/2747f4d6-039a-11e5-9959-03b7cc012de7.png)