# Chart Capabilities and Construction Attributes in ArcGIS Online Dashboards and XlsxWriter

## ArcGIS Online Dashboards

ArcGIS Online Dashboards provide various chart types, each with specific capabilities and attributes. Here are the detailed possibilities and attributes for each type of chart and their subtypes.

### Basic Chart Types

#### 1. Line Chart
- **Purpose**: Display data trends over time or categories.
- **Attributes**:
  - `Title`: Chart title
  - `Data`: Time-series or categorical data
  - `Axes`: X-axis (time or category) and Y-axis (values)
  - `Series`: One or more data series
  - `Styling`: Line color, markers, and line style

##### Subtypes
- **Multiple Line Chart**: Display multiple lines to compare trends between different data series.
- **Stacked Line Chart**: Cumulative total of different data series over time.
- **Area Line Chart**: Similar to a line chart but with the area under the line filled to highlight volume.

#### 2. Bar Chart
- **Purpose**: Compare quantities across categories.
- **Attributes**:
  - `Title`: Chart title
  - `Data`: Categorical data
  - `Axes`: X-axis (categories) and Y-axis (values)
  - `Series`: One or more data series
  - `Styling`: Bar color and spacing

##### Subtypes
- **Stacked Bar Chart**: Displays segments of data in stacked bars to show the total of different sub-categories.
  - **Attributes**: Multiple data series, stack colors, and labels.
- **100% Stacked Bar Chart**: Shows the relative percentage of each sub-category, summing to 100% for each category.
  - **Attributes**: Multiple data series, normalized to 100%, stack colors, and labels.
- **Clustered Bar Chart**: Places bars for each sub-category side by side for easy comparison.
  - **Attributes**: Multiple data series, clustered bars, bar colors, and cluster spacing.
- **Horizontal Bar Chart**: A variation of the bar chart with horizontal bars for better readability of long category labels.
  - **Attributes**: Same as bar chart but with horizontal orientation.

#### 3. Pie Chart
- **Purpose**: Show proportions of a whole.
- **Attributes**:
  - `Title`: Chart title
  - `Data`: Categorical data
  - `Series`: One data series (values and categories)
  - `Styling`: Slice colors and labels

##### Subtypes
- **Doughnut Chart**: A variation of the pie chart with a hole in the center.
  - **Attributes**: Same as pie chart with additional styling for the doughnut hole.
- **Exploded Pie Chart**: One or more slices are offset from the center to highlight particular segments.
  - **Attributes**: Same as pie chart with the option to "explode" specific slices.

#### 4. Scatter Plot
- **Purpose**: Illustrate the relationship between two numerical variables.
- **Attributes**:
  - `Title`: Chart title
  - `Data`: Paired numerical data
  - `Axes`: X-axis and Y-axis (both numerical)
  - `Series`: One or more data series
  - `Styling`: Point color, shape, and size

##### Subtypes
- **Bubble Chart**: A variation of the scatter plot where the size of the points indicates a third variable.
  - **Attributes**: Similar to scatter plot with additional data series for bubble size.
- **Scatter Plot with Lines**: Connects data points with lines to show trends.
  - **Attributes**: Similar to scatter plot with line styling options.

### Customization Options
- **Data Filtering**: Apply filters to display specific subsets of data.
- **Interactive Elements**: Incorporate dynamic elements like selectors and pop-ups.
- **Thematic Mapping**: Integrate charts with maps for geographic data visualization.
- **Styling and Appearance**: Customize colors, labels, legends, and tooltips for clarity and aesthetics.

## XlsxWriter

XlsxWriter is a Python library used to create Excel files, including various types of charts. Here are the detailed capabilities and the essential attributes required to construct these charts.

### Basic Chart Types

#### 1. Line Chart
- **Purpose**: Display trends over time or categories.
- **Attributes**:
  - `Title`: Chart title
  - `Data`: Time-series or categorical data
  - `Axes`: X-axis (time or category) and Y-axis (values)
  - `Series`: One or more data series
  - `Styling`: Line color, markers, and line style

