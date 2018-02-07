# swirl course for ECON 452 at UMass Amherst

This is a swirl course, for now mostly covering Data Manipulation.

The course and most of its content is adapted from the developers of the swirl package. Check out their [website](http://swirlstats.com) and [swirl GitHub repository](https://github.com/swirldev/swirl).

## Install and run the course

1) Make sure you have a recent version version of swirl:

```
install.packages("swirl")
```

2) Enter the following from the R console:

```
library(swirl)
install_course_github('noew','econ452_swirl')
swirl()
```

3) If you encounter an error message, try the following option:

a. Go to (https://github.com/noew/econ452_swirl), and click on [Clone or Download], then choose [Download ZIP].
b. Save the file in your working directory (remember that you can set your working directory using the Files tab in RStudio)
c. In the R console, type the following:

```
install_course_zip("econ452_swirl-master")
swirl()
```

## Uninstall the course

If you'd like to remove a course at any time, you can use `uninstall_course("econ452_swirl")`.
