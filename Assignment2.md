# Assignment 2

# Table of Contents
1. Part 1: Working with web-based visualization tools and data
2. Part 2: Working with Flourish
3. Part 3: Working with Tableau
4. Critique: Different methods of visualization

## Part 1: Working with web-based visualization tools and data 

### 2021: Top 5 Countries with the highest Government Debt-to-GDP ratio 
<iframe src="https://data.oecd.org/chart/6O8M" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6O8M" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2021</a></iframe>
🎨 Using the color gray to calm down the overall visual impression of the chart and allow the top 5 countries to stand out.

### 1995-2021: Top 5 Countries with the highest Government Debt-to-GDP ratio
<iframe src="https://data.oecd.org/chart/6O8S" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6O8S" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 1995 – 2021</a></iframe>
🎨 Using the color gray to shift the focus to the top 5 countries.

## Part 2: Working with Flourish
<div class="flourish-embed flourish-chart" data-src="visualisation/11134241"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
🎨 A Grid of line charts allows us to visually compare several charts along a shared x and y axes.

📌 Takeaways:
- The General government debt-to-GDP ratio measures the gross debt of the general government as a percentage of GDP. 
- The danger of default increases with the debt-to-GDP ratio, which might spark a financial panic in both local and global markets.
- Japan has the highest national debt in the world.

#### Custom Visualization
<div class="flourish-embed flourish-hierarchy" data-src="visualisation/11146915"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
📌 Takeaways:
- Bigger circles depict higher debt-to-GDP ratios.
- We can infer that Japan and Greece continue to be at the center of the map during most years depicting the hight debt-to-GDP ratios. 

🎨 A circle packing chart allows us to **visualize large datasets faster**.
🎨 The **interactive chart** shows an annual snapshot of the different countries, one year at a time. Thus, we can interpret how the positioning changed over time.
🎨 In this manner, we can reduce **eye travel** compared to the grid of line charts. 
- **Drawback?** I tried to adjust the color scale to match the size of the circles to make it faster to interpret. But Flourish doesn't support color by value for this visualization type. This made me opt for a heatmap. 

<div class="flourish-embed flourish-heatmap" data-src="visualisation/11147788"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

📌 Takeaways:
- We can infer that the OECD average has increased over time, especially in the past few years. 

🎨 Color
- A heatmap allows us to visually compare categorical data faster with the help of color.
- The **color scale** is chosen keeping in mind that red is associated with negativity. 
- In this case, **darker colors symbolize the higher risk factor of countries not being able to pay the government debt**.

🎨 Crafting for clarity
- If the reader is interested in a more precise value, we have **pop-ups to display additional information**.
- The general audience may not grasp Alpha-3 country codes quickly which is why I merged an additional data source from Wikipedia to display the country names and **improve readability**. 

🎨 Selecting chart types
- This map is **static** and **less busy** compared to the circle packing chart which can **allow the user to explore trends at their own pace**.

## Part 3: Working with Tableau 
<iframe src="https://public.tableau.com/views/GovernmentDebt_16628232281880/Dashboard1?:language=enGB&:display_count=y&:showVizHome=no&:origin=viz_share_link" width="100%" height="1200" seamless frameborder="0"></iframe>

<iframe src="https://public.tableau.com/views/GovernmentDebtmapped/Dashboard2?:language=enGB&:display_count=y&:showVizHome=no&:origin=viz_share_link" width="100%" height="1200" seamless frameborder="0"></iframe>
