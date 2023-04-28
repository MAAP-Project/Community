---
name: Data Request
about: Suggest a data set for ingestion in the platform
title: '[Data]:'
labels: MSFC
assignees: freitagb, wildintellect

---

**Dataset Name**
*What is the name of the data requested?*

**Dataset Description**
*Please provide a short description of the data.*

**Requestor name/affiliation**
*What is your name and research affiliation?*

**Platform/Instrument/Method**
*What Sensor, and/or platform used to collect data?*

**URL or DOI to dataset description**

**URL to download or access data**

**Data License**
*Is the data openly available? Please list the license if you know it (e.g. CC-BY)*

**Intended science use case**
*Please describe how you intend to use the data, or the expected relevance to MAAP users.*

## Spatio-Temporal Asset Catalog (STAC)

This collection will be published as a Spatio-Temporal Asset Catalog (STAC) Collection. You can read the complete STAC collection spec here: https://github.com/radiantearth/stac-spec/blob/master/collection-spec/collection-spec.md.

The minimum set of fields required to submit a STAC collection are:

**id:** Identifier for the Collection that is unique across the provider. This is typically an abbreviated and hyphenated or camel-cased version of the dataset name, For example `gedi_l2a_v002` for "GEDI L2A Elevation and Height Metrics Data Global Footprint Level V002".

**title:** A short descriptive one-line title for the collection. Technically, this is not requried by the STAC Spec but it is used by the STAC browser.

**description:** Detailed multi-line description to fully explain the collection.

**spatial extent:** A bounding box for the potential spatial extents covered by the collection. Read more in the [spatial-extent-object section of the spec](https://github.com/radiantearth/stac-spec/blob/master/collection-spec/collection-spec.md#spatial-extent-object).

**temporal extent:** Describes the temporal extents of the collection as an interval. Read more in the [temporal-extent-object section of the spec](v).

**links:** A list of references to other documents. There must be a at least one link and we highly recommend and may require in the future link to documentation which includes details about how to access and open the data.

**Again, this is the minimum set of information to publish to STAC. If there is other information to include about the dataset which might be relevant to other users in finding or using the dataset, please let us know and we can help determine how to include that information in the STAC collection.**

## Optional

**Approximate size of data**
*Please estimate of how many GB/TB/PB the data is.*

**Additional information**
*Any additional info you think is relevant, possibly including spatial or temporal subset if applicable.*
