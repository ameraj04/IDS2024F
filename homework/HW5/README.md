1. This answer has been uploaded.   

2. The three desiderata of Probability Theory are:
(I) Degrees of plausibility are represented by real numbers that means no negative number. 
(II) Qualitative correspondence with common sense.
(III) Consistency.
(a) If a conclusion can be reasoned out in more than one way, then every possible way must lead to the same result.
(b) We must always consider all the evidence relevant to a question. We should not arbitrarily ignore some information, basing the conclusions only on what remains.
(c) We must always represent equivalent states of knowledge by equivalent plausibility assignments. That is, if the state of knowledge is the same (except perhaps for labeling the propositions) in two problems, then it must assign the same plausibilities in both.  

3. All data visualizations map data values into quantifiable features of the resulting graphic. We call these features Aesthetics. Some examples are: Colors (used to differentiate between data groups/categories), Shapes (used to differentiate between data groups/categories),  Sizes (can indicate lower/higher values), Position (X and Y coordinates), Line width and Line type (solid, dotted), etc.   

4. The two types of Aesthetics are: 
1. Positional Aesthetic: Those that can represent continuous data. Continuous data values are values for which arbitrarily fine intermediates exist. These involve the placement of data points in a visual space, typically using the X and Y coordinates (or axes). Positional aesthetics are the primary means of showing relationships and trends between variables.
For example, time duration is a continuous value. Between any two durations, say 60 seconds and 61 seconds, there are arbitrarily many intermediates, such as 60.5 seconds, 60.51 seconds, 60.50001 seconds, and so on. 
2. Non-Positional Aesthetic: These involve visual properties that do not rely on the specific location of the data point but instead use other attributes to convey information.
For example, the number of people in a room is a discrete value. A room can hold 5 people or 6, but not 5.5. Non-positional aesthetics enhance the visualization by adding more dimensions of information, allowing the viewer to interpret additional variables without changing the position of the data points. For example, Color: Different hues to represent categories or gradient colors for continuous values, Size: To indicate magnitude or importance, as seen in bubble charts, Shape: Different symbols or markers to distinguish between groups or categories.

5. The two major types of data are:
1. Qualitative Data (or Categorical Data)
•	Definition: Qualitative data describes characteristics, categories, or qualities. It is non-numeric and often involves attributes or labels that describe a particular quality or classification.
•	Examples:
o	Nominal Data: Categories without any natural order or ranking. Example: Types of fruits (apple, banana, orange).
o	Ordinal Data: Categories with a natural order or ranking. Example: Customer satisfaction ratings (poor, fair, good, excellent).
2. Quantitative Data (or Numerical Data)
•	Definition: Quantitative data represents numerical values that can be measured or counted. It describes quantities and can be used for arithmetic calculations.
•	Examples:
o	Discrete Data: Countable values, often whole numbers. Example: Number of students in a classroom (e.g., 40 students).
o	Continuous Data: Measurable values that can take any number within a range, often including fractions or decimals. Example: Height of individuals (e.g., 5.8 feet).

6. Categorical Variables are used to represent data that can be divided into groups or categories. Variables holding qualitative data are known as factors. These variables do not have a numerical value in the usual sense, but rather label or describe an attribute or quality. For example, country, gender, etc. Levels of factors are most commonly without order, but factors can also be ordered.  

1. Ordered Data (Ordinal Data)
•	This type of data has a meaningful order or ranking, but the differences between the values are not necessarily uniform or measurable. There is a clear sequence or rank, but the exact difference between the levels may not be defined.
•	Examples:
o	Education Levels: High school < Bachelor's < Master's < Doctorate
o	Customer Satisfaction Ratings: Poor < Fair < Good < Excellent
 2. Unordered Data (Nominal Data)
•	This type of data consists of categories without any inherent order or ranking. : The categories are distinct, but there is no logical sequence or ranking among them.
•	Examples:
o	Types of Fruits: Apple, Banana, Orange, Mango
o	Countries: USA, Canada, Japan, Australia

Column	Quantitative/Qualitative	Numerical/Categorical	Continuous/Discrete	Ordered/Unordered
Month	  Qualitative	                Categorical	              N/A	            Ordered
Day	    Quantitative	              Numerical	              Discrete	        Ordered
Location Qualitative	              Categorical	              N/A	            Unordered
StationID Qualitative	              Categorical	              N/A	            Unordered
Temperature	Quantitative	          Numerical	              Continuous	      Ordered

When plotting data, axes that represent the same or comparable units and are intended for direct comparison should use the same units and grid size. This practice helps maintain consistency, avoids misleading interpretations, and allows for an accurate visual comparison. When both axes represent the same unit or measurement, such as length, weight, or time, they should have identical scales and grid sizes. Example: A scatter plot comparing height (in cm) vs. arm span (in cm). Both axes use the same unit (centimeters), so the scales should be equal to make the 45-degree line (where height equals arm span) accurate.

