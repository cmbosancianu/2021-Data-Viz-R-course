# Data Visualization with `R`: Principles and Practice

Over the last decade data visualization has become a topic of increasing focus and importance for a range of institutions and professions. Presenting ideas and insights using graphical tools has always been a core area of academic work. What we see in recent years, though, is the expansion of this practice in the routine work of international organizations, private-sector companies, and media outlets. A number of trends have driven this expansion: (1) an exponential increase in the public availability of data; (2) a considerable push in both the public and private sectors for evidence-based decision-making and quantifiable metrics for measuring success; (3) an increasing degree of familiarity with data-based arguments on the part of a greater share of the public; and (4) a greater need for public institutions, and even companies, to exhibit transparency toward stakeholders.

With rapid growth in any field, though, comes the difficulty of maintaining standards of quality. This is what this course tries to address. One of its main goals is to present students with a set of standards of good practice when assessing or creating data visualizations. At the same time, it is also intended to give students the tools with which to easily create such visualizations of their own. It will be a hands-on, practical course in *how to evaluate* and *create data visualizations*, based on *open-source* software and up-to-date datasets.

## Course Schedule

### Principles of good data visualization (May 5, Session 1)

We start by delving into a few of the guidelines and principles for how to create effective data visualizations.

Readings:

1. Tufte, Edward R. 2001. *The Visual Display of Quantitative Information*. Second edition. Cheshire, CT: Graphics Press. Chapters 4 and 6.
2. Healy, Kieran. 2018. *Data Visualization: A Practical Introduction*. Princeton, NJ: Princeton University Press. Chapter 1.

### `R` and the `tidyverse` ecosystem (May 5, Session 2)

In this session we explore the `tidyverse` ecosystem of `R` packages. These packages, and especially `dplyr`, are extremely helpful in preparing frequently messy online data for plotting.

Readings:
1. Healy, Kieran. 2018. *Data Visualization: A Practical Introduction*. Princeton, NJ: Princeton University Press. Chapter 2 (without 2.1).
2. *R Bootcamp*: Chapters 3 and 4. Available at: [https://r-bootcamp.netlify.app/](https://r-bootcamp.netlify.app/).

### Univariate and multivariate graphs (May 6, Session 3)

We start the applied portion of the class by going over the most typical types of graphs for univariate and multivariate data, and how to implement them in `ggplot2`. We cover histograms, bar charts, area plots, box-and-whisker plots, line charts, and scatterplots.

Readings:

1. Healy, Kieran. 2018. *Data Visualization: A Practical Introduction*. Princeton, NJ: Princeton University Press. Chapters 3 and 4.
2. Unwin, Antony. 2015. *Graphical Data Analysis with R*. Boca Raton, FL: CRC Press. Chapters 3, 4 and 5.

### Customizing graphs (May 6, Session 4)

Most graphs intended for public release require heavy customization. In this session we advance by going beyond the `ggplot2` defaults: (1) using colors, shapes and sizes to encode more information into the plot; (2) faceting; (3) highlighting specific data points; and (4) "cleaning up" a plot to highlight the information we want conveyed.

Readings:

1. Healy, Kieran. 2018. *Data Visualization: A Practical Introduction*. Princeton, NJ: Princeton University Press. Chapters 5 and 8.

### Designing maps with `ggmap` (May 7, Session 5)

Presenting spatial data and displaying it under the form of maps has recently been made much easier by the launch of the `ggmap` package. In this session we go over how to create maps with the `ggmap` package, and how to present information at different levels of aggregation.

Readings:

1. Healy, Kieran. 2018. *Data Visualization: A Practical Introduction*. Princeton, NJ: Princeton University Press. Chapter 7.
2. Kahle, David, and Hadley Wickham. 2013. "`ggmap`: Spatial Visualization with `ggplot2`." *The R Journal* **5**(1): 144–161.

### Graphs derived from model output (May 7, Session 6)

In the final session, we cover the creation of graphs from statistical model output in order to convey our model-based insights to a wider audience. We learn how to plot regression coefficients, predictions from the data, as well as how to present uncertainty about our conclusions.

Readings:

1. Healy, Kieran. 2018. *Data Visualization: A Practical Introduction*. Princeton, NJ: Princeton University Press. Chapter 6.
2. Kastellec, Jonathan P., and Eduardo L. Leoni. 2007. "Using Graphs Instead of Tables in Political Science." *Perspectives on Politics* **5**(4): 755–771.


## Additional Readings

For more advanced topics related to using `R` for producing graphs, more sophisticated types of data visualizations, as well as the specific challenges pertaining to graphically displaying very large quantities of information, please consult one of the relevant references below.

- Chen, Chun-houh, Wolfgang Härdle, and Antony Unwin. 2008. *Handbook of Data Visualization*. New York: Springer.
- Cleveland, William S. 1985. *The Elements of Graphing Data*. Monterey, CA: Wadsworth Advanced Books and Software.
- Tukey, John W. 1977. *Exploratory Data Analysis*. Reading, MA: Addison-Wesley.
- Unwin, Antony, Martin Theus, and Heike Hofmann. 2006. *Graphics of Large Datasets: Visualizing a Million*. New York: Springer.
- Wickham, Hadley. 2016. *`ggplot2`: Elegant Graphics for Data Analysis*. Second edition. New York: Springer.
- Wilkinson, Leland. 2005. *The Grammar of Graphics*. Second edition. New York: Springer.
- Cook, Dianne, Eun-Kyung Lee, and Mahbubul Majumder. 2016. "Data Visualization and Statistical Graphics in Big Data Analysis." *Annual Review of Statistics and Its Application* **3**: 133–159.
- Evergreen, Stephanie, and Chris Metzner. 2013. "Design Principles for Data Visualization in Evaluation." *Data Visualization, part II: New Directions for Evaluation* **140**: 5–20.
- Frees, Edward W., and Robert B. Miller. 1998. "Designing Effective Graphs." *North American Actuarial Journal* **2**(2): 53–76.
- Zeileis, Achim, Kurt Hornik, and Paul Murrell. 2009. "Escaping RGBland: Selecting colors for statistical graphics." *Computational Statistics & Data Analysis* **53**(9): 3259–3270.

There is also a vibrant community devoted to interactive data visualizations. Although we do not have the time in this course to cover this topic as well, if interested you can find out more about this in the following places:

- [https://master.bioconductor.org/help/course-materials/2015/CSAMA2015/lab/shiny.html](https://master.bioconductor.org/help/course-materials/2015/CSAMA2015/lab/shiny.html)
- [https://seankross.com/developing-data-products/shiny.html](https://seankross.com/developing-data-products/shiny.html)
- [https://shiny.rstudio.com/tutorial/](https://shiny.rstudio.com/tutorial/)
- [https://shiny.rstudio.com/images/shiny-cheatsheet.pdf](https://shiny.rstudio.com/images/shiny-cheatsheet.pdf)
- [https://shiny.rstudio.com/articles/](https://shiny.rstudio.com/articles/)