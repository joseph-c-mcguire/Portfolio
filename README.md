# Portfolio
A portfolio of my work

## Mathematical Competition in Modeling (MCM) - Opiod Epidemic
This was the first data analysis project I worked, as part of the MCM 2019.
After a regression analysis of the data, our team concluded with a number of possibilites of what was correlated to significant increases in opioid-related arrests.
We concluded that one possibility was an increase in interactions with the healthcare system (nurses, doctors, clinics, etc.) was correlated with an increase in opioid arrests by county.
Our reasoning for this was these interactions increase your chance of being prescribed a opioid, and hence acted as points of introduction for the addiction.

Another trend we saw in the data was counties high in indicators of socio-economic resources often saw an increase in opioid arrests, indicating that while better investment in these counties by state and federal governments likely would help, opioid trends did follow closely to these factors.
Counter-intuitive to what was assumed by our team.

## REU in Computational and Applied Math (UCLA 2019) - Deforestation
As part of this project, my research team for that summer was tasked with modeling deforestation in the Amazon rainforest of Brazil.
After close analysis of geo-spatial data, cleaning of data sets provided, and literature review we concluded that a large proportion of the deforestation events were occuring because of land clearance rather than intentional 'poaching' of trees for sell.
The latter category did account for a small percentage of the data, and were often in remote areas.
So our team split to work on these two modes of deforestation.

I worked with the team that primarily focused on the land clerance model of deforestation.
From first principles, we developed a data-driven model that based on previous year's data would fit a probability distribution over the area being considered.
From this distribution, we would then simulate a year of deforestation events by sampling from this distribution.
Once an event occured, the forest around the event would continue be deforested year-after-year, simulating persistent land clerance.
From taking the first two thirds of years present in our data, within a error-tolerance, we were able to accurately predict +80% of the deforestation data in the remaining one third test set.

These results were then collected in the report in the file above and presented to the program at the end of the summer.
My team and I then produced 2 posters to present our findinigs at the Intelligence Communities Academic Research Symposium in Washington D.C.
