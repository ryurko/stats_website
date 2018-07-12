+++
date = "2017-09-23T00:00:00"
title = "nflWAR: A Reproducible Method for Offensive Player Evaluation in Football"
abstract = "Unlike other major professional sports, American football lacks comprehensive statistical ratings for player evaluation that are both reproducible and easily interpretable in terms of game outcomes. Existing methods for player evaluation in football depend heavily on proprietary data, are not reproducible, and lag behind those of other major sports. We present four contributions to the study of football statistics in order to address these issues. First, we develop the R package nflscrapR to provide easy access to publicly available play-by-play data from the National Football League (NFL) dating back to 2009. Second, we introduce a novel multinomial logistic regression approach for estimating the expected points for each play. Third, we use the expected points as input into a generalized additive model for estimating the win probability for each play. Fourth, we introduce our nflWAR framework, using multilevel models to isolate the contributions of individual offensive skill players, and providing estimates for their individual wins above replacement (WAR). We estimate the uncertainty in each player’s WAR through a resampling approach specifically designed for football, and we present these results for the 2017 NFL season. We discuss how our reproducible WAR framework, built entirely on publicly available data, can be easily extended to estimate WAR for players at any position, provided that researchers have access to data specifying which players are on the field during each play. Finally, we discuss the potential implications of this work for NFL teams."
abstract_short = ""
event = "New England Symposium on Statistics in Sports"
event_url = "http://nessis.org/"
location = "Harvard University"

selected = false
math = true

url_pdf = "pdf/nflWAR.pdf"
url_slides = "pdf/NESSIS_nflWAR.pdf"
url_video = "https://www.youtube.com/watch?v=djD-yL3vWNQ"
url_custom = [{name = "Pitt talk", url = "pdf/nflWAR_pitt_class.pdf"}]
#url_custom_2 = [{name = "Great Lakes", url = "pdf/greatlakes_2017.pdf"}]


# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++