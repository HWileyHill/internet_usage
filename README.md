CONTENTS OF THIS DIRECTORY:
* charts_internetusage.png - Two scatter plots from the Jupyter notebook, comparing Internet usage with the two other statistics provided in the dataset.
* dataset-cover.png - A copy of the infographic that accompanied the original dataset on Kaggle.
* gapminder_internet.csv - A copy of the dataset this analysis covers, exactly as downloaded from Kaggle.
* Internet Usage Notebook.ipynb - The Jupyter notebook that contains the bulk of my work.
* README.md - You are here!
* requirements.txt - A list of all the libraries and their versions I had installed when I created and ran this code.  Not all of them are required, but it is difficult to say which ones are or aren't.
* us_internet.png - A screenshot of a table from the Jupyter notebook, showing how the US ranks among its peers in terms of Internet usage.

TO RUN:
First, install Jupyter on your machine if you haven't already.  Then, open a command window, navigate to this directory, and run this command:
$ jupyter notebook
This should open up a new window in your web browser.  In it, click on "Internet Usage Notebook.ipynb" and you're on your way.  All the necessary packages and libraries are imported in the first code cell.

If this doesn't work, run this command (still from this directory) and then try again:
$ pip install -r requirements.txt

QUESTIONS THIS ANALYSIS ADDRESSES (AND THEIR ANSWERS, IN BRIEF):
* How does the developer's home country, the United States, rank among the other countries in terms of Internet usage?
** The United States ranks 26th, above China but below Japan, among others.
* The infographic depicts a mean Internet usage of 66.2%.  Can the dataset confirm or refute this number?
** No; essential information was omitted from the dataset that this calculation cannot be made without.
* Urban citizenship and GDP/capita are given in the dataset alongside Internet usage.  Do the former statistics correlate with the latter in any way?
** Yes, weakly but positively in both cases.
* Is it possible, using a machine learning model, to predict Internet usage from urban citizenship and GDP/capita?
** Yes, somewhat accurately in fact, with an r-squared of almost 75%.

ACKNOWLEDGEMENTS:
The Global Internet Usage dataset was collated by GapMinder, and is hosted on Kaggle.  It has a usability rating of 10.00, which means it is fully documented; it is also very clean and usable, save for some missing values.  It can be accessed through the following URL, which I advise checking out if you have further questions about the dataset:
https://www.kaggle.com/datasets/sansuthi/gapminder-internet
