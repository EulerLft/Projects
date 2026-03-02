Life Expectancy and GDP: A Comparative Analysis
This project investigates the relationship between economic output (GDP) and human longevity across six distinct nations: Chile, China, Germany, Mexico, the United States, and Zimbabwe. Using Python, Pandas, and Seaborn, I analyzed fifteen years of data to determine if financial growth is the primary driver of life expectancy.

Project Overview

The core objective was to move beyond simple correlations and explore the distribution and volatility of both metrics. The project answers several key questions:
•	Has life expectancy and GDP increased over time for all nations?
•	Is there a consistent correlation between wealth and longevity?
•	How do extreme outliers in health and wealth impact our understanding of global development?

Key Analytical Findings
The most significant discovery in this project is the "decoupling" of economic scale and human health. While GDP often grows exponentially, life expectancy follows a biological ceiling.
•	Diminishing Returns: Chile, with an economy $1/65$th the size of the USA or China, maintains an equal or higher life expectancy. This suggests that once a survival threshold is met, trillions in additional GDP yield only marginal gains in lifespan.
•	The Zimbabwe Case Study: Between 2004 and 2008, Zimbabwe's GDP contracted by nearly $30\%$, yet life expectancy increased by three years. This inverse relationship proves that targeted public health interventions—addressing disease, famine, or conflict—are far more impactful than raw economic growth.
•	Distribution Mismatch: Life expectancy is heavily left-skewed, with a median of $76.75$ years. Conversely, GDP is extremely right-skewed, with a few "powerhouse" nations pulling the mean to $3x$ the median.

Data Visualizations
To reveal these insights, the project utilizes several advanced visualization techniques:
•	Log-Scale Transformations: Used to "unpack" GDP data and show the structured economic distribution hidden by extreme outliers.
•	Comparative Boxplots: Visualizes the tight four-year gap between the 25th and 75th percentiles of life expectancy compared to the massive $24$-fold spread in GDP for the same middle-50% of the population.
•	Time-Series Analysis: Tracks the recovery of outliers and the steady, incremental gains of developed nations.

Conclusion
The data suggests that for most nations, human longevity is governed by a stable biological ceiling and advancements in global medicine rather than exponential economic expansion. While GDP growth is necessary for basic development, it becomes a secondary factor once a nation moves past the initial survival threshold.

Technologies Used
•	Python: Core analysis
•	Pandas: Data manipulation and summary statistics
•	Seaborn/Matplotlib: Data visualization and distribution plotting
•	Jupyter Notebook: Interactive documentation and code execution