##### Subtypes
- **Multiple Line Chart**: Display multiple lines to compare trends between different data series.
  - **Attributes**: Multiple data series, line colors, and markers.
- **Stacked Line Chart**: Cumulative total of different data series over time.
  - **Attributes**: Multiple data series, stack colors, and cumulative values.
- **Area Line Chart**: Similar to a line chart but with the area under the line filled to highlight volume.
  - **Attributes**: Area fill colors and line styling.

#### 2. Bar Chart
- **Purpose**: Compare quantities across categories.
- **Attributes**:
  - `Title`: Chart title
  - `Data`: Categorical data
  - `Axes`: X-axis (categories) and Y-axis (values)
  - `Series`: One or more data series
  - `Styling`: Bar color and spacing

##### Subtypes
- **Stacked Bar Chart**: Displays segments of data in stacked bars to show the total of different sub-categories.
  - **Attributes**: Multiple data series, stack colors, and labels.
- **100% Stacked Bar Chart**: Shows the relative percentage of each sub-category, summing to 100% for each category.
  - **Attributes**: Multiple data series, normalized to 100%, stack colors, and labels.
- **Clustered Bar Chart**: Places bars for each sub-category side by side for easy comparison.
  - **Attributes**: Multiple data series, clustered bars, bar colors, and cluster spacing.
- **Horizontal Bar Chart**: A variation of the bar chart with horizontal bars for better readability of long category labels.
  - **Attributes**: Same as bar chart but with horizontal orientation.

#### 3. Column Chart
- **Purpose**: Similar to bar charts but vertical.
- **Attributes**:
  - `Title`: Chart title
  - `Data`: Categorical data
  - `Axes`: X-axis (categories) and Y-axis (values)
  - `Series`: One or more data series
  - `Styling`: Column color and spacing

##### Subtypes
- **Stacked Column Chart**: Vertical bars stacked to show parts of a whole.
  - **Attributes**: Multiple data series, stack colors, and labels.
- **100% Stacked Column Chart**: Stacked vertical bars, normalized to 100%.
  - **Attributes**: Multiple data series, normalized to 100%, stack colors, and labels.
- **Clustered Column Chart**: Places columns for each sub-category side by side for easy comparison.
  - **Attributes**: Multiple data series, clustered columns, column colors, and cluster spacing.

#### 4. Pie Chart
- **Purpose**: Represents data as parts of a whole.
- **Attributes**:
  - `Title`: Chart title
  - `Data`: Categorical data
  - `Series`: One data series (values and categories)
  - `Styling`: Slice colors and labels

##### Subtypes
- **Doughnut Chart**: A variation of the pie chart with a hole in the center.
  - **Attributes**: Same as pie chart with additional styling for the doughnut hole.
- **Exploded Pie Chart**: One or more slices are offset from the center to highlight particular segments.
  - **Attributes**: Same as pie chart with the option to "explode" specific slices.

#### 5. Scatter Plot
- **Purpose**: Shows relationships between two variables.
- **Attributes**:
  - `Title`: Chart title
  - `Data`: Paired numerical data
  - `Axes`: X-axis and Y-axis (both numerical)
  - `Series`: One or more data series
  - `Styling`: Point color, shape, and size

##### Subtypes
- **Bubble Chart**: A variation of the scatter plot where the size of the points indicates a third variable.
  - **Attributes**: Similar to scatter plot with additional data series for bubble size.
- **Scatter Plot with Lines**: Connects data points with lines to show trends.
  - **Attributes**: Similar to scatter plot with line styling options.

### Customization Options
- **Chart Titles and Labels**: Add and customize titles, axis labels, and data labels.
- **Legend Positioning**: Place legends in different positions around the chart.
- **Data Series Formatting**: Customize the appearance of data series with colors, patterns, and markers.
- **Axis Scaling and Formatting**: Adjust axis scales, gridlines, and formats (e.g., currency, percentage).
- **Adding Trendlines**: Insert trendlines to highlight data trends.

This README provides an overview of the chart possibilities in ArcGIS Online Dashboards and XlsxWriter, detailing basic types, subtypes, and customization options for effective data visualization.
