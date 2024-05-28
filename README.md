# Chart Capabilities and Construction Attributes in ArcGIS Online Dashboards and XlsxWriter

## ArcGIS Online Dashboards

ArcGIS Online Dashboards provide various chart types, each with specific capabilities and attributes. Here are the detailed possibilities and attributes for each type of chart and their subtypes.

### Basic Serial Chart Types

#### 1. Line Chart
- **Purpose**: Display data trends over time or categories.
- **Primary Attributes**:
  - `Category field`: Selects Y-axis data (time or category)
  - `Split by field`: Selects categorical data to be split 
  - `Statistic`: Selects statistic for vizualization: count, average, minimun, maximum, sum, standarde deviation, percentile discrete, and percentile continuous
  - `Field`: Selects the values for vizualization
- **Presentation Attributes**:
  - `Text color`: Selects text color
  - `Font size (px)`: Selects font size
  - `Orientation`: Selects horizontal or veritcal orientation
  - `Legend placement`: Side, bottom, or hidden
  - **Category Axis Attributes**:
    - `Title`: Name of X-axis
    - `Title size (px)`: Selects title font size
    - `Scrollbar`: Adds scrollbar for user to move along X-axis (on/off)
    - **Label Attributes**:
      - `Visibility`: Display or hide labels (on/off)
      - `Size (px)`: Sets font size for labels
      - `Placement`: Selects label placement relavtive to the X-axis: default, staggered, rotated, wrapped
    - **Axis Attributes**:
      - `Color`: Selects color of axis
      - `Opacity`: Selects opacity of axis (0.0-1.0)
      - `Thickness`: Selects thickness of axis (0-10)
    - **Grid Attributes**:
      - `Color`: Selects color of grid
      - `Opacity`: Selects opacity of grid (0.0-1.0)
      - `Thickness`: Selects thickness of grid (0-10)
  - **Value Axis Attributes**:
    - `Title`: Name of Y-axis
    - `Title orientation`: Up or down
    - `Title size (px)`: Selects title font size
    - `Minimum value`: Selects minimum value on Y-axis
    - `Maximum value`: Selects maximum value on Y-axis
    - `Integers only`: Rounds Y-axis to whole numbers (on/off)
    - `Logarithmic`: Puts Y-axis in logarithmic scale (on/off)
    - **Label Attributes**:
      - `Visibility`: Display or hide labels (on/off)
      - `Size (px)`: Sets font size for labels
      - **Value formatting**:
        - `Style`: Decimal or Percent
        - `Digit grouping`: Adds commas to grouped digits (on/off)
        - `Minimum decimal places`: Minimum decimal places in Y-axis labels
        - `Maximum decimal places`: Maximum decimal places in Y-axis labels
        - `Value prefix/suffix`: Manually add prefix/suffix to Y-axis labels
    - **Axis Attributes**:
      - `Color`: Selects color of axis
      - `Opacity`: Selects opacity of axis (0.0-1.0)
      - `Thickness`: Selects thickness of axis (0-10)
    - **Grid Attributes**:
      - `Color`: Selects color of grid
      - `Opacity`: Selects opacity of grid (0.0-1.0)
      - `Thickness`: Selects thickness of grid (0-10)
    - `Guides`: Provide context to the data being displayed on a chart by representing goals or thresholds. Guides can be lines that represent a single value or a shaded area that represents a range of values. In addition, serial charts can have multiple guides. 


##### Subtypes
- **Smoothed Line Chart**: Lines between points are smoothed to makes trends potentially more vizually appealing

#### 2. Bar Chart
- **Purpose**: Compare quantities across categories.
- **Primary Attributes**:
  - `Category field`: Selects Y-axis data (time or category)
  - `Split by field`: Selects categorical data to be split 
  - `Statistic`: Selects statistic for vizualization: count, average, minimun, maximum, sum, standarde deviation, percentile discrete, and percentile continuous
  - `Field`: Selects the values for vizualization
