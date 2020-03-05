# Sample website wth basic data summary and visualization
Link to the webpage here: https://davidneedsmorecoffee.github.io/Web-Design-Challenge/WebVisualizations/index.html

### Using a previously analyzed data set based on weather data 
* `Resources/cities.csv`
* https://github.com/davidneedsmorecoffee/python-and-api-for-weather-and-vacation-destination-analysis)

### A visualization dashboard website was created. Here's the breakdown of the website:
* 7 pages total
  *Each page will contain visualizations and their corresponding explanations

    * 1 `Landing` page:
      * Explanation of the project.
      * Links to each visualizations page.
    * 4 `Visualization` pages:
      * The plot/visualization itself for the selected comparison.
      * Interpretation of the plot and its significance.
    * 1 `Comparisons` page:
      * Contains all of the visualizations on the same page for easy visual comparison.
      * Bootstrap grid was used for the visualizations.
        * The grid was sized to display two visualizations across on large and medium screens, or one visuzliation across on extra-small and small screens.
    * 1 `Data` page:
      * Displays a responsive table containing the data used in the visualizations.
        * The table was made with bootstrap table component.
        * The data was based on conversion of `.csv` file to HTML via pandas.

### Other small features of the website include:
  * Home button in the top left corner to return to the landing page from any page.
  * Dropdown `plots` menu on the top right corner which provides links to each individual visualization page.
  * Links on the top right to access the `Comparisons` or `Data` pages
