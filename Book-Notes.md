# Notes
## 1. Introduction
Process:
Import -> Tidy -> Explore (Cycle: Transform -> Visualize -> Model -> Transform) -> Communicate

### plotting
ggplot(data = \<DATA>) + \<GEOM_FUNCTION>(mapping = aes(\<MAPPINGS>))

## Exercise
1. Run ggplot(data = mpg) what do you see?
2. How many rows are in mtcars? How many columns?
3. What does the drv variable describe? Read the help for ?mpg to find out.
4. Make a scatterplot of hwy vs cyl.
5. What happens if you make a scatterplot of class vs drv. Why is the plot not useful?
