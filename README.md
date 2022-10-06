# maps-valeriechavez
maps-valeriechavez created by GitHub Classroom


I have created a map of High School Student's self-reported peer-belonging by state. For each school that surveyed student's responses were compiled into a key factor rating. These key factors were then aggregated at the state level. 

Note that not all 48 states in the continental US surveyed, those who do not have any data are shown in gray. Also note that sample sizes vary by state, though this is not reflected on the map. 

Below are descriptions of the data:
data source: 
The source is YouthTruth Student Survey, a national nonprofit that works with schools and districts across the country. For the confidentiallity of student's and clients, raw data cannot be shared.

spatial units being displayed:
Data are displayed at the state level, each state shows the average peer-belonging rating for YouthTruth students, which are the average of a 1-5 likert scale (with 5 being the most positive, 1 being the most negative), state means ranged from 2.909091 to 3.757303

what you are trying to communicate:
I wish to show the variety in student's self-described peer-belonging by geography. Note that while likert averages tend toward 3 (on a 5 point scale) as the data are aggregate with a large sampe, any deviations might be noteworthy.

what decisions you made and why you made those to best communicate the data.
I chose to use the key factor rating as these are the composite scales for each survey intrument. I also choose to look at mean (as opposed to over all distrubtion, percent positive or any other possible attribute) as I thought it would be the clearest to interpret and the most concise to convey. (If I had more time I would have liked to look at the percent of students that rated 4 and 5 for each state as this might be more informative, however for the sake of time, I went with mean). I concsidered making the graph interactive. I chose to use the theme tufte as it nicely formatted the text, and the plasma color theme as it nicely constracted colors. I chose not to include any accompanying charts or graphs as the distributions looked similar by state and preferred to keep the graph concise. I included a plotly option as well as the static graph as the tooltip is useful for seeing the value at each state. 
