# SPICE symbol library with LTspice assemblies

## Usage

This is a collection of SPICE compatible models and LTspice assemblies.
To import these into LTspice open the "Simulate" menu then click "Control Panel",
there go to the "Sym. & Lib. Search Paths" tab, input the path to this directory
in both the "Library Search Path" and "Symbol Search Path" text fields and accept the
changes. When you want to add any of these components to your schematic, while in the
"Select Component Symbol" window select this directory from the "Top Directory" drop-down
list, the assemblies here should be listed.

## Adding models and assemblies

To add models or assemblies just drop them into this directory, the name being
the model name for the component, then create a ``.txt`` file with the sources for
the added symbols and assemblies.
