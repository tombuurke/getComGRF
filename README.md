# getComGRF
Calculate Center of Mass position from Ground Reaction Forces

**Inputs**

GRF    - Ground reaction force (m) from single forceplate.
           NB: In case of multiple forceplates e.g. split-belt treadmill,
           combine the 2 GRFs to a single GRF, for more info see Kwon3D:
           http://www.kwon3d.com/theory/grf/multi.html
           
Cop    - Center of pressure (m) from single forceplate.
           NB: In case of multiple forceplates e.g. split-belt treadmill,
           combine the 2 Cops to a single Cop, for more info see Kwon3D:
           http://www.kwon3d.com/theory/grf/multi.html
           
Time   - Time array corresponding to the GRF and Cop vector.

sf     - Sample frequency (Hz)

Weight - Subject weight (kg)

**Output**

Com    - Mediolateral center of mass position

**Originally written by Tom J.W. Buurke (2017)**

Department of Human Movement Sciences, University Medical Center 
  Groningen, University of Groningen, The Netherlands
  
Department of Movement Sciences, KU Leuven, Leuven, Belgium

**Version 1.0** - Changelog (August 15 2017):

First version

**Version 1.1** - Changelog (January 5 2022):

Cleaned up for publication
