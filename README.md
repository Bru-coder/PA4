# Data Analysis and Visualization Project

## Overview
This project leverages data wrangling and visualization techniques to explore how different demographic and academic variables influence academic performance. Through careful analysis and visual storytelling, we extract meaningful insights from educational data, focusing on the impacts of academic tracks, gender, and regional background on student math scores.

## Objectives
1. **Data Wrangling**: Manipulate and prepare data to create specific subsets for detailed analysis.
2. **Visualization**: Develop visual representations to illustrate how different factors contribute to academic outcomes.

## Data Frames Creation
The project involves creating specific data frames based on predefined criteria to analyze various facets of the data:

### Vis Data Frame
- **Criteria**: Students with math scores below 70.
- **Fields**: Name, Gender, Track, Math Score.
- **Hometown**: Constantly set to 'Visayas'.
- **Output Example**:
| Name | Gender | Track           | Math |
|------|--------|-----------------|------|
| S4   | Male   | Instrumentation | 65   |
| S11  | Female | Communication   | 48   |
| S22  | Female | Communication   | 64   |

### Instru Data Frame
- **Criteria**: Entries with 'GEAS' gender, in 'Electronics' track with math scores over 70.
- **Fields**: Name.
- **Track and Hometown**: Constantly set to 'Instrumentation' and 'Luzon', respectively.

### Mindy Data Frame
- **Criteria**: Female students from 'Mindanao' in 'Electronics' track with an average score of 55 or higher.
- **Fields**: Name, Track, Electronics Score, Average Score.

## Visualization
The project features a comprehensive visualization that examines the correlation between the selected academic and demographic factors and average math grades. This visualization helps to determine if the track chosen in college, gender, or hometown significantly impacts students' average scores.

## Insights Expected
By analyzing these facets, the project aims to identify potential patterns and trends that can inform educational strategies and interventions, highlighting areas where students may need more support or resources based on their backgrounds and chosen academic paths.
