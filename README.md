# como_dispatch
Basic analysis of one year of police calls and dispatch activities, in Columbia, Mo.

A year's worth of data was downloaded from https://www.como.gov/CMS/911dispatch/police.php in September 2022. 

For this project, I cleaned dispatch data from the Columbia Police Department and geocoded addresses into longitude/latitude coordinates. I then completed a spatial join with data imported using tidycensus, to look for any correlations between median income of a Census block group and calls, patrols and police reports filed.
