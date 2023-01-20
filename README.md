# module-11


Deliverable 1: Scrape titles and preview text from Mars news articles.
file name: part_1_mars_newsRL.ipynb

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.
file name: part_2_mars_weatherRL.ipynb


#########################
For weather table in part 2:
Column name meanings:

  id: the identification number of a single transmission from the Curiosity rover
  terrestrial_date: the date on Earth
  sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
  ls: the solar longitude
  month: the Martian month
  min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
  pressure: The atmospheric pressure at Curiosity's location

Questions addressed in the analysis:

  How many months exist on Mars?
  How many Martian (and not Earth) days worth of data exist in the scraped dataset?
  What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    Find the average minimum daily temperature for all of the months.
    Plot the results as a bar chart.
  Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
    Find the average daily atmospheric pressure of all the months.
    Plot the results as a bar chart.
  About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    Consider how many days elapse on Earth in the time that Mars circles the Sun once.
    Visually estimate the result by plotting the daily minimum temperature.

exported into csv file:
