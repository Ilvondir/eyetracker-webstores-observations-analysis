# Analysis of the effectiveness of product layout in online stores

The research focused on analyzing observations collected using the SMI RED 500 eyetracker. Participants, being tracked by the eyetracker, were tasked with viewing three different product layouts. The data thus obtained were used to create a script that would clearly list all the results of the research.

The data were processed using Python. Most of the data analysis was performed using the Pandas package. The results of the research were visualized using Plotly charts.

The research demonstrated that the grid layout is the least effective among the possible product arrangements, as users viewing such a page pay attention to fewer products compared to the carousel and list layouts. The stimulants are in the files [Grid.png](https://raw.githubusercontent.com/Ilvondir/eyetracker-webstores-observations-analysis/master/Grid.png), [List.png](https://raw.githubusercontent.com/Ilvondir/eyetracker-webstores-observations-analysis/master/List.png) and [Carousel.png](https://raw.githubusercontent.com/Ilvondir/eyetracker-webstores-observations-analysis/master/Carousel.png).

As part of the research, a script was also created that displayed user observations on a given stimulus in a three-dimensional space. These plots are located in the plots folder, and [here you can see an example of one of them](https://raw.githubusercontent.com/Ilvondir/eyetracker-webstores-observations-analysis/master/plots/plot2.1.png), also from a [different perspective](https://raw.githubusercontent.com/Ilvondir/eyetracker-webstores-observations-analysis/master/plots/plot2.2.png).

The research was conducted to fulfill the requirements of the course Selected Topics in Contemporary Computer Science in the Computer Science degree. The project was awarded a grade of 5.0 on a scale from 2 to 5.

## Used Tools
- Python 3.12.2
- Jupyter Notebook 6.29.4
- Pandas 2.2.2
- Plotly 5.21.0

## Requirements

For running the application you need:

- [Python](https://www.python.org/downloads/)

## How to run

1. Execute command `git clone https://github.com/Ilvondir/eyetracker-webstores-observations-analysis`.
2. Run all cells in `analysis.ipynb`.
3. Run all cells in `plots.ipynb`.
