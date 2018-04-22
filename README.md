# boston_results
Scrapping and visualizing Boston Marathon Results

There is a notebook that was used to scrape the results for all finishers of the Boston Marathon 2016.

A second notebooks is used to analyse some of the results.

I have added the list with the results that were taken.


add/changesto scrape.ipynb: 
changed all 2016 dates to 2018
df = pd.DataFrame(data, columns=columns)
df.to_csv(filename, index=False, encoding='utf-8')

DataFrame insstance was missing
encoding needed to satisfy non-ascii character error

