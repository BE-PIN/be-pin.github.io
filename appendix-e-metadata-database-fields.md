# Appendix E — Metadata database fields

*Section 8.2.3 — Description of the fields of the metadata database*

Description of the metadata recorded for each data source held in the database. Five
fields are populated from a controlled vocabulary; those keywords are defined in the
second half of this appendix.

## Field definitions

*Table 8. Description of the fields constituting the metadata database.*

| Field | Description |
| --- | --- |
| `id` | Unique internal id of the dataset |
| `name` | Name of the surveillance system or dataset |
| `shortDescription` | Short description of the dataset |
| [`type`](#type) | Type of data |
| `institution` | Organization(s) responsible for maintaining the data |
| `source` | Description of the provenance of the data |
| `linkURL` | Link(s) to webpage(s) describing the data |
| `linkDCAT` | URI of a DCAT-AP resource available in a catalogue |
| `contactInfo` | Email address(es) or contact details to obtain more information on the data |
| [`detailLevel`](#detaillevel) | Keyword indicating the granularity of data available in terms of personal information |
| [`accessibility`](#accessibility) | Keyword indicating the availability status of the data |
| [`updateFrequency`](#updatefrequency) | Keyword indicating the frequency update of the dataset |
| `targetPopulation` | Description of the group of individuals covered in the data and assessment of the exhaustivity of the data collection |
| [`category`](#category) | Keyword indicating the category of data as defined in Ingelbeen *et al.* |
| `isCovid` | Flag indicating whether the dataset is specific to the COVID-19 pandemic or not (1 = COVID-19 specific) |
| `isBelgium` | Flag indicating whether the dataset is specific to Belgium or has an international scope (1 = Belgian specific) |
| `isActive` | Flag indicating whether the data collection is still active or not (1 = Active) |

## Keyword definitions

*Table 9. Description of the keywords used to populate the controlled-vocabulary fields
of Table 8.*

### `type`

| Keyword | Description |
| --- | --- |
| `table` | Classical tabular dataset |
| `collection` | A collection of datasets, not necessarily linked with each other |
| `database` | An ensemble of structured tables and relations |
| `data product` | A database available for reuse in part or as a whole |
| `platform` | A tool to access and analyze data |

### `detailLevel`

| Keyword | Description |
| --- | --- |
| `nominative` | Contains variable or combination of variables allowing direct identification of individuals |
| `pseudonymized` | Contains pseudonymized (reversible) identifier(s) |
| `longitudinal follow-up` | Individuals are evaluated at multiple timepoints |
| `case-based` | Contains individual level information but without nominative data or pseudonymized identifiers |
| `aggregated` | Counts by categories |
| `metadata` | Only information on the data, no data itself |

### `accessibility`

| Keyword | Description |
| --- | --- |
| `opendata` | Data is readily available from a repository (or upon request) |
| `requestable` | Data can be shared after agreement with data holder |
| `restricted` | Data cannot be accessed without further approval |

### `updateFrequency`

| Keyword | Description |
| --- | --- |
| `real-time` | Update may occur at any time (or near real-time) |
| `daily` | Update occurs on a daily basis |
| `weekly` | Update occurs on a weekly basis |
| `monthly` | Update occurs on a monthly basis |
| `yearly` | Update occurs on a yearly basis |
| `irregular` | Update does not follow strict schedule |
| `static` | Data correspond to a snapshot in time |

### `category`

| Keyword | Description |
| --- | --- |
| `traditional` | Usual human health surveillance (e.g. case list) |
| `one health` | Integration of animal health surveillance |
| `behavioral` | Related to host and vector behavior (e.g. mobility data) |
| `programmatic` | Related to a public health intervention (e.g. vaccination campaign) |
| `population factor` | Providing background information on host at individual or population level (e.g. seroprevalence study) |
| `pathogen characteristic` | Related to the pathogen itself (e.g. genomic) |
| `other` | — |

---

<sub>Reproduces Tables 8 and 9 of the main report. Field names and keyword values are
given verbatim; a small number of spelling errors in the descriptions have been
corrected.</sub>
