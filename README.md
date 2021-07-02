# Generic GPX
My alternative to GPX - a GPS telemetry standard that DOESN'T have unique tags

Used for a project where GPS telemetry tracks needed to be iterative. This is cumbersome on the [GPX](https://wiki.openstreetmap.org/wiki/GPX) standard, which contains unique trackpoint tags that include telemetry within the tag. This format simply splits this telemetry data into their own tags nested underneath the generic trackpoint.

Contains the format file (to be used with Phil Harvey's [ExifTool](https://github.com/exiftool/exiftool)) and a sample generic-gpx output file.
