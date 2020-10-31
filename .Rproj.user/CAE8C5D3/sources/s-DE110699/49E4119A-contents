library(palmerpenguins)
library(ggplot2)
library(dplyr)
library(viridis)

out <- penguins %>%
  group_by(island)

ggplot(penguins, aes(bill_length_mm, bill_depth_mm))+
  geom_point(aes(colour=sex))+
  scale_color_viridis(discrete=TRUE)

print("Anda pepperoni pizza or two or three")
