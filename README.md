# Insights of A City Through the Eyes of Airbnb Reviews: Inferring Urban Characteristics from Homestay Guest Experiences

The Jupyter notebooks are the python code that cleans the raw review data retrieved from Inside Airbnb, retains only English reviews, and performs the NLP task.

The main function in .ipynb files is ```aspect_description(text)```. This is a self-define dependency parsing tool, which extracts the root word/nominal subject/direct object of a sentence, along with its descriptive word. Auxiliary words are excluded for higher accurary.

The Rmarkdown(.rmd) files are subsequent statistical/spatial analysis conducted in R language. Analysis includes: correlation, spatial-autocorrelation. ggplot is employed to generate plots for the visualization purpose of my thesis work.
