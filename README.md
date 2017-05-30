# The Moving Epidemics Method Shiny Web Application

[![Travis Build Status](https://travis-ci.org/lozalojo/memapp.svg?branch=master)](https://travis-ci.org/lozalojo/memapp)
[![Coverage Status](https://img.shields.io/codecov/c/github/lozalojo/memapp/master.svg)](https://codecov.io/github/lozalojo/memapp?branch=master)
[![monthly](http://cranlogs.r-pkg.org/badges/memapp)](https://www.rpackages.io/package/memapp) 
[![total](http://cranlogs.r-pkg.org/badges/grand-total/memapp)](https://www.rpackages.io/package/memapp)
[![CRAN](http://www.r-pkg.org/badges/version/memapp?color=009999)](https://cran.r-project.org/package=memapp)
[![License](https://img.shields.io/badge/license-GPL%20%28%3E=%202%29-lightgrey.svg?style=flat)](http://www.gnu.org/licenses/gpl-2.0.html)

## Overview

*memapp* is a web application created to serve as a graphical user interface for the R mem library. It was created using Shiny, a web application framework for R. This application uses the development version of the mem R library.

## Installation

Currently there is no CRAN version of the *memapp* library, so it has to be installed from its source.

```
# install the devtools package:
install.packages("devtools")
# install the memapp development version from GitHub:
devtools::install_github("lozalojo/memapp")
```

## Usage

To run the memapp application, just use the function:

```
# run the app:
memapp::runmemapp()
```

You can specify other parameters passed to `shiny::runApp`, such as `display = normal`, or  
`launch.browser = TRUE`.

## More on the memapp

There are two documents that you will find useful when running the app:

1.  The *surveillance Guidelines*.
    
1.  The *Technical Manual*.

Both are included in the help menu of the application.

## References

Vega T., Lozano J.E. (2004) Modelling influenza epidemic - can we detect the beginning 
and predict the intensity and duration? International Congress Series 1263 (2004) 
281-283.

Vega T., Lozano J.E. (2012) Influenza surveillance in Europe: establishing epidemic 
thresholds by the Moving Epidemic Method. Influenza and Other Respiratory Viruses, 
DOI:10.1111/j.1750-2659.2012.00422.x.