Transforming the axes of a plot can significantly improve data visualization, especially when dealing with data that has a wide range of values, non-linear relationships, or distributions. A common approach is applying transformations like logarithmic, square root, or standardization. Scenario: Visualizing Population Growth Over Time
Imagine you are plotting the population of a country over several decades. The data shows exponential growth:
Year	Population (in millions)
1900	10.1
1920	12.2
1940	11.	4
1960	12.	8
1980	13.	16
2000	14.	32
2020	15.	64
Problem with Raw Data Visualization:
Linear Scale: If you plot this data on a standard line chart with a linear scale for the Y-axis (population), you will see the following issues:
The growth looks extremely steep towards the end, making it hard to observe the trend in earlier years (where the population was smaller).
The rapid increase compresses the lower values into a small range, making it hard to analyze the growth pattern over time.
Solution: Logarithmic Transformation on the Y-axis:
By applying a logarithmic transformation to the Y-axis (population), we can better visualize the data:
Log Y-axis: Plotting the population in terms of log⁡(Population) scales down the exponential growth, turning the curve into a straight line.

All three coordinate systems—Cartesian, curvilinear, and polar—are valid for representing data. The choice of the system depends on the type of data and the most intuitive way to visualize or analyze it:
a.	Cartesian Coordinates (Rectangular grid, black):
o	Typically used for data with linear relationships or structured grids (e.g., height vs. weight). This is a valid coordinate system.
o	Example: Plotting points (x,y)(x, y)(x,y) in a 2D space.
b.	Curved Grid (blue):
o	Useful when the data or the domain naturally follows curves or warped geometries. No matter how you combine movements aling b1 and b2, you will always be stuck on the curves, you cannot reach every point on the grid. Therefore, this is not a valid coordinate system.
o	Example: Representing airflow over an airplane wing.
3.	Skewed Grid (red):
o	This one has slanted points but they can still reach every point in the grid. Therefore, this is a valid coordinate system.

1.Qualitative Color Scale :means to distinguish discrete items or groups that do not have an intrinsic order, such as different countries on a map. . 2.Represent data values (sequential): Gradual transitions between colors, often moving from light to dark or one hue to another. Best Usage: For ordered data with a natural progression, such as temperature, elevation, or time. 3.Represent data values (diverging): Two contrasting colors diverging from a neutral midpoint. Best Usage: For data with a meaningful midpoint, such as deviations from an average, zero, or target value 4.Highlight: Distinct, contrasting colors to represent discrete, unordered categories. Best Usage: For categorical or nominal data, such as different countries, brands, or species.

The issue with this visualization lies in the presence of the word "wrong" in the top-right corner. While the actual plot appears to be a density plot showing the distribution of "age (years)" along with its density values, labeling it as "wrong" without context is unhelpful.
1.	Possible Issues with the Data:
o	The density values may not sum to 1, which is a requirement for proper density plots.
2.	Visual Design Concerns:
- Lack of explanation for why the visualization is labeled as "wrong” and it can confuse readers. 
- A small change on a non-linear scale may appear much larger visually than a large change on a linear scale, potentially leading to incorrect conclusions. 
- The plot lacks sufficient labels or titles to explain its purpose. For example:
•	What is the dataset or population?
•	Is this showing a specific subset of data, like a demographic group?
Therefore, without this context, the plot cannot be interpreted properly.

The color palette transitioning from purple to green, passing through white is more effective for visualization than the red-to-green palette in many cases, particularly because it provides better contrast and is more inclusive for individuals with color vision deficiencies. The magenta-to-green palette is more distinguishable for individuals with red-green color blindness because magenta provides sufficient contrast compared to green. This palette works well for diverging data, where you need to show deviations from a neutral midpoint (represented by white in this case). For example: Showing changes above and below an average or baseline. Magenta and green are positioned on opposite sides of the color wheel, making them visually distinct and easy to differentiate even for humans.

This has been submitted (file uploaded).

The four major schools of thought in Probability Theory are:
1. Frequentist Inference: Uncertainty is inherent in the experiment. I cannot reduce uncertainty any further. Therefore, the uncertainty is aleatoric.
2. Bayesian Inference: The uncertainty is due to my lack of knowledge: 1. Wrong / inadequate model. 2. Lack of sufficiently detailed data which leads to inadequate models. I can reduce uncertainty with better data / model. Therefore, the uncertainty is epistemic.
3. Classical (Laplacean) Interpretation: Probability is defined as the ratio of favorable outcomes to all equally likely outcomes. This approach assumes a finite number of equally probable outcomes. Example: The probability of rolling a 6 on a fair die is 16\frac{1}{6}61, since all six outcomes are equally likely.
4. Axiomatic Interpretation: Probability is defined mathematically as a set function satisfying Kolmogorov's axioms (introduced by Andrey Kolmogorov in 1933). This approach is neutral regarding philosophical interpretation and focuses on building a consistent mathematical framework. Example: Rolling a Fair Six-Sided Dice.

Extra Credit 1: . Frog/Toad: The most immediate perception is of a frog or toad sitting by the water. But looking more closely, the body of the frog looks like a horse with a rider.  

Extra Credit 2: Move one matchstick from the 6 of 8 to the - (minus sign), turning it into a + (plus sign):
The new equation will be:
0 + 3 + 4 = 7
This holds true since 0 + 3 + 4 = 7.
