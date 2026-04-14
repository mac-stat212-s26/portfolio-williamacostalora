
# ggplot2 Visual Guide

## Grammar of Graphics
### Mapping Variables to Aesthetics
#### Position
#### Color
#### Size
#### Shape

## Basic Structure
### ggplot(data, aes(x,y))
### geom_*()
### Additional layers (+)

## Core Components
### Data
#### data.x
### Aesthetics (aes)
#### Mappings
### Geoms
#### Visual Representation

## Two Variables
### Animation
#### geom_smooth
### Aesthetics
#### color_continuous
#### title
#### subtitle
#### x, y, z labels
#### caption

## Stacked Bar (2 categorical vars)
### position = 'stack'
### position = 'dodge'
### position = 'fill'
### Reverse proportion

## Faceting (Small Multiples)
### Split into subplots by axes
### facet_wrap(~category)
### facet_grid(rows~cols)
#### Options: free_x/free_y
### facet_wrap(~vars)

## Aesthetics Reference
### x, y position
### color (outline color)
### fill (fill color)
### shape (point shape)
### size (point/line size)
### alpha (transparency)
### linewidth (line thickness)

## Single Variable Plots
### One var
### ggplot() + geom_histogram()
### + facet

## Global vs Local Mapping
### Global (variables by all layers)
#### aes() at ggplot(data, aes(x,y, color))
### Local (specific to one geom)
#### geom_point(aes(color=geom))
#### geom_smooth()

