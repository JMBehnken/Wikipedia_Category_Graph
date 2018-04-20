# Wikipedia_Category_Graph
Which topics can be associated with Wikipedia-Articles?

Each Wikipedia-Article is linked to some categories.
By moving up this category-tree-structure, a main-article can be associated with many related topics.

This notebook scrapes the categories of any Wikipedia-Article and stores their connections to each other in a csv-file. 
The file can be used to plot and compute the corresponding graph with the program gephi

Since a large article is an enormous task for a single core, a multiprocessing solution with many cores can be utilized.
