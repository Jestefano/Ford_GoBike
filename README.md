# Ford_GoBike

The dataset that I chose was from Ford GoBike. I tried to think questions that are related to how to make more profit out of the data that we have already collected, that is, questions like how to target your main audience with advertisement or in which place we should offer our services (since there is more demand in them).

### Instructions:
You should download manually the data from 2019 and put it into the same folder as this one.

### Findings:

My main findings from the exploratory analysis are the following:

1) Around 99.9% of people from the data was born after 1940. I chose to focus to portrai this information in two different ways, one of the was numerically, since the amount of data is such impresive number I decided that it is helpful to maintain this number in mind to understand the decition that I took to focus on the right part of the graph (after 1940). The other way that I decided to portray this information was with a histogram. I did this because it is notorious that the data is concentrated in the right part of the graph with the bars.

2) The graph of member_birth_year is left skewed with maximum around 1987. As I explained in the previous point, since almost all the data is concentrated from 1940 to 2005 I decided to focus on this interval. As the graph suggest, there is a left skewed behavior. This was impossible to see in that detail in the previous graph, because of that this was the right choice to make. Also, I played around with the bin sizes to get the one that favours my conclusion the most.

3) The distribution of the start and end position are almost identical. With a big concentration around (37.78,-122.40). First I focused on the outsiders, since there is data missing (I assumed that they put the coordinates (0,0) to portray that) I deleted them. Then, I put the two graphs in paralel to see what are the main differences between them. The decision of the graph was mainly because I was using two variables. There was another alternative that I did not take, which is a scatter plot using different colors. I did not use it because the amount of data is really large. Because of that I decided to split the graph into two different parts.

4) The main focus of the next graph (and next finding) is the fact that even though we look at two different groups, their consumption might be different in the sense of time. So in order to verify that I plotted the graph of the city and checked the density of the consumption per point. As I noted the consumption and the density of the consumption are different from the amount of data that we have.

Resources:

- Udacity Data Analyst program.
- Documentation from matplotlib
- https://github.com/hakimel/reveal.js#installation
