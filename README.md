# The environmental cost of fashion
### A website report using interactive visualizations created with D3
This is a classroom project created in the month of December 2022 at Pratt Institute, NYC. 

## 01. About the project
The environmental impacts of the fashion industry are widespread and substantial. The [Fashion Revolution](https://www.fashionrevolution.org) is the world’s largest fashion activism movement, mobilizing citizens, brands and policymakers through research, education and advocacy. Their [“fashion transparency index”](https://www.google.com/search?client=safari&rls=en&q=fashion+transparency+index&ie=UTF-8&oe=UTF-8) is a tool to rank the world’s largest fashion brands and retailers based on what information they disclose about their social and environmental policies, practices and impacts, in their operations and supply chain. The Index is a tool to push and incentivise fashion brands to be more transparent about their social and environmental efforts as it is foundational to achieving systemic change in the global fashion industry. The research study scores brands on various transparency indices with varying weights. 

**This interaction visualization project will focus on the environmental impact metrics captured in the study.** 

The project will answer the research questions -
- Which companies/fashion brands perform the best/worst in terms of sharing information on their environmental impact transparency metrics charted out by fashion revolution?
- What are the scores of each of the companies across the transparency sub-segments?

Read the complete project proposal [here](https://docs.google.com/document/d/1m5mDR6d8ahnKloVvW77OdbqLKlHP3M9e2Fki1RC-KiU/edit).

## 02. Data source

The scores of each of the brands in the study, across categories have been sourced from the website. The excel sheet with the scores was filtered according their relevance with impact on the environment.

## 03. Design rationale

The visualization is designed to allow viewers to understand the context and the dataset before jumping into the visuals. There are hence a couple of starter slides added that share information on the relevance of the topic and provides a link to the raw dataset.

## 04. Project documentation 

### Video of the visual

The below video shows all the pages with the interactions incorporated in the visual.
add

### Page-wise breakdown of data presented

**01 Intoductory page**
Viewers see a starter section and get into the visual report by clicking on "explore".


**02 Context pages**
There are 3 context pages that describe the relevance of the topic, fashion transparency index and the dataset. 


This page helps viewers understand the type of visuals they can view.


**03 Performance of indvidual brands across categories**
5 stakced bar charts are presented in ths section. Viewers can jump between the scores of brands across different categories like water consumption, energy use, waste circularity, etc. Scores can be calculated by counting the number of bars in every brand.  


**04 The topmost and the least sustainable brands**
This visual lists the brands according to the highest and lowest total scores (scroing out of 32). Viewers can sort the visuals in ascending or descending order (also colored accordingly). 


**05 Explore the performance of the different countries**
This bubble chart shows average scores of each country along with the number of brands they have. Bigger the circle, higher is the score. A slider at the top helps viewers select the maximum score of their choice.


### Key features added
Stacked bar plots:
- Buttons to toggle between charts

T-shirt icons visual:
- Tooltip hover providing additional data 
- Ascending and descending order buttons

Bubble chart:
- Interactive buttons
- Single color nodes
- Slider
- Label names
- Use of force simulation

## 05 Key findings 
Stacked bar plots:
Most of the brands appear to be doing well in the categories - sustainable sourcing and materials and carbon emmissions. 

T-shirt icons visual:
There are many brands with a score of 0/32. The highest a brand has scored is 26/32 which is OVS from Italy.

Bubble chart:
Australia, Sweden, Canada, Spain and Denmark are the top performing countries. Although most of them have few brands listed.  

