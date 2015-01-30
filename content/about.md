+++
weight = "0"
type = "post"
draft = false
sidebar = true
Title = "ABOUT: IOOS GitHub Pages"
date = 2014-08-04T07:56:39Z
url = "index.html"
+++


# Projects
<a name="System Integration Test"></a>

## IOOS Catalog of Services and Datasets

* [IOOS Web Catalog](http://catalog.ioos.us)
* [GitHub repository](https://github.com/ioos/) that holds source codes and modules of the IOOS Catalog

## [System Integration Test](https://github.com/ioos/system-test)

The system integration test development site on github contains IPython notebooks demonstrating how to access data from servers in various scenarios. 

## [ncSOS](https://github.com/asascience-open/ncSOS)

NcSOS adds an OGC SOS service to datasets in your existing THREDDS server. It complies with the [IOOS SWE Milestone 1.0 templates](https://github.com/ioos/sos-guidelines/tree/master/template/milestone1.0) and requires your datasets be in any of the [CF 1.6 Discrete Sampling Geometries](http://cfconventions.org/Data/cf-conventions/cf-conventions-1.6/build/cf-conventions.html#discrete-sampling-geometries).

## i52N and related activities like sensor web harvesters

*  [i52N-SOS](http://ioos.github.io/i52n-sos/), an IOOS customized build of the [52°North Sensor Observation Service (SOS)](http://52north.org/sos) that extends the stock upstream [52°North SOS](https://github.com/52North/SOS) with IOOS specific encoding formats, test data, and more.
* [IOOS SOS Compliance Test Tool](https://github.com/ioos/ioos-sos-compliance-tests), a set of CTL ([compliance test language](http://portal.opengeospatial.org/files/?artifact_id=33085)) files and utility scripts to test IOOS SOS implementations.
* [IOOS SOS Validator](https://github.com/ioos/ioos-sos-validator) for simple schema validation of SOS responses and templates 

# Guidelines and specifications

## [Data Provider Guidelines](http://www.ioos.noaa.gov/data/contribute_data.html)

The _**Guidance for Implementation of the Integrated Ocean Observing System (IOOS) Data Management and Communications (DMAC) Subsystem**_ describes the responsibilities of an IOOS Data Provider published on the official IOOS Web site.


## [SOS Guidelines](http://ioos.github.io/sos-guidelines)

A website with documentation on using IOOS SOS v1.0 that includes:    

* [Overview of SOS activities in IOOS](http://ioos.github.io/sos-guidelines/about/)  
* [IOOS SOS 1.0 Web Service Description Document](http://ioos.github.io/sos-guidelines/doc/wsdd/sos_wsdd_github_notoc/)   
* [IOOS SOS Profile Templates](http://ioos.github.io/sos-guidelines/template/)  
* [List of IOOS-specific compliance tests](http://ioos.github.io/sos-guidelines/doc/testing/sos_test_list_github_notoc_summary/)   

## netCDF and/or opendap guidelines
* See [https://github.com/dpsnowden/netcdf-guidelines] for some initial ideas on what this needs to contain.
* [IOOS Compliance Checker](https://github.com/ioos/compliance-checker) tool to check local/remote netCDF datasets against a variety of compliance standards. 

## [Data encoding in CSV/TSV](http://ioos.github.io/ioos-csv-tsv/)

The _**IOOS Convention for observation data encoding in CSV/TSV**_ document describes the rukes and constraints for encoding observation data as plain text Comma-Separated Values (CSV) or Tab-Separated Values (TSV).

## [Asset Identifiers](http://ioos.github.io/conventions-for-observing-asset-identifiers/)

The _**IOOS Conventions for Observing Asset Identifiers**_ document describes the conventions used by the Integrated Ocean Observing System (IOOS) program to assign an identifier to IOOS-related observing assets including measurement stations, platforms and sensors.

## [Vocabularies](https://ioos.github.io/vocabularies)

A collection of the Instructions and Guidelines for use of Controlled Vocabularies in IOOS-compliant data services.

## [Data Services for Animal Telemetry](http://ioos.github.io/animal-telemetry/)
 
* A brief [description](http://ioos.github.io/animal-telemetry/about/) of the National Animal Telemetry Network (ATN). 
* [Strategic Plan And Recommendations](http://ioos.github.io/animal-telemetry/animal-telemetry-plan/) for a National ATN through U.S. IOOS

## Biological Data Services 

* [Data Enrollment Process](http://ioos.github.io/biological-data-services/) proposed and supported by IOOS DMAC to support sharing and integration of aquatic biological data.

# Contributing and changes

To make changes to this website and add information, see the [Website Deployment Workflow](website_deployment_workflow_updated) page. 

