# Self-Study Project
This is a self-study project as part of MSIS 2626: Dashboard, Scorecard, and Visualization class. It is divided into 2 parts.

For the first part the topic of interest is **climate change caused by human activity** and we have to do the following: 
1. Do a literature search on what is an effective visualization.
2. Select evaluation criteria and put them in a framework.
3. Find 5 visualization.
4. Use your criteria to evaluate the 5 visualizations.
5. Write a conclusion.

For the second part we have to replicate the first Warming Stripes visual found [here](http://www.climate-lab-book.ac.uk/2018/warming-stripes/) using any visualization tool.

Reference: [Syllabus](https://github.com/mschermann/msis2629spring2019) & Professor comments.

## Part 1
### Introduction

Data visualization is a graphical representation of data points. The main purpose is to communicate the information clearly which will help the audience of the visual to identify hidden patterns and also enable the decision-maker of business to make the right decision. A good visualization can also help the user to identify areas of improvement, identify influencing factors to influence customers, and in some cases also make predictions.

### Literature Study

#### **Why is data visualization important?**
Human brain finds it easy to process information from charts or graphs for large amounts of complex data compared to spreadsheets and reports. Data visualization is a quick, easy way to convey concepts in a universal manner – and you can experiment with different scenarios by making slight adjustments.

#### **The Role of Visual Perception in DataVisualization**
The effectiveness of a visualization depends on many conditions such as conventions, subjective user preferences, cultural settings, and the structural correspondence with its denoting data. A theory of effective data visualization should therefore be based on theories of human visual system that describe human capabilities of perceiving visual relations. 

A step by step process model for effective data visualization:
  1. To determine the structure of data, i.e. how data elements are related to each other.
  2. To determine visual elements that represent data elements in such a way that the perceptual structure of the decided visual elements represents the structure of the data.
  3. To the layout process which transforms the abstract perceptual structure to a drawable visualization.

The paper also illustrates following  factors that influences visualizations to be effective:
  1. The choice of visual attributes for data attributes may influence the effectiveness of visualizations.
  2. The generation of values for the undecided visual attributes may also influence the effectiveness of visualizations. The reason is that a human viewer perceives differences between shapes of visual elements and may infer that these differences visualize differences in the presented data.

#### **The three elements of successful visualization**
  1. It understands the audience: Before you start building up visualization, start with a goal by understanding who the audience of the visual is, their expectations and how can this visual help the audience take some action from it.
  2. It sets up a clear framework: The first step is to make sure that the data is clean and you take remove/mention about the outliers depending on the context. The choice of chart type and consistency of the text is another crucial factor.
  3. It tells a story: Finally, it should tell a story and set a common ground for the audience. Storytelling helps the reader gain insights about the data.

#### **How to choose the best form of visualization?**

  1. 5 second rule: Research shows that the average modern attention span for viewing anything online is less than 5 seconds, so if you can’t grab attention within 5 minutes, you’ve likely lost your viewer. Include clear titles and instructions and tell people succinctly what the visualization shows and how to interact with it.
  2. Design and layout matter: The design and layout should facilitate ease of understanding to convey your message to the viewer. 
  3. Keep it simple: Keep charts simple and easy to interpret.
  4. Pretty doesn’t mean effective: There is a misconception that aesthetically pleasing visualization is more effective. To draw attention, sometimes we want them to be pretty and eye-catching. But if it fails to communicate the data properly, you’ll lose your audience’s interest as quickly as you gained it.
  5. Use color purposely and effectively: Use color only if it assists in conveying your message. If using colors, be consistent in choosing the color scheme.

Literature References:<br>
[Why is data visualization important?](https://www.sas.com/en_us/insights/big-data/data-visualization.html)<br>
[The Role of Visual Perception in DataVisualization](https://pdfs.semanticscholar.org/95d1/24d8748ac5bddcd29b2b09a8585b1a697e63.pdf) <br>
[The three elements of successful visualization](https://hbr.org/2013/04/the-three-elements-of-successf)<br>
[How to choose the best form of visualization?](https://mschermann.github.io/data_viz_reader/fundamentals.html#how-to-choose-the-best-form-of-visualization)

### Framework to evaluate 5 visualizations

* Below is the rubric I came up with for evaluating the visualization:
  1. **Simple to interpret:**<br>Is the visual simple and easily interpretable?
  2. **Labels:**<br> Are the labels readable and is the choice of font type and size enhancing the readability of the visual?
  3. **Title, Legends and Annotations (TLA):**<br> Are these simple yet effective in communicating what the visual represents?
  4. **Chart Type:**<br> Is the choice of chart type proper or would a different chart type would have more sense?
  5. **Less is more:**<br> Is there anything in the visual that is redundant?
  6. **Color choice:**<br> Is the choice of colors in the visual inconsistent or giving any weightage to any element that is not necessary?
  
* Scored on below scale:
  1. **Outstanding** - 4<br>
  2. **Effective** - 3<br>
  3. **Adequate** - 2<br>
  4. **Ineffective** - 1<br>

Reference: [Visualization Assessment Rubric for above mentioned scores](https://scholarworks.iu.edu/dspace/bitstream/handle/2022/16814/VisualizationAssessmentRubric.pdf?sequence=6)
### Evaluations of the visuals collected using the framework created above

#### Visual 1
![Image of Global](https://github.com/bharatimalik/DataViz_SS_Project/tree/master/Images/Global.JPG)

Evaluation:
1. Simple to interpret:<br>
The visual is simple and easy to interpret. It is a bar chart that tells us the global temperature for various year ranges.
2. Labels:<br>
The font-size of X-axis could be matched with font-size of Y-axis label and could be displayed at a 45 degree angle rather than horizontal. The Y-axis labels are clear. It would be good to mention "Year" for the X-axis title.
3. Title, Legends and Annotations:<br>
Title of the visual is missing. The legend representing what each color represents is missing. The annotation on what that horizontal dotted line represents is missing.
4. Chart Type:<br>
Line chart would have been more appropriate to communicate the changing trend in the global temperatures.
5. Less is more:<br>
The data labels are redundant here. Although absence of data labels may cause difficulty to read the exact values but as the purpose of this visual is to show the upward-trend of the global temperature, it becomes redundant information here.
6. Color choice:<br>
What each color represents is not very clear. One interpretation of 3 colors could be that blue represents the low temperature range, green represents the medium temperature range and orange represent the high temperature range. But communicating the same with color legends is imperative.

| Simple to interpret | Labels | Title, Legends & Annotations | Chart Type  | Less is more | Color choice |
| :-----------------: |:------:| :---------------------------:|:-----------:|:------------:|:------------:|
| 4                   | 3      | 1                            | 2           | 2            | 2            |

[Visual 1 Source](https://www.washingtonpost.com/news/wonk/wp/2013/07/09/you-cant-deny-global-warming-after-seeing-this-graph)

#### Visual 2
![Image of ClimateRisks](https://github.com/bharatimalik/DataViz_SS_Project/tree/master/Images/ClimateRisks.JPG)

Evaluation:
1. Simple to interpret:<br>
It is not that simple to interpret visually. It tells us the probability of vulnerability risk due to climate change as the population size increases. It is an interactive bubble chart that displays 2-3 cities when you hover over each continent button. [Try it here](https://readymag.com/maplecroft/1213892/). Instead, the interactive ability could have been enhanced if by clicking over the bubble we could get more detailed information about the details of the bubble such as the name of the city, population size, etc.
Does the visual mean that a climate vulnerability of 0 - 2.5 comes under Extreme-Risk category and so on? Also, psychologically when we read Y-axis, the values increase from bottom to top and thus we would expect that Y-axis start from low-risk and goes to high-risk.
2. Labels:<br>
Labels are readable and the font size of X-axis and Y-axis labels are consistent.
3. Title, Legends, and Annotations:<br>
Title of the visual is missing. The legend representing continents is clear. The annotation of the size of the bubble is mentioned. But it is difficult to decipher if a particular city has a 6 million size of population or 8 million size of population. 
4. Chart Type:<br>
The choice of bubble chart to represent the size of the population is correct. 
5. Less is more:<br>
The information in the visual is well stuctured and does not have any redundant information.
6. Color choice:<br>
Choosing colors to differentiate the continents is a good idea. However the color chosen for Europe and America belongs to the same family and it would have been best to choose a different color for one of those continents. Using white color for Low-risk - High-risk on Y-axis is difficult to read.

| Simple to interpret | Labels | Title, Legends & Annotations | Chart Type  | Less is more | Color choice |
| :-----------------: |:------:| :---------------------------:|:-----------:|:------------:|:------------:|
| 2                   | 4      | 2                            | 4           | 4            | 3            |

[Visual 2 Source](https://www.maplecroft.com/insights/analysis/84-of-worlds-fastest-growing-cities-face-extreme-climate-change-risks/)

#### Visual 3
![Image of NonEnergySources](https://github.com/bharatimalik/DataViz_SS_Project/tree/master/Images/NonEnergySources.JPG)

Evaluation:
1. Simple to interpret:<br>
It is difficult to interpret what is the exact intent of this visual. Also, we do not know what these percentages represent?
2. Labels:<br>
There is no consistency in the positioning of the labels for what each pie represents. Some are positioned inside the pie and some are positioned outside the pie.
3. Title, Legends, and Annotations:<br>
Title of the visual is missing. Color legends could have een used to show what each pie represents. 
4. Chart Type:<br>
Its difficult to comment on the chart type as it is not clear what the intention of the chart was in the first place.
5. Less is more:<br>
The visual does not have any redundant information.
6. Color choice:<br>
Using more than 6 colors in the visual distracts the reader and makes him lose track about the main intent of the visual. 

| Simple to interpret | Labels | Title, Legends & Annotations | Chart Type  | Less is more | Color choice |
| :-----------------: |:------:| :---------------------------:|:-----------:|:------------:|:------------:|
| 2                   | 1      | 1                            | 1           | 4            | 1            |

[Visual 3 Source](https://oilprice.com/Energy/Energy-General/The-Top-5-Non-Energy-Sources-of-Climate-Change.html)

#### Visual 4
![Image of LineComparison](https://github.com/bharatimalik/DataViz_SS_Project/tree/master/Images/LineComparison.JPG)

Evaluation:
1. Simple:<br>
The visual is simple and easy to interpret. However what the depth of blue and pink colors represent is not very clear.
2. Labels:<br>
The font-size of X-axis and Y-axis labels are different.
3. Title, Legends, and Annotations:<br>
Title of the visual is missing. Color legends are appropriately used for better understanding. 
4. Chart Type:<br>
Chart type used is correct
5. Less is more:<br>
Color legends already mentions what each color represents. Thus mentioning them again in the diagram with big arrow marks doesn't seem to be visually impressive. 
6. Color choice:<br>
Usage of colors is correct and the choice of colors are also correct.

| Simple to interpret | Labels | Title, Legends & Annotations | Chart Type  | Less is more | Color choice |
| :-----------------: |:------:| :---------------------------:|:-----------:|:------------:|:------------:|
| 3                   | 3      | 4                            | 4           | 3            |4             |

[Visual 4 Source](https://www.carbonbrief.org/qa-how-do-climate-models-work)

#### Visual 5
![Image of Droplets](https://github.com/bharatimalik/DataViz_SS_Project/tree/master/Images/Droplets.JPG)

Evaluation:
1. Simple:<br>
The chart is simple to interpret.
2. Labels:<br>
Labels are consistently positioned. But the size of the Note text could be reduced 1-2 sizes smaller. 
3. Title, Legends, and Annotations:<br>
Title and the text under the title could be reframed together as one sentence. Color legends are correct.
4. Chart Type:<br> 0.28% is so minimal compared to other numbers that we can barely see the blue color in the chart. Thus a bar chart would have been more appropriate to display all 3 figures. It is also recommended to avoid 3D charts wherever unnecessary to avoid any confusion.
5. Less is more:<br>
"expressed as %of total" is redundant for the current chart type.
6. Color choice:<br>
Choice of colors is appropriate.


| Simple to interpret | Labels | Title, Legends & Annotations | Chart Type  | Less is more | Color choice |
| :-----------------: |:------:| :---------------------------:|:-----------:|:------------:|:------------:|
| 4                   | 3      | 3                            | 1           | 3            | 4            |

[Visual 5 Source](https://www.geocraft.com/WVFossils/greenhouse_contrib.html)

### Conclusion
This project helped me gain knowledge of different theories behind effective visualization. For visualization to be effective, the chart should be simple to interpret with consistent texts and headers. The choice of charts and colors make/break the overall visualization experience. But the most important aspect of building an effective visualization is to keep the audience in mind. Thus data visualization, if used effectively can help the reader make the right analysis/decision/prediction! 

## Part 2

### Replication of Warming Stripes

Implementation of this replication can be found in a Tableau file [here](https://github.com/bharatimalik/DataViz_SS_Project/TableauReplication.twbx)<br>
Data Source link can be found [here](https://www.metoffice.gov.uk/hadobs/hadcrut4/data/current/download.html) and to understand more about the data [click here](https://www.metoffice.gov.uk/hadobs/hadcrut4/HadCRUT4_accepted.pdf)<br>
The [highlighted](https://github.com/bharatimalik/SS-Proj/blob/master/Images/data.JPG) data was used for this replication.

#### Tableau Results:
![Image of TableauReplication](https://github.com/bharatimalik/DataViz_SS_Project/tree/master/Images/TableauReplication.JPG)
