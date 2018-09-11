# GAP-Analysis-Species
The creation of the Analysis Package for protection status of terrestrial vertebrate species pre-dates the current concepts of scientific workflows leading toward vetted tools of various kinds. It is one of the first "BAPs" that we launched in the National Biogeographic Map v1.0. This BAP and the gap analysis of ecological systems both rely on an underlying analaytical database with a set of pre-calculated metrics based on 2001 GAP Species Habitat Maps, 2001 GAP Land Cover, and PAD-US 1.4 protection status. We are in the process of a) spinning these precalculated data up behind a more robust API that we can share and b) building a new computational method that will allow us to update to newer versions of some of the data and calculate stats in real time.

In the near term, we've captured a number of the historic artifacts in this repo to help explain how we got to the live tools viewable in the [National Biogeographic Map](https://maps.usgs.gov/biogeography) and as a building point for future analysis package development.

The workflow here is interesting in that it involved a rich exchange between scientists, data managers, and software engineers to come up with a way of putting an early idea for the BAP idea online. It helped us refine our thinking about where we want to be in this work, particularly a way to narrow the gap between scientific workflow and online tool availability for resource managers. Many of the ideas for this BAP are encapsulated in the Powerpoint file in this repo that laid out specific ideas for the two "GAP BAPs." This document and surrounding conversation led to working software that is not particularly practical to share in this repo (too tied up with other software) but that helped us build toward current thinking.

An included zip package in this repo also contains a set of files associated directly with the early generation of this analysis package. It comes from a JIRA issue that tracked the core of the work at that time.

# USGS Provisional Software
This software is preliminary or provisional and is subject to revision. It is being provided to meet the need for timely best science. The software has not received final approval by the U.S. Geological Survey (USGS). No warranty, expressed or implied, is made by the USGS or the U.S. Government as to the functionality of the software and related material nor shall the fact of release constitute any such warranty. The software is provided on the condition that neither the USGS nor the U.S. Government shall be held liable for any damages resulting from the authorized or unauthorized use of the software.
