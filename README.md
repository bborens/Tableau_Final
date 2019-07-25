# Tableau Data Visualization 
## Udacity
### Examining Professional Baseball Players

#### Dataset

[Link to Dataset](https://s3.amazonaws.com/udacity-hosted-downloads/ud507/baseball_data.csv)




#### Summary

This dataset contains the statistics of 1,157 unique professional baseball players, including attributes which contain their handedness, height in inches, weight, batting average, and home runs. The visualizations included in the Tableau published story examine the performance values among players. 

#### Links to Tableau Story

[Initial_Story](https://public.tableau.com/views/InitialStory_15596803547140/BaseballInitialStory?:embed=y&:display_count=yes&publish=yes&:origin=viz_share_link)

[Final_Story](https://public.tableau.com/views/FinalStory_15596803945390/BaseballInitialStory?:embed=y&:display_count=yes&publish=yes&:origin=viz_share_link)


#### Design 

> I chose to create a scatterplot which includes all players included in the dataset, which examines the correlation between batting average (x-axis), and homerun totals (y-axis).

> The second visualization examines the above scatteplot, subgrouped into three smaller plots which are defined by the player's associated 'Handedness' value; whether they are L (left-handed), R (right-handed), or B (Both/Switch Hitters).

> My third visualization examines whether or not there is a positive linear relationship between players' heights and weights via a scatterplot. I suspected there would be a positive relationship since there was one when I initially examined a dataset of professional soccer players for a prior project. 

> The fourth visualization is a bar graph which examines players by their (binned) weight category (x-axis), with their total homeruns (y-axis) being the value. 

> The last visualization created is similar to the above graph, except rather than the sum (total) of the homeruns, the value (y-axis) is defined by its average homerun value for the associated weight class (bin). This was done due to the majority of players fitting into an average bin and the sum obscuring performance values when examining binned weights against each other. 

#### Feedback

1) The visuals should include some sort of annotation to describe what you're looking at. 

*Solution*: Added text to annotate each graph. 

2) It would be helpful to add analytics. For example trend lines or median/average values to see how each bin or individual player ranks.

*Solution*: Addded analytics layers to each graph, such as Median, Average, and Quartile Lines to respective graphs.

3) Maybe change the colors from green to something else since green is a hard color for some with color deficiency to differentiate values.

*Solution*: Changed colors to a different color for accessibility reasons listed above. Fixed Zoom on Weight/Height plot.

#### Sources

1) [Tableau_Crash_Course](https://hooktube.com/watch?v=TPMlZxRRaBQ)

2) [A_Game_Of_Decisions_With_Andy_Kirk](https://hooktube.com/watch?v=GVkXbQOzKNs)