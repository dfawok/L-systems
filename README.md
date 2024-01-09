
Extract from Boudon et al., 2012 "L-Py: an L-system simulation framework for modeling plant architecture development based on a dynamic language" Front. Plant Sci., (3)

"The formalism of L-systems has emerged as the major paradigm for constructing FSPMs. Introduced in the late 1960s by A. Lindenmayer as a formalism for describing developmental processes in biology (Lindenmayer, 1968),
L-systems proved well suited to describe models of plant development (Prusinkiewicz and Lindenmayer, 1990; Prusinkiewicz, 1998, 1999). In L-systems, the plant is represented by a bracketed string, whose elements, called modules,
represent the plant’s components (metamers, meristems, flowers, etc.). Modules consist of a symbolic name and an optional set of parameters. Modules with the same name represent the same type of component 
(e.g., I for internode, M for meristem, etc.). A set of rules (also called productions) then defines how each module transforms over time. In particular, a module can produce one or more new modules, thus giving a possibility 
of adding new components to the structure. The formalism of L-systems has emerged as the major paradigm for constructing FSPMs (c.f. FSPM Special Issue, 2005, 2008, 2011). Introduced in the late 1960s by A. Lindenmayer
as a formalism for describing developmental processes in biology (Lindenmayer, 1968), L-systems proved well suited to describe models of plant development (Prusinkiewicz and Lindenmayer, 1990; Prusinkiewicz, 1998, 1999). [...]"

L-py is an open-source L-system-based modeling environment based on Python. To install L-Py, you need to create an environment (named for instance lpy) :

conda create -n lpy openalea.lpy -c fredboudon -c conda-forge

The package openalea.lpy is retrieved from the fredboudon channel (developement) and its dependencies will be taken from conda-forge channel. Then, you need to activate the L-Py environment:

conda activate lpy

And then run L-Py:

lpy

N.B: A complete master class is available on Youtube on the channel "ROMI - Robotics for Microfarms"

Here are stored some important tutorials to start with L-systems language and to learn for example:

How to create basic architecture with different kind of organs (stem, leaves, buds...) and functions to modify their shapes,

![tutorial_1](https://github.com/dfawok/L-systems/assets/128010740/1e5cc912-de62-4a59-9110-80b01248c095)

How to transform architectural data stored under MTG format into L-systems,

![transform_MTG_to_L_system](https://github.com/dfawok/L-systems/assets/128010740/3ee771ec-bb41-4619-be76-a66cd3239efc)

How creating and combining functions to model different gradients within the plant

![tutorial_3](https://github.com/dfawok/L-systems/assets/128010740/1733fc56-ac77-44e6-b552-e36780412bb4)



