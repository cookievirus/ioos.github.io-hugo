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
* [GitHub repository](https://github.com/ioos/catalog) that holds source codes and modules of the IOOS Catalog

## System Integration Test

The [system integration test development site](https://github.com/ioos/system-test) on github contains IPython notebooks demonstrating how to access data from servers in various scenarios. 

## IOOS ncSOS

The [IOOS ncSOS](https://github.com/asascience-open/ncSOS) adds an OGC SOS service to datasets in your existing THREDDS server. It complies with the [IOOS SWE Milestone 1.0 templates](https://github.com/ioos/sos-guidelines/tree/master/template/milestone1.0) and requires your datasets be in any of the [CF 1.6 Discrete Sampling Geometries](http://cfconventions.org/Data/cf-conventions/cf-conventions-1.6/build/cf-conventions.html#discrete-sampling-geometries).

## i52N and related activities like sensor web harvesters

*  [i52N-SOS](http://ioos.github.io/i52n-sos/), an IOOS customized build of the [52°North Sensor Observation Service (SOS)](http://52north.org/sos) that extends the stock upstream [52°North SOS](https://github.com/52North/SOS) with IOOS specific encoding formats, test data, and more.
* [IOOS SOS Compliance Test Tool](https://github.com/ioos/ioos-sos-compliance-tests), a set of CTL ([compliance test language](http://portal.opengeospatial.org/files/?artifact_id=33085)) files and utility scripts for thorough standard validation and test of the IOOS SOS implementations.

<!-- * [IOOS SOS Validator](https://github.com/ioos/ioos-sos-validator) for simple schema validation of SOS responses and templates --> 

# Guidelines and specifications


## DMAC Implementation Guidelines for Data Providers

The [_**Guidance for Implementation of the Integrated Ocean Observing System (IOOS) Data Management and Communications (DMAC) Subsystem**_](http://www.ioos.noaa.gov/data/contribute_data.html) describes the responsibilities of an IOOS Data Provider published on the official IOOS Web site.

## IOOS Service Registration Guidelines

Registration of the IOOS services allows the wide range of various clients to efficiently discover U.S. IOOS data. The [IOOS Service Registration Guide](http://ioos.github.io/registry/) describes the registration process, elaborates on IOOS Catalog and NGDC Registry interaction, and provides examples of Registry querying for metadata. 

## SOS Guidelines

A [website](http://ioos.github.io/sos-guidelines) with documentation on deploying IOOS SOS v1.0 that includes:    

* [Overview of SOS activities in IOOS](http://ioos.github.io/sos-guidelines/about/)
* [List of IOOS-specific compliance tests](http://ioos.github.io/sos-guidelines/doc/testing/sos_test_list_github_notoc_summary/)  
* [IOOS SOS 1.0 Web Service Description Document](http://ioos.github.io/sos-guidelines/doc/wsdd/sos_wsdd_github_notoc/)   
* IOOS SOS Response Templates:
  - [GetCapabilities](http://ioos.github.io/sos-guidelines/template/SOS-GetCapabilities/)
  - [DescribeSensor for a network of platforms](http://ioos.github.io/sos-guidelines/template/SML-DescribeSensor-Network/)
  - [DescribeSensor for a single platform](http://ioos.github.io/sos-guidelines/template/SML-DescribeSensor-Station/)
  - GetObservation:
     * [Generic OM part](http://ioos.github.io/sos-guidelines/template/OM-GetObservation/)
     * [TimeSeries SWE Data Record’s static and dynamic fields for multiple stations with multiple sensors](http://ioos.github.io/sos-guidelines/template/SWE-MultiStation-TimeSeries/)
     * [TimeSeries SWE Data Record’s static and dynamic fields for multiple stations with multiple sensors and QC elements](http://ioos.github.io/sos-guidelines/template/SWE-MultiStation-TimeSeries_QC/)
     * [TimeSeries SWE Data Record’s static and dynamic fields for a single station with a single sensor](http://ioos.github.io/sos-guidelines/template/SWE-SingleStation-SingleProperty-TimeSeries/)
     * [TimeSeriesProfile SWE Data Record’s static and dynamic fields for a station with profiling sensors](http://ioos.github.io/sos-guidelines/template/SWE-SingleStation-TimeSeriesProfile/)
     * [TimeSeriesProfile SWE Data Record’s static and dynamic fields for a station with profiling sensors and QC elements](http://ioos.github.io/sos-guidelines/template/SWE-SingleStation-TimeSeriesProfile_QC/)   

## netCDF and/or opendap guidelines
* See [https://github.com/dpsnowden/netcdf-guidelines] for some initial ideas on what this needs to contain.
* [IOOS Compliance Checker](https://github.com/ioos/compliance-checker) tool to check local/remote netCDF datasets against a variety of compliance standards. 

## Data encoding in CSV/TSV

The [_**IOOS Convention for observation data encoding in CSV/TSV**_](http://ioos.github.io/ioos-csv-tsv/) document describes the rukes and constraints for encoding observation data as plain text Comma-Separated Values (CSV) or Tab-Separated Values (TSV).

## Asset Identifiers

The [_**IOOS Conventions for Observing Asset Identifiers**_](http://ioos.github.io/conventions-for-observing-asset-identifiers/) document describes the conventions used by the Integrated Ocean Observing System (IOOS) program to assign an identifier to IOOS-related observing assets including measurement stations, platforms and sensors.

## Vocabularies

A [collection of the Instructions and Guidelines for use of Controlled Vocabularies](https://github.com/ioos/vocabularies) in IOOS-compliant data services (the link temporarily leads to the GitHub repository itself rather then to the GitHub Pages).

## Data Services for Animal Telemetry

A [collection](http://ioos.github.io/animal-telemetry/) of documents describing animal telemetry implementation: 

* A brief [description](http://ioos.github.io/animal-telemetry/about/) of the National Animal Telemetry Network (ATN). 
* [Strategic Plan And Recommendations](http://ioos.github.io/animal-telemetry/animal-telemetry-plan/) for a National ATN through U.S. IOOS
* [IOOS Animal Acoustic Telemetry (AAT) Data Project](http://ioos.github.io/animal-telemetry/aat_data_ioostech_wiki/).

## Biological Data Services 

A [collection](http://ioos.github.io/biological-data-services/) of documents describing data services for biological objects:

* [Data Enrollment Process](http://ioos.github.io/biological-data-services/biological-data-procedure/) proposed and supported by IOOS DMAC to support sharing and integration of aquatic biological data.
* [IOOS Biological Observations Services](http://ioos.github.io/biological-data-services/biological-observations/) that address the DMAC requirements for biological observations standards and interoperability.

# Contributing and changes

To make changes to this website and add information, see the [Website Deployment Workflow](website_deployment_workflow_updated) page. 

