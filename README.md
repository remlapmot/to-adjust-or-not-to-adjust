
<!-- README.md is generated from README.Rmd. Please edit that file -->

# to-adjust-or-not-to-adjust

R Shiny App demonstrating different scenarios about adjusting for
covariates in statistical models when the underlying data generating
process is different.

## Building the app

To build the app, either

-   open the project in RStudio, open `to-adjust-or-not-to-adjust.Rmd`
    and click the *Run Document* button

-   or, run the following code in R

    ``` r
    rmarkdown::run('to-adjust-or-not-to-adjust.Rmd')
    ```

## App URL

The app is deployed at
<https://remlapmot.shinyapps.io/to-adjust-or-not-to-adjust/>

<img src="img/qrcode.svg" width="33%" />

### To deploy (and update) to shinyapps.io

-   Click the *Publish* button (blue circle in top right corner of
    Source pane) and follow subsequent instructions to connect your
    shinyapps.io account

-   Or, in RStudio go to: Tools \| Global Options \| Publishing; and
    Connect shinyapps.io account and then run

    ``` r
    rsconnect::deployApp()
    ```
