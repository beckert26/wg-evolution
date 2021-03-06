# Stars

Question: How many times was a project starred over time.

## Description
Projects on github can be starred by users who want to follow certain projects. This metric will describe the amount of time a project was starred over the course of time.

## Objectives
<ul>
<li>This metric can be valuable for many reasons. The first being learning whether your open source project getting starred matters. This metric will test whether there is correlation between the amount of times  project being starred leading to a healthier project. It will also test whether during a certain period of time if an increase in stars lead to an increase in work on a project. This metric can be a good test to whether your project is losing or gaining engagement and interest over time.</li>
</ul>

## Implementation
**Aggregators**
<ul>
<li>Count. Total number of stars during a period.</li>
</ul>

**Parameters**
<ul>
<li>Period of time: Start and finish date of the period. Default: forever. Period during which changes are considered.</li>
<li>Star: Project being starred on github.</li>
</ul>

### Filters
<ul>
<li>By each unique repository. </li>
    <li>User needs to have a github account for more than a week </li>
</ul>

### Visualizations
<ul>
<li>Count per month over time</li>
</ul>
This should be repsented with a line graph. With the x-axis being time and the Y-axis being the amount of star during a certain period.

**Example Graph:**<br>
    ![alt text](https://github.com/beckert26/wg-evolution/blob/master/metrics/images/graph.png)

### Data Collection Strategies
**Specific description: Github**

Data should be collected from github. A star is defined by a user hitting the star button on a github repository.

**Mandatory parameter:**
<ul>
  <li>Date of when a user starred a repository. </li>
</ul>

