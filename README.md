# <p align="center">Do We Have a Plan BEE? :bee: Analyzing 30 Years of Honey Data</p>

A data analysis attempting to explain a reduction in the U.S. bee population

# <p align="center"> ![HTML CSS Code Screen Shot](images/website_screen_shot.jpeg) </p>

## Questions to Answer?
- Over the last 30 years, is honey production from bees increasing or decreasing?
- Over the last 30 years, is the value of honey production increasing or decreasing?
- What are the top honey producing states and counties?
- What are the top honey producing counties in Indiana?
- How have acres bearing almonds changed as honey production has changed?


## Data Sets to Collect

# <p align="center"> ![HTML CSS Code Screen Shot](images/USDAscreenShot.png) </p>

- Data from the USDA is grouped into two programs, with the Census program being more robust:
    <ol start="1">
        <li>Census - collected once every five years (2017, 2012, 2007, 2002).</li>
        <li>Survey - collected every year since 1987.</li>
    </ol>

- Honey production by U.S., state, and county (including all 92 Indiana counties).
- Honey value by U.S., state, and county (including all 92 Indiana counties).
- Bee colony inventory by U.S., state, and county (including all 92 Indiana counties).
- Bee colony loss by U.S., state, and county (including all 92 Indiana counties).
- Acres bearing almonds by U.S. and state.

# <p align="center"> ![HTML CSS Code Screen Shot](images/HoneyProductionPandasScreenshot1.JPG) </p>


## **E**xtract**T**ransform**L**oad (ETL) the data
- Within Jupyter Notebook/Lab, utilize Pandas to load and clean USDA honey data.

# <p align="center"> ![HTML CSS Code Screen Shot](images/ETL_image.png) </p>


## Analysis to Run
- Change in honey production by state
- Change in honey value by state from
- Change in bee colony inventory from
- Change in bee colony loss from
- Change in acres bearing almonds

- Correlate almond production to decrease in honey production


## HTML / CSS
- Utilizes Sass, a powerful professional grade CSS extension library. Sass allows for nesting, variables and imports to create a neat and simple style sheet.
- Several advanced CSS animations including a pure CSS popup.
- A bio section with several open clickable links per contributor.

# <p align="center"> ![HTML CSS Code Screen Shot](images/HTMLCSSCodeScreenShot.jpeg) </p>


## Machine Learning
- Supervised vs unsupervised - why did we choose one technique over the other?
- Do not overfit or underfit the data
- Need a measure of fitness (R2)
- Understand difference between precision and accuracy
- If using linear regression, use lots of scatter plots and lines
- Multi-regression (a lot vs. one)

# <p align="center"> ![HTML CSS Code Screen Shot](images/Honey_Prod_LR.PNG) </p>

# <p align="center"> ![HTML CSS Code Screen Shot](images/Bee_Colony_LR.PNG) </p>

# <p align="center"> ![HTML CSS Code Screen Shot](images/Almond_LR.PNG) </p>


## Tableau
- A **[Tableau Story](https://public.tableau.com/profile/michael.davis5317#!/vizhome/Do_We_Have_A_Plan_Bee/HoneyStory?publish=yes)** was created consisting of nine total dashboards, which are all incorporated into one easy to understand story.
- Our story is a combination of graphs, charts, and interactive maps.

# <p align="center"> ![HTML CSS Code Screen Shot](images/IndianaCountyHoneyProduction4YearMapComparisonImage.png) </p>

# <p align="center"> ![HTML CSS Code Screen Shot](images/Top10HoneyProducingCounties.png) </p>

## Deploy the Site
- A custom domain **[DoWeHaveAPlanBee.com](https://www.dowehaveaplanbee.com/)** was purchased and GitHub Pages was used to deploy the live site.

# <p align="center"> ![HTML CSS Code Screen Shot](images/GitHub_Pages_settings.JPG) </p>


## Conclusions
- As honey production (lbs) in the United States has declined 33.4% over the last 30 years, honey value ($) has increased by 161.1%.
- North and South Dakota are the top 2 honey producing states, accounting for 34% of the country's
	production in 2019.
- 5 of the 7 highest honey producing counties are in North Dakota.
- In 2019, Indiana ranked 31st in honey production.
- From a high of 1.89 million pounds of honey produced in 1987, Indiana's honey production fell 73.7% in 
2019 with just 495,000 pounds produced.
- Almond bearing acres have increased every year since nationwide data started being collected in 2007.


- - -
## Tools Used

- Adobe Illustrator
- Adobe Photoshop
- CSS
- GitHub
- GitHub Pages
- HTML
- matplotlib
- Pandas
- Python
- scikit-learn
- Seaborn
- Tableau


## Authors

- **Ben Reiff** - **[benreiff](https://github.com/benreiff "GitHub for Ben Reiff")**  Ben was the lead on data cleaning and GitHub
- **Chelsea Snedden** - **[chelseasnedden](https://github.com/chelseasnedden "GitHub for Chelsea Snedden")**  Chelsea was the lead on Machine Learning
- **Michael R. Davis** - **[Davis1776](https://github.com/Davis1776 "GitHub for Michael Davis")**  Michael was the lead on Tableau and project management
- **Morgan Bricker** - **[bricker3k](https://github.com/benreiff "GitHub for Morgan Bricker")**  Morgan was the lead on HTML and CSS


## Acknowledgments

- Data Source: [United States Department of Agriculture (USDA)](https://quickstats.nass.usda.gov/ "USDA Quickstats")
- [Tableau](https://www.tableau.com/ "Tableau Homepage") was used to create the data visualizations.
- [Seaborn](https://seaborn.pydata.org/ "Seaborn") was used to create machine learning plots.
- [scikit-learn](https://scikit-learn.org/stable/ "scikit-learn") was used to create machine learning plots.
- [Plotly.js documentation](https://plot.ly/javascript/ "Plot.ly") was used to help create machine learning plots.
- [Butler University Data Analytics and Visualization Executive Education program](https://www.butler.edu/executive-education "Butler University Executive Education program") and instructors for assistance.
- Hat tip to Triology Education Services for providing the challenge guidelines.
- Partially inspired by the Oscar nominated documentary [HoneyLand](https://www.imdb.com/title/tt8991268/ "IMDB's Honeyland page")


## Copyright
:copyright: 2020 Ben Reiff, Chelsea Snedden, Michael R. Davis, Morgan Bricker. All Rights Reserved.
- - -