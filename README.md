# web_scraping_challenge

This two_part challenge uses jupyter notebooks, BeautifulSoup, and Splinter to gather data about Mars from web pages. It then does some statistical analysis of the data collected, using Pandas, and uses matplotlib to plot some of the analyses.

Part 1, "part1_mars_news.ipynb", collects news article titles and previews from a static web page that was designed for scraping and prints the titles and a preview snapshot of each article.

Part 2, "part2_mars_weather.ipynb", collects Mars weather data from a table on a different web page, also designed for scraping, formats the data, conducts some analysis on it, creates five plots, and saves the collected data to a .csv file, 'mars_weather.csv", in the "output" subfolder.  All of the results of the analyses are contained in the jupyter notebook.  The output file will be created if it does not exist, or overwritten if it does, but the output directory must exist in advance.

The code is designed such that the jupyter notebook should be started from the directory where the scrript files are stored.  

A freely-downloadable version of "chromedriver.exe" is included in the package, in the subfolder "chromedriver".  Our instructor suggested that it is better practice to distribute it this way in a production environment, where different versions might be needed for different projects.  These notebooks expect it to be found there.

The analyses are statistical except for the last one, which is based on visual observation of a temperature data plot, and estimatino, per the challenge requirements, but matches quite closely with reported data from NASA.  The estimate created is within 10% of the actudal number, and the project requirements were to be wihin 25%.  A more finely-detailed set of grid lines might have made the estimate more precise, but would have made the plot much more cluttered and difficult to view, and was outside the scope of the requirement.  The numbers of martian days and months, in conjunction with the terrestrial date in the data table, also could have been used with a lot more coding to create a mathematical estimate.

While many more markdown cells were added, the detailed markdown cells from the starter code are all included exdept the last one, which contained a plot within it.  The list comprehensions to process through the rows and then through the fields in a row were written after a review of multiple questions about this in stack overflow.




