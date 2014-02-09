# Constellation lines

## Introduction
The file [ConstellationLines.dat](ConstellationLines.dat) contains lists of stars from the [Bright Star
Catalogue](https://cdsarc.unistra.fr/viz-bin/cat/V/50) (BSC, 5th Revised Ed. (Preliminary Version) (1991))
that can be connected in order to draw the basic constellations of our night sky.  The file was originally
created in early 2005, for what was to become the Dutch/Flemish popular-astronomy website
[hemel.waarnemen.com](http://hemel.waarnemen.com).  Four static example maps can be found on that website
(with labels in Dutch): [North pole](http://hemel.waarnemen.com/kaarten/vast/noordpool.jpg), [Equator ~0h
RA](http://hemel.waarnemen.com/kaarten/vast/equator_08-00-16.jpg), [Equator ~12h
RA](http://hemel.waarnemen.com/kaarten/vast/equator_20-12-04.jpg), [South
pole](http://hemel.waarnemen.com/kaarten/vast/zuidpool.jpg).


## Using the data
The data file is in plain text.  Each data line in the file shows a list of space-separated values that can be
used to draw a single line on the map (usually a single constellation).  To keep the number of lines limited
(most constellations use up a single line in the file), sometimes a drawn line retraces itself without 'taking
the pen off the map'.  Note that some constellations (e.g. Cru) cannot be drawn using only one line, and have
multiple data lines in this file.


## Column descriptions
1. Latin constellation abbreviation (`%3s`);
2. number of stars to draw lines between = number of numbers following on this line (`%2d`);
3. (rest of the columns) BSC numbers for those stars (1-9110) (`%4d` each).



## Copyright
Copyright (c) 2005-2014, Marc van der Sluys, [hemel.waarnemen.com](http://hemel.waarnemen.com).


## Licence

The data can be used under the terms of the Creative Commons
[Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0) licence.

![CC BY 4.0](https://licensebuttons.net/l/by/3.0/88x31.png "CC BY 4.0")
