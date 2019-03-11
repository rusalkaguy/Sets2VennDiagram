# Sets2VennDiagram
Create Venn Diagrams from List of 2-5 sets of IDs

```R
# 
# load
#
require(devtools)
devtools::install_github("rusalkaguy/Sets2VennDiagram")
library(Sets2VennDiagram)
#
# test
#

# show docs
?Sets2VennDiagram::vennSets

# simple Venn
Sets2VennDiagram::vennSets(list(A=1:5,B=3:7),set.col=c("A"="red", "B"="blue"))
```

