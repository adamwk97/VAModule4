# Module 4 - Visual Analytics Patterns

For this assignment, I have chosen to use a dataset containing over 15000 video game sales by number of copies sold. Since the dataset was rather large, I subsetted it to the top 300 and have decided to sort the data by the number of copies sold (in millions) by each publisher. 
The data set I have used can be found below. 

```
initialdf = read.csv("https://www.dropbox.com/s/30k3noix2dp8vh7/video_game_sales.csv?dl=1", row.names=NULL)

df = initialdf[1:300,]
```
After subsetting the data, importing it into Tableau Public and experimenting, I created the following two graphics. The first one is a simple bar chart showing the volume of copies sold by the most popular publishers. This graph may be useful because it quickly and clearly captures which publishers have sold the most copies. This is a very straightforward graph that is simple yet effective. 

![graph1](./images/videogamesalesbar.png)

The second graph I created using Tableau Public was a bubble chart. This graph is unique from the bar chart, and most other graphs for that matter, as it focuses more on visual appeal and popping rather than numbers and informative details. However, this graph is also simple yet effective as it takes no more than a quick glance to see relatively how popular and how many copies have been sold from each publisher.

![graph2](./images/videogamesalesbubble.png)

[Visit my GitHub Profile](https://github.com/adamwk97)
