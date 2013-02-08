# scape-component-profiles
To guarantee interoperability between services and enable automation of preservation processes, preservation components must have a standardised interface. The preservation components are based on [Taverna](http://www.taverna.org.uk/) workflows as a common language. They either wrap command line tools with necessary post-processing, are directly implemented as workflows or are composed of other components.

To allow discoverability, components must be annotated with relevant information using a common vocabulary. Standardised interfaces add the possibility of automating parts of a preservation process. Additionally, dependencies allow an execution platform to run the components. All these aspects are defined as preservation component profiles.
The Taverna workbench can be extended to easily validate workflows against profiles and create and publish components in the component catalogue [myexperiment.org](http://www.myexperiment.org/).

# Repository
This repository contains the profiles, the corresponding ontology and other related files.

## Profiles
This folder contains the profiles that describe different component types. They specify the metadata that must be added to workflows to adhere to profiles. Profiles are written as XML documents that are validated against the [Taverna component profile XSD](http://ns.taverna.org.uk/2012/component/profile/ComponentProfile.xsd).

The profile specifies mandatory workflow elements (e.g. *InputPort*, *OutputPort*, and *Activity*). For the component itself and each element, the *annotations* and *semanticAnnotations* are defined. Ports depth can also be restricted. Semantic annotations are based on the *ontology* specified in the profile. 

## Ontology
The ontology is used to add semantic annotations to the workflows.



This work is licensed under a [Creative Commons Attribution-NonCommercial 3.0 Unported License](http://creativecommons.org/licenses/by-nc/3.0).

[![Creative Commons Attribution-NonCommercial 3.0 Unported License](http://i.creativecommons.org/l/by-nc/3.0/88x31.png)](http://creativecommons.org/licenses/by-nc/3.0)