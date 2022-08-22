# UFOs

## Overview of the analysis:
Produce a webpage containing a dynamic table. Update to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time under the date, city, state, country, and shape categories.

## Resources:
- Software: HTML5, Bootstrap, Javascipt
- Data file(s): data.js

## Results:
Opening the site a person is no longer limited to having to view every sighting for the date they search or even needing to know the date.

![image_name](/resources/initial_view.png)

A person may not know what the date was that the sighting they are looking for occurred on but they may know the location. For example "el cajon, ca"

![image_name](/resources/elcajon_ca_view.png)

Now that they know the sighting they wanted to see occurred on "1/4/2010", they can add the date to the search criteria and see that listing by itself.

![image_name](/resources/elcajon_ca_01042010_view.png)

Now they want to see other sightings in "ca" on the same date. They can add the state as "ca" in the search criteria and remove the city name.

![image_name](/resources/all_ca_01042010_view.png)

And finally after seeing that there were two "light" anomalies on "1/4/2010" in "ca", now they want to see how many other locations also had "light" sightings on the same day. So they can just remove the "ca" from the state option and add "light" to the shape category.

![image_name](/resources/all_lights_on_01042010_view.png)


## Summary:
One of the biggest drawbacks to the current design of this site is that it is case sensitive. Searching for a capitalized state abbreviation (i.e. CA, AR), will return zero results

Some additional recommendations for development of this site would be to:
1. update the search query to not be case sensitive so that searching for criteria,such as state abbreviations, will recognize both upper or lower casing.
2. add mouse-over definitions for each search input header showing possible options.
