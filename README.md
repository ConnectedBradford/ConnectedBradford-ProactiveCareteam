<a href="https://www.bradfordresearch.nhs.uk/our-research-teams/connected-bradford/">
  <img align="left" alt="ConnectedBradford" width="55px" src="https://github.com/ShoreRob1/Images/blob/main/CB%20logo%201.png?raw=true" />
</a>

This is the Connected Bradford Primary Care GitHub page where you can find a summary of the dataset(s), data dictionaries and helpful code.

# Flexible Data Model (FDM) 

As a standard all our research datasets are stored in a Flexible Data Model (FDM) this is loosely based on the OHDSI standards and includes a person and onbservation period table that are in OHDSI standards .Click [here](https://www.ohdsi.org/data-standardization/) for details if the OHDSI CDM Model. 

# Connected Bradford Proactive Care team (PACT)

Contains the scripts and data dictionary for the PACT FDM . This is the data gathered by Bradford District Care tust from the Proactive Care team (PACT)

For details of Pact please click here https://www.bdct.nhs.uk/services/proactive-care-team/

It contains approximately 2000 patients with the clinical record. The dataset has been fully anonymised, but can link to other FDM's.

The latest extract of PACT data is stored in CB_FDM_PACT - build date 2024-04-26


# Tables
The Bradford Royal Infirmary FDM (warehouse) is made up of 2 source tables (summarised below and data dictionaries linked) from routinely collected data from Bradford Royal Infirmary for 2279 individuals and their routinely collected data. 

The dates relevant for the latest build are: 2020-09-17	to	2023-04-19

The source tables are largely populated by fields with the tbl_ where there is a person and a start and end date, and cb_ where there is no identifiable person, these are typically lookups.

### The source data tables are: 

tbl_PACT_evaluation_contacts
tbl_PACT_evaluation_detail

For more information please go to the docs folder. 

There is no identifiable information (such as names, date of birth, address,) available to the Connected Yorkshire project so patient confidentiality and privacy will be protected.

