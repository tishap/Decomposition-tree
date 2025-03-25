
# Olympic Events Decomposition Tree Visualization

## Project Overview

This project showcases a **Decomposition Tree** visualization of Olympic events data, providing a hierarchical breakdown of metrics such as medal types, teams, sports, age groups, and athlete heights. The decomposition tree enables users to explore data dynamically across multiple dimensions, uncovering insights through drill-downs and aggregations.

## What is a Decomposition Tree?

The **Decomposition Tree** is a powerful visual analysis tool used to hierarchically explore data across multiple dimensions. It starts with a high-level overview and allows users to drill down into specific branches to analyze contributing factors or patterns. This visualization is particularly effective for root cause analysis, dynamic exploration, and understanding hierarchical relationships within data.

### Key Features:
- **Hierarchical Visualization:** Displays data in a tree structure with nodes representing metrics or categories.
- **Dynamic Drill-Down:** Users can expand nodes to explore deeper levels of data.
- **AI Integration (Optional):** Suggests the next dimension for exploration based on predefined criteria.
- **Cross-Filtering:** Interacts with other visuals in the report to refine analysis.

## Mechanism of the Decomposition Tree

### How It Works:
1. **Data Input:**
   - The visualization requires two types of fields:
     - **Analyze Field:** A measure or aggregate (e.g., number of events).
     - **Explain By Fields:** Dimensions that break down the measure (e.g., medal type, team, sport).

2. **Node Creation:**
   - The root node represents the total value of the analyzed metric (e.g., total Olympic events: 232,344).
   - Each branch splits into subcategories based on dimensions like medal type (Gold, Silver, Bronze), teams, sports, etc.

3. **Drill-Down Functionality:**
   - Clicking the "+" icon next to a node expands it into its subcategories.
   - Users can drill down in any order to explore specific paths of interest.

4. **Data Aggregation:**
   - The tree automatically aggregates data at each level. For example:
     - Total events are broken down by medal type.
     - Medal types are further divided by teams (e.g., United States, Germany).
     - Teams are segmented by sports, age groups, and height categories.

5. **Interactive Filtering:**
   - Selecting nodes filters related visuals in the report.
   - Cross-filtering updates paths dynamically based on selected criteria.

### Visual Representation:
- **Root Node:** Represents the total metric being analyzed.
- **Branches:** Break down the metric into dimensions (e.g., medal type → team → sport → age → height).
- **Bars:** Display aggregated values for each category.
- **Plus Signs (+):** Indicate expandable nodes for further drill-down.

## Example Breakdown:
1. Start with the total number of Olympic events: 232,344.
2. Drill down into medal types:
   - Did Not Medal: 200,881 events
   - Bronze: 10,710 events
   - Gold: 10,450 events
   - Silver: 10,303 events
3. Explore teams under each medal category (e.g., United States → Athletics → Age → Height).
4. Analyze further dimensions like sports and athlete demographics.

## Technologies Used:
- **Visualization Tool:** Power BI Decomposition Tree Visual
- **Data Source:** Olympic Events Dataset
- **Features Utilized:** Analyze Field and Explain By Dimensions

