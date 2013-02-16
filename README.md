# Honeypot Globe Data

## About
You can see this data in action, and learn more about this project, on [plainlystated.com](http://www.plainlystated.com/honeypot-globe/).

## Data Formats
The data in kippo.json and kippo.md comes from the same source, but is represented differently.

#### JSON
The [JSON data](https://github.com/honeypot-globe/data/blob/gh-pages/kippo.json) is comprised of triplets of (latitude, longitude, magnitude), where magnitude indicates the relative number of login attempts from this position. The magnitude is computed using a slight log (base 1.1), to smooth out a numbers a bit.

#### Markdown
The [markdown data](https://github.com/honeypot-globe/data/blob/gh-pages/kippo.md) is for anyone interested in a human-readable format of the data, and indicates the actual number of login attempts from a location.
