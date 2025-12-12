---
title: "My Project"
format: html
editor: visual
author: "Emmanuel Mhango"
bibliography: bibliography.bib
execute:
  keep-md: true
---

## Uganda Waterpoints

This dataset provides comprehensive information on water points across Uganda. This dataset is a free dataset shared through [The Humanitatian Data Exchange](https://data.humdata.org/dataset/wpdx_uga "Uganda Water points Data"). Each entry represents an individual water source, such as a well or a rainwater harvesting system, with associated details covering location, type, functionality, management, and usage.

Key attributes include:

-   **Geographical information:** Latitude, longitude, and administrative divisions (region, district, sub-county).

-   **Water source and technology:** The type of water source (e.g., protected well, rainwater harvesting) and the technology used.

-   **Operational status:** Whether the water point is functional or non-functional.

-   **Management and governance:** How the water point is managed (community-managed, fee-based, etc.) and the organization responsible.

-   **Installation and maintenance history:** Year of installation, rehabilitation records, and organizations involved.

-   **Population served:** The number of people served within the vicinity of the water point.

-   **Water quality indicators:** Includes parameters such as fecal contamination presence and subjective quality assessments.

-   **Proximity metrics:** Distances to urban centers, primary, secondary, and tertiary water sources.

**Analysis Goals:**\
The primary goals of analyzing this dataset are:

1.  **Monitoring and Evaluation (M&E):** Assess the operational status and functionality of water points across different regions to track performance, identify trends, and support evidence-based decision-making.

2.  **Risk Assessment:** Identify areas at higher risk of water point failure, contamination, or insufficient coverage to prioritize interventions, rehabilitation, and resource allocation.

This dataset serves as a detailed resource for monitoring water access and quality in Uganda, supporting strategic planning, management effectiveness assessment, and risk-informed decision-making for water infrastructure.

## Import

To load the data, you should first load the required libraries to use:


::: {.cell}

:::


Now, load your dataset like this


::: {.cell}

:::


Now, we will write code to bring your data into a state where it’s ready for analysis.

-   Rename columns with `rename()`

-   Select columns that are relevant with `select()`

-   Remove missing values with `filter()` or `drop_na()`

-   Join several dataframes with `left_join()`, `right_join()`, etc.

-   Create new variables with `mutate()`


::: {.cell}

:::


Save the processed data into a CSV file


::: {.cell}

:::


## Visualization

Visualization is important because it helps to visually represents the data. We will visualize 2 graphs for the dataset:

### 1. Bar graph of impacted people by the resource type

This visualization shows the total population impacted by the functional status of the waterpoint.


::: {.cell}
::: {.cell-output-display}
![](index_files/figure-html/unnamed-chunk-5-1.png){width=672}
:::
:::


### 2. Scatter Plot (Criticality vs Pressure)

This scatter plot shows the relationship between pressure (how heavily a water point is used) and criticality (how essential or high-risk the water point is).


::: {.cell}
::: {.cell-output-display}
![](index_files/figure-html/unnamed-chunk-6-1.png){width=672}
:::
:::


## Summary of the 5 selected data variables


::: {#tbl-statistics .cell tbl-cap='Summary of Key Variables'}
::: {.cell-output-display}

```{=html}
<div id="snlobaagqv" style="padding-left:0px;padding-right:0px;padding-top:10px;padding-bottom:10px;overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>#snlobaagqv table {
  font-family: system-ui, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#snlobaagqv thead, #snlobaagqv tbody, #snlobaagqv tfoot, #snlobaagqv tr, #snlobaagqv td, #snlobaagqv th {
  border-style: none;
}

#snlobaagqv p {
  margin: 0;
  padding: 0;
}

#snlobaagqv .gt_table {
  display: table;
  border-collapse: collapse;
  line-height: normal;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#snlobaagqv .gt_caption {
  padding-top: 4px;
  padding-bottom: 4px;
}

#snlobaagqv .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#snlobaagqv .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 3px;
  padding-bottom: 5px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#snlobaagqv .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#snlobaagqv .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#snlobaagqv .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#snlobaagqv .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#snlobaagqv .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#snlobaagqv .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#snlobaagqv .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#snlobaagqv .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#snlobaagqv .gt_spanner_row {
  border-bottom-style: hidden;
}

#snlobaagqv .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  text-align: left;
}

#snlobaagqv .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#snlobaagqv .gt_from_md > :first-child {
  margin-top: 0;
}

#snlobaagqv .gt_from_md > :last-child {
  margin-bottom: 0;
}

#snlobaagqv .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#snlobaagqv .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#snlobaagqv .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#snlobaagqv .gt_row_group_first td {
  border-top-width: 2px;
}

#snlobaagqv .gt_row_group_first th {
  border-top-width: 2px;
}

#snlobaagqv .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#snlobaagqv .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#snlobaagqv .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#snlobaagqv .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#snlobaagqv .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#snlobaagqv .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#snlobaagqv .gt_last_grand_summary_row_top {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: double;
  border-bottom-width: 6px;
  border-bottom-color: #D3D3D3;
}

#snlobaagqv .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#snlobaagqv .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#snlobaagqv .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#snlobaagqv .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#snlobaagqv .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#snlobaagqv .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#snlobaagqv .gt_left {
  text-align: left;
}

#snlobaagqv .gt_center {
  text-align: center;
}

#snlobaagqv .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#snlobaagqv .gt_font_normal {
  font-weight: normal;
}

#snlobaagqv .gt_font_bold {
  font-weight: bold;
}

#snlobaagqv .gt_font_italic {
  font-style: italic;
}

#snlobaagqv .gt_super {
  font-size: 65%;
}

#snlobaagqv .gt_footnote_marks {
  font-size: 75%;
  vertical-align: 0.4em;
  position: initial;
}

#snlobaagqv .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#snlobaagqv .gt_indent_1 {
  text-indent: 5px;
}

#snlobaagqv .gt_indent_2 {
  text-indent: 10px;
}

#snlobaagqv .gt_indent_3 {
  text-indent: 15px;
}

#snlobaagqv .gt_indent_4 {
  text-indent: 20px;
}

#snlobaagqv .gt_indent_5 {
  text-indent: 25px;
}

#snlobaagqv .katex-display {
  display: inline-flex !important;
  margin-bottom: 0.75em !important;
}

#snlobaagqv div.Reactable > div.rt-table > div.rt-thead > div.rt-tr.rt-tr-group-header > div.rt-th-group:after {
  height: 0px !important;
}
</style>
<table class="gt_table" data-quarto-disable-processing="false" data-quarto-bootstrap="false">
  <thead>
    <tr class="gt_heading">
      <td colspan="4" class="gt_heading gt_title gt_font_normal" style>Summary of Key Variables</td>
    </tr>
    <tr class="gt_heading">
      <td colspan="4" class="gt_heading gt_subtitle gt_font_normal gt_bottom_border" style>Summary per waterpoint</td>
    </tr>
    <tr class="gt_col_headings">
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col" id="Variable">Variable</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Mean">Mean</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Median">Median</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col" id="Std.-Dev">Std. Dev</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td headers="Variable" class="gt_row gt_left">assigned_population</td>
<td headers="Mean" class="gt_row gt_right">763</td>
<td headers="Median" class="gt_row gt_right">449</td>
<td headers="Std. Dev" class="gt_row gt_right">1,107</td></tr>
    <tr><td headers="Variable" class="gt_row gt_left">distance_to_city</td>
<td headers="Mean" class="gt_row gt_right">83,929</td>
<td headers="Median" class="gt_row gt_right">74,413</td>
<td headers="Std. Dev" class="gt_row gt_right">47,342</td></tr>
    <tr><td headers="Variable" class="gt_row gt_left">local_population</td>
<td headers="Mean" class="gt_row gt_right">1,644</td>
<td headers="Median" class="gt_row gt_right">1,028</td>
<td headers="Std. Dev" class="gt_row gt_right">1,994</td></tr>
    <tr><td headers="Variable" class="gt_row gt_left">pressure</td>
<td headers="Mean" class="gt_row gt_right">3</td>
<td headers="Median" class="gt_row gt_right">2</td>
<td headers="Std. Dev" class="gt_row gt_right">5</td></tr>
    <tr><td headers="Variable" class="gt_row gt_left">usage_cap</td>
<td headers="Mean" class="gt_row gt_right">282</td>
<td headers="Median" class="gt_row gt_right">300</td>
<td headers="Std. Dev" class="gt_row gt_right">39</td></tr>
  </tbody>
  
  
</table>
</div>
```

:::
:::


In @tbl-statistics, you can see that standard deviation is generally big. The High SD means that the population assigned to water points varies hugely. Some water points serve very few people, others serve more.

Furthermore,in the same @tbl-statistics, the small mean and median but larger SD for pressure suggests that pressure values are skewed. some points have extreme under usage unlike others.

## Conclusion

The analysis demonstrates substantial variability in water point usage, population served, and proximity characteristics, highlighting uneven service distribution and emphasizing the need for targeted interventions to improve equitable access and system reliability across Uganda.

This dataset is sourced from WPdx [@wpdxuga] and supported by earlier studies such as @nsubuga2014water. The analysis approach draws on principles from the Tidyverse ecosystem [@wickham2019].
