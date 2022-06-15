# UFO Sightings Database

### Overview
The projected is designed to allow a user to search through a UFO sighting database by selecting location, date, and a description of what was seen. With that information, users can make deteriminations of the validity of those sightings and further research other sightings.

### Using the site
The site itself is fairly basic. To search, a user inputs data on the left side, then filtered results show up in the table. Though not all fields are required to perform the search, the more data the better to help narrow down UFO sightings.

![ufo_site](https://i.postimg.cc/gcwTdKbG/ufo-site.png)

### Drawbacks and recommendations
Though the UFO database is mostly complete, with the current workflow, it isn't as easy to search as could be possible. User input data must be exact, including capitalization and punctuation. 

Possible solutions to this would include transforming the user input on the backend, to match what's listed in the database. This could be done with forced lower case on any user input, and using regular expressions to help search the data.  Another solution could be the use of dropdown menus and calendar-picker, for fields where it may be possible to standardize, like data, location state, location country, and shape of the object.
