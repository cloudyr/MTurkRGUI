# A Graphical User Interface for MTurkR #

**MTurkRGUI** provides a graphical user interface for [MTurkR](http://cran.r-project.org/package=MTurkR).

## Installation ##

[![CRAN Version](http://www.r-pkg.org/badges/version/MTurkRGUI)](http://cran.r-project.org/package=MTurkRGUI)
![Downloads](http://cranlogs.r-pkg.org/badges/MTurkRGUI)
[![Travis-CI Build Status](https://travis-ci.org/leeper/MTurkRGUI.png?branch=master)](https://travis-ci.org/leeper/MTurkRGUI)

To install the latest development version of **MTurkRGUI** from GitHub:

```R
# latest stable version
install.packages("MTurkRGUI", repos = c(getOption("repos"), "http://cloudyr.github.io/drat"))

# latest (unstable) version from GitHub
if(!require("devtools")){
    install.packages("devtools")
    library("devtools")
}
install_github("leeper/MTurkRGUI")
```

To install the latest version from CRAN, simply use:

```R
install.packages("MTurkRGUI")
```

## Using **MTurkRGUI** ##

The MTurkR documentation files contain minimal examples for all functions. Further examples of how to use MTurkRGUI are provided in [the MTurkR GitHub wiki](https://github.com/leeper/MTurkR/wiki). Users can contribute their own examples or further documentation there, or via pull requests to the GitHub repository.

If you experience problems using MTurkRGUI, you can:
  
  - [Report issues on Github](https://github.com/leeper/MTurkRGUI/issues)
  - Contact the package maintainer [via email](mailto:thosjleeper@gmail.com) or on [Twitter](https://twitter.com/thosjleeper)

[![cloudyr project logo](http://i.imgur.com/JHS98Y7.png)](https://github.com/cloudyr)
