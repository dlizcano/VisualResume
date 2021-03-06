
<!-- README.md is generated from README.Rmd. Please edit that file -->
VisualResume
============

The `VisualResume` package contains the `VisualResume.R` function which produces a Visual resume like the one below:

``` r

VisualResume::VisualResume(
 titles.left = c("Diego J. Lizcano, PhD", "Wildlife biologist, Mammals, Photography", "*Built with love in R using the VisualResume package: https://github.com/ndphillips/VisualResume"),
titles.right = c("WebSite: http://dlizcano.github.io", "email: dj.lizcano@gmail.com", "Full Resume: http://dlizcano.github.io/about"),
titles.right.cex = c(2, 2, 1),
titles.left.cex = c(4, 2, 1),
timeline.labels = c("Education ", "Teaching - Reseach"),
timeline = data.frame(title = c("Los Andes U. (COL)", "Los Andes U. (COL)", "Kent U. (UK)", "Pamplona U. (COL)", "World Bank", "CI (USA)", "CSF", "ULEAM (ECU)", "ULEAM (ECU)", "TNC (COL)"),
                      sub = c("BSc. Student", "Research Assistant", "PhD. Student", "Researcher-Professor",  "Consultant", "Visiting Scientist", "Research Fellow", "Project Leader", "Profesor", "Biodiversity specialist"), # wordl bank and CI are troked for display
                      start = c(1990, 1996  , 2001, 2006  , 2012.1, 2012.1, 2013, 2014.2, 2015.2, 2016.2),
                      end = c(1996.1, 2001, 2006, 2012.1, 2013.2, 2012.2, 2014, 2015.2, 2016, 2018),
                      side = c(1, 0, 1, 0, 1, 1, 0, 1, 1, 0)), # 1 arriba, 0 abajo
milestones = data.frame(title = c("BSc",  "PhD"),
                        sub = c("Biology",  "Biodiversity Management"),
                        year = c(1996,  2006)),
events = data.frame(year = c(2000, 2001, 2002, 2003, 2013, 2015),
                    title = c("Lizcano, D. J., &  Cavelier J. 2000. Biotropica 32:165 173.",
                              "Lizcano, D. J., &  Cavelier J. 2000. Journal of Zoology 252:429 435.",
                              "Lizcano et. al., 2002. Journal of Biogeography 29:7 15.",
                              "Lizcano, D. J., & Cavelier J. 2004. Tapir Conservation 13:18–23.",
                              "Ahumada, J. A., J. Hurtado, and D. Lizcano. 2013. PLoS ONE 8:e73707.",
                              "Ortega-Andrade, H. M., Prieto-Torres, Ǵomez-Lora, and D. J. Lizcano. 2015.\nPLoS ONE 10:e0121137.")),
interests = list("programming" = c(rep("R", 19), rep("LaTex", 2), rep("HTML", 10), "Python - Julia"),
                 "Statistics" = c(rep("GLMM", 6), rep("Bayesian", 8), rep("Occu Models", 2), 
                                  rep("Random Forest", 3)),
                 "Capacity building" = c(rep("Motivation", 15), rep("Decision", 1), rep("Leadership", 10))),
year.steps = 2
)
```

![](README-unnamed-chunk-2-1.png)

You can install `VisualResume` from GitHub as follows:

``` r
#install.packages("devtools") # Only if you don't have the devtools package
devtools::install_github("ndphillips/VisualResume")
```
