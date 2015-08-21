# Developing-Data-Products

Histogram visualize the distribution of child heights.

Used slider to vary the bin size of the histogram.

Shape of the histogram showing the child's height distribution varies accordingly.

Download the server.R and ui.R files and place them in a directory named 'Explore Galtons Child Data'. Open an R session and set the working directory to the folder that contains the directory 'Explore Galtons Child Data'. Then run the following commands:

library(shiny)

runApp('Explore Galtons Child Data')

Press esc to resume R session.


------------------------------------------------------
Could not publish on Rstudio server.
used devtools::install_github('rstudio/shinyapps') but always gave me error:

Warning in library(pkg_name, lib.loc = lib, character.only = TRUE, logical.return = TRUE) :
  there is no package called 'shinyapps'
Error: loading failed
Execution halted
