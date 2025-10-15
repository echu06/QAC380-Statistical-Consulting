# QAC380-Statistical-Consulting

penguins.xlsx

library(readxl)
library(skimr)
penguins <- read_excel("penguins.xlsx")

summary(penguins)
skim(penguins)

