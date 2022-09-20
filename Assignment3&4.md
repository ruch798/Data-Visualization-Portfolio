# Assignment 3 and 4
## Step one: find a data visualization (with data you can use!) 🔎

As a Computer Engineer, it is imperative to be updated about advancements in the industry, especially when there are new strides daily. 

### 🗓️ 2020 - When I first saw the chart

I remember coming across a visualization about the biggest tech acquisitions in 2020, which was extremely hard to infer when I first glanced at it. 

### 🗓️ 2022 - Reviewing it from a critic's perspective

With the knowledge I have about critiquing visualizations through this course, I could see a lot of reasons why the chart was challenging to interpret and misleading in several ways.

- **Data Visualization** : Visual Capitalist, [Visualizing the Biggest Tech Mergers and Acquisitions of 2020](https://www.visualcapitalist.com/visualizing-biggest-tech-mergers-and-acquisitions-of-2020/).
- **Original data source** : Computer World, [Biggest technology acquisitions of 2020](https://www.computerworld.com/article/3513439/biggest-technology-acquisitions-of-2020.html).

![](https://i.imgur.com/WKVfvI7.png)

## Step two: critique the data visualization with Data Visualization Effectiveness Profile 👩‍💻
## Informative 📚
### Usefulness 
📝 Is it useful for the intended audience?  Does it communicate valuable information?
<p align="center"><img src="https://i.imgur.com/Sc8Maxu.png" width=700></p>
The visualization communicates useful information for a tech audience interested in learning more about **tech acquisistions during the pandemic**.

### Completeness  
📝 Does the visualization have everything necessary to make it understandable?
<p align="center"><img src="https://i.imgur.com/A5etdsn.png" width=700></p>
The **timeline** at the bottom of the chart helps us to infer that most companies saw the opportunity to grow their business through mergers and acquisitions when the market was down.

### Perceptibility
📝 Can the reader understand the information with minimal effort? Is the visualization type appropriate?  Does it use illogical comparisons?
<p align="center"><img src="https://i.imgur.com/2giiCsa.png" width=700></p>
**Design**
- The selected graph type is **unconventional**, which shifts the focus from the information being conveyed to the user admiring the design component of the visualization.
- **Colors have been unnecessarily used** to compare the intensities of each data point when the length of bars could have sufficed.

**Information**
- The information is **difficult for the human eye to perceive** with minimal effort and appropriate precision. 
- The **scale chosen is inaccurate** as well. For example, $40B is not 40 times $1B in the chart. 

### Truthfulness
📝 Is the visualization accurate, reliable and valid?  Is it representing what it says it is, and in the most complete and truthful manner? Does it misrepresent the data or make comparisions that aren't correct?
<p align="center"><img src="https://i.imgur.com/Ckgre4Y.png" width=700></p>
- The visualization is inaccurate, unreliable, and invalid. 
- The **comparisons drawn** in the chart are **not correct**. For example, $40B is not 40 times $1B in the chart.

### Intuitiveness
📝 Is it easy to understand and clearly communicates the information?  If unfamiliar, does it include easy to understand instructions on how to interpret it?
<p align="center"><img src="https://i.imgur.com/PviSGNF.png" width=700></p>
- The chosen chart type is **unconventional** in the tech industry. 
- Although instructions on interpreting the chart have been provided, the **depiction of each data point** is **inaccurate** because of the shape chosen instead of a bar. 
- **No visual scale** has been provided for accurate comparison.
- For smaller M&A, the **text size** is **difficult to read**.
- The convention specified in the instructions mentioned that the company names inside the bubble-shaped bar were the acquired companies. But in the case of more minor mergers and acquisitions, the shape was too small to accommodate the company names, so the **visualization broke the instructions it had set** to convey the information, which makes it **inconsistent**. 

## Emotive 🤩
### Aesthetics
📝 It is interesting / enjoyable to look at?  Is it a good example of what a beautiful data visualization might look like?  Is it somewhere in the middle pleasing but otherwise not distracting to look at?
<p align="center"><img src="https://i.imgur.com/6vCa7yX.png" width=700></p>
The data visualization is interesting but confusing to interpret.

### Engagement
📝 Does it lead the audience to learn more about the topic?  Does it inspire the audience to talk about the data or share it with others?
<p align="center"><img src="https://i.imgur.com/npAl40h.png"></p>
- The visualization packs a lot of information, but it would lead the tech audience to learn more about the topic. 
- It inspires the audience to share it with more people in their network.

### Overall observations
What went well 🤩
- The timeline at the bottom of the chart helps us infer that more extensive M&A occurred when the market was exceptionally down.

What didn't go well 😠
- The chosen chart type is extremely inaccurate for conveying information. For a tech audience, accuracy is more important than design. 

What would I do differently? 🥳
- If I had to use the same chart type, I would ensure I provide a scale for visual comparison and correct the scale factor of data points.
- I would get rid of color since the length of the bars would suffice.

### Audience 
The primary audience for this tool is people from the tech industry: 
- engineers interested in staying on top of trends, 
- engineers interested in working for said companies, 
- technical consultants looking to advise companies interested in M&A

The visualization draws the attention of the audience. But inaccuracies will be uncovered when we pay attention to detail. Therefore, this is not an appropriate chart to be shared at board or executive meetings with senior company members who would value accuracy more than design.

### Final thoughts
This method was successful at evaluating the visualization I had picked. 
I would include **simplicity** as a factor for evaluating a visualization as well. 
The measure would aim to capture whether a visualization is simple to understand. 
- whether it has highlighted only a small number of categories to **improve the focus of the reader**
- whether it **uses color appropriately** to make critical information stand out
- whether it keeps eye travel to a minimum

## Step three: sketch out a solution 🎨
- **Chart type**: In my re-design, the first thing I did was to use a familiar chart type that represents the scale accurately, which is what led me to choose a bar chart.
- **Column**: Rather than showing the Acquiree information inside the bars, I created a separate column for it right next to the Acquirer Company. Since most people read the chart from left to right, they would first see the Acquirer company, then the acquired company, and finally the amount spent.
- **Color**: I chose to highlight NVIDIA's spend compared to all the companies by using the color green and graying out the rest. In addition, I opted for this shade of green since it is similar to the company's logo and would immediately stand out to those in the tech industry.
- **Reference line**: I chose to highlight the average amount spent on acquisitions to establish a line of reference for big tech companies depicted in the chart.
- **Title**: I changed the title to "NVIDIA spent the most on tech acquisitions in 2020" so that readers can quickly interpret the chart and understand the key takeaway.

<p align="center"><img src="https://i.imgur.com/ZWmWcMs.jpg" width=800></p>

### Same chart but neater! Thanks to Tableau ✨
<div class='tableauPlaceholder' id='viz1663450753272' style='position: relative'><noscript><a href='#'><img alt='Dashboard 2 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment3-OriginalDesign&#47;Dashboard2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Assignment3-OriginalDesign&#47;Dashboard2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment3-OriginalDesign&#47;Dashboard2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1663450753272');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} 
  else if ( divElement.offsetWidth > 500 ) 
  { vizElement.style.width='1000px';vizElement.style.height='827px';} 
  else { vizElement.style.width='100%';vizElement.style.height='727px';}                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## Step four: Test the solution 🧪
## 🎙️ Interview 1 : Technical Consultant, mid 20's 
<p align="center"><img src="https://i.imgur.com/V8U7fap.png"></p>

## 🎙️ Interview 2 : Computer Engineer, mid 20's 
<p align="center"><img src="https://i.imgur.com/0EGFssY.png"></p>
[HTML template by Bootdey](https://www.bootdey.com/snippets/download/card-chat-list), MIT License

**Similarities**
- The interviewees could interpret what the chart was about.
- The interviewees shared similar thoughts as me regarding the audience for this data visualization.
- The interviewees preferred a uniformly sorted chart and recommended opting for a stacked bar chart representing the total expense of companies on M&A in 2020.

**Differences**
- One of them had the same takeaway as the title. The other interviewee focused more on the data and had a new insight.

**What patterns in the feedback emerge?**
- The feedback began to get more detailed as they spent more time looking at the chart.

**What did you learn from the feedback?**
- The chart type would need restructuring to make it more clear.
- The title needed some work to convey the message correctly and avoid confusion.
- The median reference line would be a better measure than the average.

## Step five: Build your solution 🔨
<div class='tableauPlaceholder' id='viz1663450586209' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment3-Re-Design&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Assignment3-Re-Design&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;As&#47;Assignment3-Re-Design&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1663450586209');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) 
  { vizElement.style.width='1000px';vizElement.style.height='827px';} 
  else if ( divElement.offsetWidth > 500 ) 
  { vizElement.style.width='1000px';vizElement.style.height='827px';} 
  else { vizElement.style.width='100%';vizElement.style.height='727px';}                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

### Changes I made ✏️ 
**Title & Subtitle**
- I changed the title to highlight that the chart represents acquisitions of big tech in 2020.
- I added a title that includes the key takeaway, which is: NVIDIA spent the most 💰

**Reference line**
- In place of the average reference line, I added a median reference line to represent the data better.

**Chart structure**
- I modified the chart structure to represent companies' total spending in acquisitions in 2020.  
- Two companies acquired more than one company. I wanted this information to be represented. Therefore, for those who wish to dig deeper into the visualization, I've added dark lines inside the bar to represent a distinction between the companies acquired. 
- I added a tooltip to include more details about the acquisition: the date of the acquisition and the amount spent. 

### What my redesigned data visualization depicts 🎬
- I changed the chart's structure to represent the total amount spent on acquisitions by big tech in 2020.
- I highlighted that NVIDIA spent the most compared to other companies.

### Reason for selecting the data visualization 📄
- I preferred this visualization since **"Less is better."**
- If people want to look for greater detail, they can hover over the bars to find what they need.
Reducing visual clutter makes a chart easier to understand. 

### What I attempted to show or do differently 🎥
- Rather than showing the acquisitions in chronological order like the original source, I re-ordered the chart to represent a sorted bar chart in order of the total amount spent on acquisitions which is more in line with what the original source intended to portray ("Visualizing the Biggest Tech Mergers and Acquisitions of 2020.")
