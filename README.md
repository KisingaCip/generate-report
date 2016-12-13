This app generates a downloadable report when the download button is clicked. It uses a .Rmd file to generate the report. [Source code](https://github.com/rstudio/shiny-examples/tree/master/112-generate-report). Note that this app uses a temporaray directory because the app directory might not be writable when deployed.

Run this app locally with the following command:

```r
shiny::runGitHub('generate-report', 'bborgesr')
```