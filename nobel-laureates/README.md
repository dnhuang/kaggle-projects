# nobel-laureates

Project started on 6/17/2023.

Got this idea from a post on r/kpop where a reddit user created a heatmap of birthdays for kpop idols. As a consumer of the medium, I also wanted to do the same thing, but since it was already done, I felt it would've been better to create a visualization based on a different dataset.

Was surfing randomly around Kaggle one day and saw this dataset; thought it could work. Had to do some preprocessing and ran into some annoying outlier and null values, but I took care of them with imputation and simple removal.

Created some simple visualizations in `eda_and_preprocessing.ipynb` with `seaborn` and `matplotlib`; noticed some interesting trends particularly with regards to gender.

The heatmaps (motivation of the project) were created using Tableau.

Dashboard created using the data (click on image to interact with the dashboard in Tableau Public):

<div class='tableauPlaceholder' id='viz1687062804370' style='position: relative'><noscript><a href='https://public.tableau.com/app/profile/daniel.huang3227/viz/nobel_laureates/NobelLaureateHeatmapDashboard'><img alt='Nobel Laureate Heatmap Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;no&#47;nobel_laureates&#47;NobelLaureateHeatmapDashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='nobel_laureates&#47;NobelLaureateHeatmapDashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;no&#47;nobel_laureates&#47;NobelLaureateHeatmapDashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>
