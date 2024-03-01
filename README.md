This R markdown file was written to automate the retrival of data from Clickup (a web-based productivity website) for creating plots of Quality metrics over time.  Each week, the script is run and creates a cumilative look at data trends for leadership to monitor Quality KPIs over time.

For privacy reasons, the authorization token "pk_" has been omttied from the script.  If the code is run in notebook, the execution will not work propoerly.  The package used (ClickRUp by Peter Solymos (https://github.com/psolymos/clickrup)) calls upon the locations of lists that are specific to the private Clickup space folders.

The code is an demonstration of how I was able to use Peter Solymos' R package, in addition to the tidyverse package, to extract data tracked on the Clickup app and automate the creation of weekly line charts, thereby removing the need for manual repetition by an engineer.
