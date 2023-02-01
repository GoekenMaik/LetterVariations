# LetterVariations

Simple Jupyter board to extract the most likely letter variations out of a list of first names, e.g. (d-t), (a-e), for example
the letter variation the first names "Anna" and "Anne" is (a-e)/(e-a).
Visualises results in a heatmap.
Comes with an additional Wikipedia Scraper to download firstnames from a list of categories.

University Project for the following task:
Derive a substitution matrix for common letter variations.
A substitution matrix is a matrix that describes the rate at which a letter is replaced with another
letter (e.g. d-t,p-b, etc.)

# Requirements 
Uses NumPy, matplotlib, seaborn, mediawiki and Levenshtein libraries.
The downloaded names are in the file names.dat
Each name should be on it's own line

# Example Output
![LetterVariations](output.png)