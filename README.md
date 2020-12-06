# UFOs

## Overview

This website began as a table with with the ability to filter UFO sightings by date. In this challenge, we added filters for city, state, country, and the shape of the object seen and published the site to Github pages to share.

## Results

The site opens with the full table of all UFO sightings from the data we have. From here we can easily filter this table according to the five criteria listed above. Take note of the format given in the preview for each filter field.

![home](images/UFO_home.png)

Enter the value you want to filter according to the format and push enter on your keyboard. You do not need to enter a value in every field in order to filter the data.

![filter](images/UFO_table.png)

Results should display in the same table format filtered in the criteria entered!

![results](images/UFO_results.png)

## Summary

There are some potential limitations to this setup as it stands now. First, this data set is static and will not update with new information as it becomes available. Secondly, as good as this data set may be we have not cleaned it. There could be misspellings or typos that could effect what would show up in a particular search result. It would also be helpful to standardize things like the duration column so that each entry is in the same format accross the entire row. This could enable us to more easily filter by every column. Lastly, the searches are case sensitive and must exactly match the format of the data entry. It might be helpful to add some lines in the JavaScript that correct for case and take some common date formats into account.

I'm also not quite sure if the website will display properly. It does on my computer, but when I published on Github Pages some of the formatting (like text color) got lost. Some of it is a problem with the CSS I believe. However, the JavaScript runs perfectly and the table does filter as it's supposed to.
