# This is a map of ballot drop boxes and early voting centers in Baltimore City. Locations and addresses are sourced from Baltimore City:
https://s3.amazonaws.com/baltimorecity.gov.if-us-east-1/s3fs-public/2025-12/updated_ballot_drop_off_locations-2026.pdf
https://www.baltimorecity.gov/boe/our-work/election-information/voting-centers

# README – Standalone qgis2web Export

This export is completely "self-contained".

To view the map, simply open "index.html" by double-clicking it.
No web server or additional software is required.

The map works because all the required JavaScript libraries are included
in the export. The application loads the GeoJSON layer data and their styles
directly from the local files.

## Publishing on a Website

If you upload the entire folder to a web server, the map will work 
immediately by opening the "index.html" file.

Example:

"https://www.example.com/my-map/index.html"
