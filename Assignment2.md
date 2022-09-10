# Assignment 2

# Table of Contents
1. Part 1: Working with web-based visualization tools and data
2. Part 2: Working with Flourish
3. Part 3: Working with Tableau
4. Critique: Different methods of visualization

## Part 1: Working with web-based visualization tools and data 

### 2021: Top 5 Countries with the highest Government Debt-to-GDP ratio
🎨 Using the color gray to calm down the overall visual impression of the chart and allow the top 5 countries to stand out. 
<iframe src="https://data.oecd.org/chart/6O8M" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6O8M" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2021</a></iframe>

### 1995-2021: Top 5 Countries with the highest Government Debt-to-GDP ratio
🎨 Using the color gray to shift the focus to the top 5 countries.
<iframe src="https://data.oecd.org/chart/6O8S" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6O8S" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 1995 – 2021</a></iframe>

## Part 2: Working with Flourish
🎨 A Grid of line charts allows us to visually compare several charts along a shared x and y axes.

📌 Takeaways:
- The General government debt-to-GDP ratio measures the gross debt of the general government as a percentage of GDP. 
- The danger of default increases with the debt-to-GDP ratio, which might spark a financial panic in both local and global markets.
- Japan has the highest national debt in the world.

<div class="flourish-embed flourish-chart" data-src="visualisation/11134241"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

#### Custom Visualization
🎨 A circle packing chart allows us to visualize large datasets faster.

📌 Takeaways:
- Bigger circles depict higher debt-to-GDP ratios.
- We can infer that Japan and Greece continue to be at the center of the map during most years depicting the hight debt-to-GDP ratios. 
- The interactive chart shows an annual snapshot of the different countries, one year at a time. Thus, we can interpret how the positioning changed over time.
- **Drawback?** I tried to adjust the color scale to match the size of the circles to make it faster to interpret. But Flourish doesn't support color by value for this visualization type. This made me opt for a heatmap. 
<div class="flourish-embed flourish-hierarchy" data-src="visualisation/11146915"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

🎨 A heatmap allows us to visually compare categorical data faster with the help of color.

📌 Takeaways:
- We can infer that the OECD average has increased over time, especially in the past few years. 
- If the reader is interested in a more precise value, we have pop-ups to display additional information.
<div class="flourish-embed flourish-heatmap" data-src="visualisation/11147788"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Part 3: Working with Tableau 
<iframe src="https://public.tableau.com/views/GovernmentDebt_16628232281880/Dashboard1?:language=enGB&:display_count=y&:showVizHome=no&:origin=viz_share_link" width="100%" height="1200" seamless frameborder="0"></iframe>

<iframe src="https://public.tableau.com/views/GovernmentDebtmapped/Dashboard2?:language=enGB&:display_count=y&:showVizHome=no&:origin=viz_share_link" width="100%" height="1200" seamless frameborder="0"></iframe>

## Critique: Different methods of visualization
| Type of visualization | Comments |
|-----------------------|----------|
| Bar chart             |          |
| Line chart            |          |
| Grid of line charts   |          |
| Heatmap               |          |
| Country Heatmap       |          |
