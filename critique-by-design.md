| [home page](https://ssleung-ux.github.io/Shirley-Leung-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique and redesign
## Step one: the visualization

Source: [makeovermonday/2023w4](https://data.world/makeovermonday/2023w4)  
Source article: [National Highway Traffic Safety Administration](https://datahub.transportation.gov/Automobiles/NHTSA-Recalls-by-Manufacturer/mu99-t4jn)

I selected this visualization because I personally have an interest in cars, which immediately caught my attention when I saw the title regarding recall.

After examining the chart more closely, I realized that the visualization does not communicate the information very intuitively. Although the pie chart uses many colors and includes data labels, it is difficult for the audience to quickly understand what the chart is showing without hovering over the tooltip or carefully examining the legend.

<img width="1568" height="740" alt="image" src="https://github.com/user-attachments/assets/0ae12de3-523e-4c21-9498-bfdfeb9f1e23" />


## Step two: the critique
One issue with the visualization is that the pie chart includes too many categories, which makes it difficult to match each slice to the corresponding manufacturer. The legend is long and requires viewers to constantly look back and forth between the chart and the labels. This makes the chart harder to read and slows down the viewer’s ability to quickly understand the information being presented.

Another concern is that the title does not indicate the time period covered by the dataset. Without knowing the duration, it is difficult for viewers to understand the context of the recall counts shown in the chart.

Overall, the large number of categories and colors makes the visualization difficult to interpret at a glance and reduces its effectiveness in communicating the main takeaway.


## Step three: Sketch a solution

<img width="1687" height="905" alt="image" src="https://github.com/user-attachments/assets/e762ce62-3f84-4459-b47b-b3ae0b685631" />


## Step four: Test the solution

The following are some reviews from in-class:

| Question | Interview 1 | Interview 2 | Interview 3 |
|--------------------------------------------------|-------------|-------------|-------------|
| Can you describe to me what this is telling you? |the naming of the labeling is confusing |Based on the word "recall", might not immediately think about cars| Can see vehicle recall take the biggest portion of overall recalls|
|Is there anything you find surprising or confusing?|The abbreviation "NHTSA" not understand what it is stands for|The legend is confusing, as equipment and vehicles can be the same thing. Not understand what's the difference| Might not have enough information display useful insight|
|          |             |             |             |

Synthesis: 
The labels I used was not specific enough, and were confusing in terms of what stories it was trying to tell. 

## Step five: build the solution

<div class='tableauPlaceholder' id='viz1775012601362' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;20&#47;2000-2022Top12NorthAmericaCarManufacturersbyRecallIncidentRecallType&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='2000-2022Top12NorthAmericaCarManufacturersbyRecallIncidentRecallType&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;20&#47;2000-2022Top12NorthAmericaCarManufacturersbyRecallIncidentRecallType&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>

Link: [Tableau public link](https://public.tableau.com/views/2000-2022Top12NorthAmericaCarManufacturersbyRecallIncidentRecallType/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
For my solution, I used sunburst chart to display the top 12 car manufacturers with the hightest volumn of recalls from 2000-2022. This chart would allow us clearly see the types of recalls are dominating for each manufacturer. 
Using a gradient color instead of all different color helps the audience draw their attention to the most serious manufacturer for recalls.
Placing labels on top of the slides are important for readers to identify the information.


## AI acknowledgements
Used AI to clean up the manufacturer's name, as their naming was inconsistent.

