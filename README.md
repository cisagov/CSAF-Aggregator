# CISA CSAF Aggregator
The CISA CSAF (Common Security Advisory Framework) Aggregator Repository serves as a centralized location to list or mirror CSAF Trusted Providers, enabling a single point of access for retrieving machine-readable CSAF documents. This supports automation and streamlines vulnerability management efforts.

## Usage
**Business/Asset Owners**: Can use the aggregator to collect CSAFs from providers aligned with their asset inventories and operational environments.

**National CERTs**: May leverage the aggregator to gather CSAFs from domestic vendors and manufacturers recognized as CSAF Providers.

# OASIS Standard
The aggregator adheres to the OASIS CSAF Version 2.0 standard, which has been ratified as an ISO/IEC 20153 international standard. This standard enables structured, machine-readable advisories that support automation in vulnerability disclosure and remediation processes. [OASIS Open CSAF Standard](https://docs.oasis-open.org/csaf/csaf/v2.0/os/csaf-v2.0-os.html)

# Contact
For questions or issues, please submit them via the Issues Tracker on the CISA CSAF Aggregator GitHub repository.

# CSAF Aggregator Role
CISA acts as a mirror and aggregator of CSAF documents from trusted providers. For technical details, refer to the [CISA CSAF Aggregator JSON schema](https://docs.oasis-open.org/csaf/csaf/v2.0/os/csaf-v2.0-os.html#725-role-csaf-aggregator).
 

## How To Be Included in the Aggregator
To be included in the aggregator, CSAF Trusted Providers must ensure each CSAF document includes the following minimum data elements for each vulnerability:

* CVE (Common Vulnerabilities and Exposures)
* CWE (Common Weakness Enumeration)
* CVSS (Common Vulnerability Scoring System) scoring
* Vulnerability Description
* Known Affected Products
* A Remediation entry for the Known Affected Products

These requirements align with best practices for structured vulnerability reporting and ensure interoperability and automation readiness.