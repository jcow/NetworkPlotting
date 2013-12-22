#NetworkPlotting

This project was created for my data visualization class during fall 2013 where we needed to explore a network dataset.  For this I chose to 
use Donald Knuth's world ladder data for five-letter words.  The two html files are a query tool that were built to explore and visualize the dataset.

##word_ladder.html
This is a system that has the ability to show a person how to get from one five-letter word to another.  This system will show the user the transition
of words via a colorization of the words and also by showing them on a circular plot.  The circular plot is sorted by it's degree in the graph.

##graph_exploration.html
Turns out that not all the five-letter words supplied by Knuth can reach one another.  This system shows how many graphs are formed from the words
and how they are connected.

edges_to_score.png
In this plot I was comparing the degree of a node in the graph to its score.  A score is defined as the average percentage from each of the words' characters and
their frequency in English.  This was obtained from [Wikipedia's letter frequency page](http://en.wikipedia.org/wiki/Letter_frequency).