# TopicAll
Interfaces and extensions for common topic modeling libraries

# Motivation
The motivation behind TopicAll is that the best topic modeling libraries like OCTIS, Tomotopy, and Gensim have different input formats, class interfaces, and so forth.  This is an attempt to create a standard library for my own usage and, possibly, yours as well.  This little project is still in ideation... I'm thinking through what would best allow me to create a topic model pipeline with a minimum of fuss to swap models in and out for comparison and (possibly) ensembling. 

When I worked on a topic model pipeline as part of my MSDS capstone at Northwestern Univeristy, I had to create a model superclass with subclasses that reflected the package from which the model was drawn and then these were further subclassed to the models.  This class hierarchy didn't reflect anything functional or a phylogensis of the models themselves, but rather the original models' authors' architectural choices. 
