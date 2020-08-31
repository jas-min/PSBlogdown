---
# An instance of the About widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: About

# Choose the user profile to display
# This should be the username (folder name) of a profile in your `content/authors/` folder.
# See https://sourcethemes.com/academic/docs/get-started/#introduce-yourself
author: admin
---
Washington Post and database developer, John Muyskens has kept an up-to-date [dataset](https://github.com/washingtonpost/data-police-shootings) of all fatal police shootings in the US. The dataset is descriptive of the circumstances of that of a police officer whom shot and killed a civilian. We can think about Philando Castile, Breonna Taylor, Tamir Rice, or Michael Brown that closely parallel these circumstances. In result of these killings, movements like Black Lives Matter, and calls for increasing accountability and change rose around the world. 

I would like to point out a few things that need to be in mind when looking at these analyses. Although it will be pointed out in the respective topic each analysis is within, these variables need to be discussed:
  
+ `manner_of_death` only has two categories, "shot" and "shot and Tasered". This is meant to indicate that if another method was used beside a gun to subdue the victim of a fatal police shooting. There isn't any other indication if other methods were reported to subdue a victim. This may be a lacking variable, but this dataset is on what is reported through local news, law enforcement websites, other databases, social media, and then vetted, so only having two categories is justified.

+ `race` has a category "unknown", which I updated in all analyses as "Not Recorded". The reasoning behind it, is because there is an "other" category, so the race was not recorded through the means described in manner of death.

+ `threat_level` has the reported immediate threat of an officer's life as "attack". This can be reported through the perception of the police report or other through the other means of updating the dataset. So keep in mind the possibility of a variation of the truth because this variable is based on perception.

+ `flee` and the `threat_level` are not necessarily related. An individual could pose an immediate threat to an officer's life while trying to escape on a bike. Just as an individual who doesn't any threat could not be trying to escape.

### Details
This is a project by Jasmin Cabarios and in collaboration with Alexander Goldstein for STAT 331 at California Polytechnic University, San Luis Obispo. 

All source code is available [here](https://github.com/jas-min/PSBlogdown) and at the bottom of every analysis via github icon.
  