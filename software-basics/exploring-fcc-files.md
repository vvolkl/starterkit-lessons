# Inspecting an FCC data file

{% objectives "Learning Objectives" %}

* Get to know FCC data files and the tools to inspect them

{% endobjectives %} 

FCC Data is generally stored in ROOT files. The layout of the file is determined by the "Event Data Model", which describes conceptually how the data is structured, and technically what branches are written in the final file.

The file we take from `eos`
contains simulated data, with particles from the generators and hits from the detector simulation.

