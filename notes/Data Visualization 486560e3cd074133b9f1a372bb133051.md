# Data Visualization

## Types of Variables

- Continuous Variables
    - Usually numbers, (the things that we can do arithmetic on)
    - Examples: heights, temperatures, revenues
- Categorical Variables
    - Usually Text, (the things that can be classified)
    - Examples: Eye colors, countries, industry
- Can be either (depends on the given problem)
    - age is continuous, but age group is categorical
    - time is continuous, but month of year is categorical
    - In such cases, we have the freedom to treat them as either continuous or categorical depending on the question that we try to answer.
    

## Visualizing Distributions (single variable)

---

[Histogram](Data%20Visualization%20486560e3cd074133b9f1a372bb133051/Histogram%20a6644922ea3842859bed632e8f60c19f.md)

[Box Plot](Data%20Visualization%20486560e3cd074133b9f1a372bb133051/Box%20Plot%208d039219a39e4ba99ed2f16f4b5ec395.md)

## Visualizing Two Variables

---

[Scatter Plot](Data%20Visualization%20486560e3cd074133b9f1a372bb133051/Scatter%20Plot%20596001ca41cc4517bc8edc600cc8baf2.md)

[Line Plot](Data%20Visualization%20486560e3cd074133b9f1a372bb133051/Line%20Plot%209a5c85a352964965ac6f63382c78d7c7.md)

[Bar Plot](Data%20Visualization%20486560e3cd074133b9f1a372bb133051/Bar%20Plot%20b242f30d30ac4b2da3bd3132284287a4.md)

[Dot Plots](Data%20Visualization%20486560e3cd074133b9f1a372bb133051/Dot%20Plots%20e95ac6c1fd704566a109cdcdbbc02cf5.md)

We can can add color and shape to make our data visualizations clearer and easier to understand, especially when you find yourself working with more than two variables at the same time. 

The colorspace defined for data visualization is called hue-chroma-luminance (HCL). It is designed to deal with the issues of color perception. 

Hue is like the color of the rainbow. 

Chroma is the intensity of the color.

Luminance is the brightness of the color.

When choosing the colors for the plot, we can choose one of three types of color scales.

1. qualitative
    
    Purpose: Distinguish unordered categories
    
    What to vary ?: hue
    
2. sequential
    
    Purpose: Show ordering
    
    What to vary?: Chroma or luminance
    
3. diverging
    
    Purpose: emphasize whether values are greater than or less than some middle value 
    
    What to vary?: Chroma or luminance, with 2 hues.