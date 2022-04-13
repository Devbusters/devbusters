---
layout: blog-post
title:  "Bring CIMplicity to your data!"
date:   2022-04-10 10:00:00 +0000
author: Diogo Silva
tags: splunk cim data extractions
categories: splunk
comments: true
---
In this post we'll be covering Splunk's Common Information Model, what is it, how can it be usefull to you, 

# What is the Common Information Model

The Splunk Common Information Model (CIM) is a shared semantic model focused on extracting value from data. The CIM is implemented as an add-on that contains a collection of data models, documentation, and tools that support the consistent, normalized treatment of data for maximum efficiency at search time.

The CIM add-on contains a collection of preconfigured data models that you can apply to your data at search time. Each data model in the CIM consists of a set of field names and tags that define the least common denominator of a domain of interest. You can use these data models to normalize and validate data at search time, accelerate key data in searches and dashboards, or create new reports and visualizations with Pivot.

The add-on also contains several tools that are intended to make analysis, validation, and alerting easier and more consistent. These tools include a custom command for CIM validation and a common action model, which is the common information model for custom alert actions. See Approaches to using the CIM for more information about the tools available in the CIM add-on.


# How is this useful?

The CIM helps you to normalize your data to match a common standard, using the same field names and event tags for equivalent events from different sources or vendors. The CIM acts as a search-time schema ("schema-on-the-fly") to allow you to define relationships in the event data while leaving the raw machine data intact.

After you have normalized the data from multiple different source types, you can develop reports, correlation searches, and dashboards to present a unified view of a data domain. You can display your normalized data in the dashboards provided by other Splunk applications such as Splunk Enterprise Security and the Splunk App for PCI Compliance. The dashboards and other reporting tools in apps that support CIM compliance display only the data that is normalized to the tags and fields defined by the Common Information Model.

The Splunk Common Information Model add-on is packaged with Splunk Enterprise Security and the Splunk App for PCI Compliance.



Check out Splunk's latest [Common Information Model Docs][splunk-cim-docs] for more info on how to get the most out of CIM and its datamodels. 

[splunk-cim-docs]: https://docs.splunk.com/Documentation/CIM/latest/User/Overview
[splunk-cim-app]: https://splunkbase.splunk.com/app/1621/