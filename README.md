
# R_on_Cloud_Web_API

Run following Steps :
1) Install R on machine.
2) $ chmod +X packageinstall.sh
3) $ ./packageinstall.sh
4) $ Rscript run.R
5) Check in browser http://127.0.0.1:8001/__swagger__/

**----------------------------------------------------------------------------**

**Run on local R console:**
R version 3.4.4
 
  **Requirements preinstalled R packages:**
  
    1) install.packages("plumber") 
    2) install.packages("jsonlite") 
    3) install.packages("readr") 
    4) install.packages("futile.logger") 
    5) install.packages("tryCatchLog")
    6) install.packages("ggplot2") 
**----------------------------------------------------------------------------**
    
    #run.R
    > library(plumber)
    > r <- plumb("plumber.R")  # Where 'plumber.R' is the location of the file shown above
    > r$run(port=8001)


**Developer:**

    Prashant Sinalkar,
    FOSSEE, IIT Bombay






