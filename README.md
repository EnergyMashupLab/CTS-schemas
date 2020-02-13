Common Transactive Services Schemas
=========================

Background
----------
The Common Transactive Services was initially developed in Phase One of the [NIST Transactive Energy [Modeling and Simulation] Challenge](https://www.nist.gov/el/smart-grid/hot-topics/transactive-energy-modeling-and-simulation-challenge). Phase One was a 2015-2016 effort to enable and extend transactive energy tehnologies.


The initial Common Transactive Services report, along with related work on transactive microgrids, is in Github repositories
- [Transactive Energy Challenge](https://github.com/EnergyMashupLab/TransactiveEnergyChallenge) at [https://github.com/EnergyMashupLab/TransactiveEnergyChallenge](https://github.com/EnergyMashupLab/TransactiveEnergyChallenge) and
- [Microgrids](https://github.com/EnergyMashupLab/microgrids) at [https://github.com/EnergyMashupLab/microgrids](https://github.com/EnergyMashupLab/microgrids), containing use cases and requirements for transactive microgrids.

Papers were presented at the [2016 Transactive Energy Conference](https://www.gridwiseac.org/historical/tes2016/tes2016.aspx) sponsored by the [GridWise Architecture Council](https://www.gridwiseac.org/) in Portland Oregon. See the conference link for the Proceedings.

Technical Description Schemas Hierarchy
--------------------------------------

This repository contains the following subdirectories, each with its own README, that contain schemas and models:

-   xsd – XML schemas for the Common Transactive Services (CTS)

-   json — JSON schemas to serialize the Common Transactive Services (CTS)
    payloads

-   UML - PDF files of UML models used from Energy Interoperation, EMIX, and the XML schemas in this folder

Built With
----------

These schemas were originally defined for the [NIST-CTS-Agents](https://github.com/EnergyMashupLab/NIST-CTS-Agents) which project uses Github, Maven, Java 8, and Spring Boot 2. 

That project now uses the Java Persistence API (JPA) and does not directly consume these schemas, although the project Java code was based on these XML Schemas. These schemas are in turn an evolution of the [OASIS Energy Interoperation](http://docs.oasis-open.org/energyinterop/ei/v1.0/os/energyinterop-v1.0-os.html) schemas. See the individual README files for more information.

Authors
-------

-   **William Cox** - *Architecture* - [Cox Software Architects
    LLC](http://coxsoftwarearchitects.com/)

-   **Toby Considine –** *Architecture* – [TC9 Inc](http://www.tc9.com/)

License
-------

This project is licensed under the Apache 2.0 License.

Acknowledgments
---------------