- **Presentation Attributes**:
  - `Text color`: Selects text color
  - `Font size (px)`: Selects font size
  - `Orientation`: Selects horizontal or veritcal orientation
  - `Legend placement`: Side, bottom, or hidden
  - **Category Axis Attributes**:
    - `Title`: Name of X-axis
    - `Title size (px)`: Selects title font size
    - `Scrollbar`: Adds scrollbar for user to move along X-axis (on/off)
    - **Label Attributes**:
      - `Visibility`: Display or hide labels (on/off)
      - `Size (px)`: Sets font size for labels
      - `Placement`: Selects label placement relavtive to the X-axis: default, staggered, rotated, wrapped
    - **Axis Attributes**:
      - `Color`: Selects color of axis
      - `Opacity`: Selects opacity of axis (0.0-1.0)
      - `Thickness`: Selects thickness of axis (0-10)
    - **Grid Attributes**:
      - `Color`: Selects color of grid
      - `Opacity`: Selects opacity of grid (0.0-1.0)
      - `Thickness`: Selects thickness of grid (0-10)
  - **Value Axis Attributes**:
    - `Title`: Name of Y-axis
    - `Title orientation`: Up or down
    - `Title size (px)`: Selects title font size
    - `Minimum value`: Selects minimum value on Y-axis
    - `Maximum value`: Selects maximum value on Y-axis
    - `Integers only`: Rounds Y-axis to whole numbers (on/off)
    - `Logarithmic`: Puts Y-axis in logarithmic scale (on/off)
    - **Label Attributes**:
      - `Visibility`: Display or hide labels (on/off)
      - `Size (px)`: Sets font size for labels
      - **Value formatting**:
        - `Style`: Decimal or Percent
        - `Digit grouping`: Adds commas to grouped digits (on/off)
        - `Minimum decimal places`: Minimum decimal places in Y-axis labels
        - `Maximum decimal places`: Maximum decimal places in Y-axis labels
        - `Value prefix/suffix`: Manually add prefix/suffix to Y-axis labels
    - **Axis Attributes**:
      - `Color`: Selects color of axis
      - `Opacity`: Selects opacity of axis (0.0-1.0)
      - `Thickness`: Selects thickness of axis (0-10)
    - **Grid Attributes**:
      - `Color`: Selects color of grid
      - `Opacity`: Selects opacity of grid (0.0-1.0)
      - `Thickness`: Selects thickness of grid (0-10)
    - `Guides`: Provide context to the data being displayed on a chart by representing goals or thresholds. Guides can be lines that represent a single value or a shaded area that represents a range of values. In addition, serial charts can have multiple guides. 
##### Subtypes
- **Stacked Bar Chart**: Displays segments of data in stacked bars to show the total of different sub-categories.
- **100% Stacked Bar Chart**: Shows the relative percentage of each sub-category, summing to 100% for each category.

#### 3. Pie Chart
- **Purpose**: Show proportions of a whole.
- **Primary Attributes**:
  - `Category field`: Selects Y-axis data (time or category)
  - `Statistic`: Selects statistic for vizualization: count, average, minimun, maximum, sum, standarde deviation, percentile discrete, and percentile continuous
  - `Field`: Selects the values for vizualization
- **Presentation Attributes**:
  - `Text color`: Selects text color
  - `Font size (px)`: Selects font size
  - `Start angle`: Selects the first orientation
  - `Inner radius`: Selects size of empty space in middle 
  - **Label Attributes**:
    - `Visibility`: Display or hide labels (Hide/Value/Percentage)
    - `Labels offset (px)`: Sets lebel distance from chart
    - `Label line opacity`: Selects opacity of label lines (0.0-1.0)
  - `Legend`: Hide, Value, or Percentage
  - **Value formatting**:
  - `Style`: Decimal or Percent
  - `Digit grouping`: Adds commas to grouped digits (on/off)
  - `Minimum decimal places`: Minimum decimal places in Y-axis labels
  - `Maximum decimal places`: Maximum decimal places in Y-axis labels
  - `Value prefix/suffix`: Manually add prefix/suffix to Y-axis labels
  - `Unit prefix`: Toggle unit prefix (on/off)
  - **Percentage formatting**:
  - `Digit grouping`: Adds commas to grouped digits (on/off)
  - `Minimum decimal places`: Minimum decimal places in Y-axis labels
  - `Maximum decimal places`: Maximum decimal places in Y-axis labels
  -  `Value prefix/suffix`: Manually add prefix/suffix to Y-axis labels

##### Subtypes
- **Doughnut Chart**: A variation of the pie chart with a hole in the center.
  - **Attributes**: Same as pie chart with additional styling for the doughnut hole.

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
