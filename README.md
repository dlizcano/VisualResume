
<!-- README.md is generated from README.Rmd. Please edit that file -->
VisualResume
============

The `VisualResume` package contains the `VisualResume.R` function which produces a Visual resume like the one below:

``` r
VisualResume::VisualResume(
 titles.left = c("Diego J. Lizcano, PhD", "Wildlife biology, mammals, photography", "*Built with love in R using the InfoResume package: www.ndphillips.github.io/inforesume"),
titles.right = c("www.lospolloshermanos.com", "dj.lizcano@gmail.com", "Full Resume: dlizcano.github.io"),
titles.right.cex = c(2, 2, 1),
titles.left.cex = c(4, 2, 1),
timeline.labels = c("Education", "Teaching"),
timeline = data.frame(title = c("Grinnell Col", "Ohio U", "U of Basel", "Max Planck Institute", "Old Van", "Gray Matter", "Sandia Laboratories", "J.P. Wynne High School", "A1A Car Wash"),
                      sub = c("BA. Student", "MS. Student", "PhD. Student", "PhD. Researcher", "Methamphetamine Research", "Co-Founder", "Chemist", "Chemistry Teacher", "Co-Owner"),
                      start = c(1976, 1980.1, 1982.2, 1985, 1996.5, 1987, 1991, 1995, 2001),
                      end = c(1980, 1982, 1985, 1987, 1998, 1992, 1995, 1998, 2003),
                      side = c(1, 1, 1, 1, 1, 0, 0, 0, 0)),
milestones = data.frame(title = c("BA", "MS", "PhD"),
                        sub = c("Mathematics", "Chemistry", "Chemistry"),
                        year = c(1980, 1982, 1985)),
events = data.frame(year = c(1985, 1995, 1997, 1999, 2012),
                    title = c("Contributed to Nobel Prize winning experiment.",
                              "Honorary mention for best Chemistry teacher of the year.",
                              "Created Blue Sky, the most potent methamphetamine ever produced.",
                              "Made first $1,000,000.",
                              "White, W., & Pinkman, J. (2012). Blue Sky: A method of [...].\nJournal of Psychopharmical Substances, 1(1),.")),
interests = list("programming" = c(rep("R", 10), rep("Python", 1), rep("JavaScript", 2), "MatLab"),
                 "statistics" = c(rep("Decision Trees", 10), rep("Bayesian", 5), rep("Regression", 3)),
                 "leadership" = c(rep("Motivation", 10), rep("Decision Making", 5), rep("Manipulation", 30))),
year.steps = 2
)
```

![](README-unnamed-chunk-2-1.png)

You can install `VisualResume` from GitHub as follows:

``` r
#install.packages("devtools") # Only if you don't have the devtools package
devtools::install_github("ndphillips/VisualResume")
```
