![OASIS Logo](https://docs.oasis-open.org/templates/OASISLogo-v3.0.png)

# OASIS Committee Note
-------

# Provenance Use Cases Version 0.1

## Committee Note 01

## 16 May 2025

&nbsp;

#### This stage:
https://docs.oasis-open.org/dps/prov-use/v1.0/cn01/prov-use-v1.0-cn01.md (Authoritative) \
https://docs.oasis-open.org/dps/prov-use/v1.0/cn01/prov-use-v1.0-cn01.html \
https://docs.oasis-open.org/dps/prov-use/v1.0/cn01/prov-use-v1.0-cn01.pdf

#### Previous stage of Version 1.0:
https://docs.oasis-open.org/dps/prov-use/v1.0/cnd01/prov-use-v1.0-cnd01.md (Authoritative) \
https://docs.oasis-open.org/dps/prov-use/v1.0/cnd01/prov-use-v1.0-cnd01.html \
https://docs.oasis-open.org/dps/prov-use/v1.0/cnd01/prov-use-v1.0-cnd01.pdf

#### Latest stage of Version 1.0:
https://docs.oasis-open.org/dps/prov-use/v1.0/prov-use-v1.0.md (Authoritative) \
https://docs.oasis-open.org/dps/prov-use/v1.0/prov-use-v1.0.html \
https://docs.oasis-open.org/dps/prov-use/v1.0/prov-use-v1.0.pdf

#### Technical Committee:
[OASIS Data Provenance Standards (DPS) TC](https://www.oasis-open.org/tc-dps/)

#### Chairs:

Lisa Bobbitt, Cisco, lbobbitt@cisco.com

Bryan Bortnick, IBM, bortnick@us.ibm.com

Fotis Psallidas, Microsoft, Fotis.Psallidas@microsoft.com

#### Secretary:
Kristina Podnar, Data & Trust Alliance, kpodnar@dataandtrustalliance.org 

#### Editors:

Lisa Bobbitt, Cisco, lbobbitt@cisco.com

Duncan Sparrell, sFractal Consulting, duncan@sfractal.comn

#### Related work:
This document is related to:
* fill in metadata spec

#### Abstract:
In today's data driven world, knowing your data is fundamental. Data transparency is critical. 
Trust in the insights and decisions coming from both traditional data and AI applications 
depends on understanding the origin, lineage, and rights associated with the data that feeds them. 
Lack of transparency has real costs, including unnecessary risks and foregone opportunities. 
And yet, many organizations today cannot answer basic data questions without considerable difficulty and investment.

To realize the value of data requires a reliable cross-industry baseline of data transparency. 
The Data Provenance standards propose a solution.
These use case scenarios showcase how the Data Provenance standards support diverse needs across the data ecosystem.

#### Status:
This is a Non-Standards Track Work Product. The patent provisions of the OASIS IPR Policy do not apply.

This document was last revised or approved by the OASIS Data Provenance Standards (DPS) TC on the above date. The level of approval is also listed above. Check the "Latest stage" location noted above for possible later revisions of this document. Any other numbered Versions and other technical work produced by the Technical Committee (TC) are listed at https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=tc-dps#technical.

TC members should send comments on this document to the TC's email list. Others should send comments to the TC's public comment list, after subscribing to it by following the instructions at the "Send A Comment" button on the TC's web page at https://www.oasis-open.org/committees/tc-dps/.

#### Citation format:
When referencing this document the following citation format should be used:

**[PROV-USE-v1.0]**

Provenance Use Cases Version 0.1_. Edited by Lisa Bobbitt, Duncan Sparrell. 16 May 2025. OASIS Committee Note 01. https://docs.oasis-open.org/dps/prov-use/v1.0/cnd01/prov-use-v1.0-cnd01.html. Latest stage: https://docs.oasis-open.org/dps/prov-use/v1.0/cnd01/prov-use-v1.0-cnd01.html.

#### Notices
Copyright &copy; OASIS Open 2025. All Rights Reserved.

Distributed under the terms of the OASIS [IPR Policy](https://www.oasis-open.org/policies-guidelines/ipr/).

The name "OASIS" is a trademark of [OASIS](https://www.oasis-open.org/), the owner and developer of this specification, and should be used only to refer to the organization and its official outputs.

For complete copyright information please see the full Notices section in [Appendix F](#appendix-f-notices).

-------

# Table of Contents

- [1 Introduction](#1-introduction)
  - [1.1 Background: Motivation](#11-background-motivation-for-jadn)
  - [1.1.1 whatever](#111-openc2-and-jadn)
  - [1.2 Purpose](#12-purpose)
  - [1.3 Terminology](#13-terminology)
- [2 Scenario 1 - Healthcare insurance data procurement](#2-information-modeling-overview)
  - [2.1 Persona](#21-defining-information)
  - [2.2 Background(#22-defining-information)
- [3 Scenario 2 - Media consumption pattern dataset for consumer behavior insights](#3-creating-information-models-with-jadn)
  - [3.1 whatever](#31-jadn-overview)
- [4 Scenario 3 - Financial services customer product enablement](#4-advanced-techniques)
  - [4.1 whatever](#41-packages-and-namespaces) 
- [5 Scenario 4 - Enhancing global logistics efficiency through AI-driven tariff harmonization](#4-advanced-techniques)
  - [5.1 whatever](#41-packages-and-namespaces) 
- [Appendix A. Informative References](#appendix-a-informative-references)
- [Appendix B. Acknowledgments](#appendix-b-acknowledgments)
- [Appendix C. Revision History](#appendix-c-revision-history)
- [Appendix D. Frequently Asked Questions (FAQ)](#appendix-d-frequently-asked-questions-faq)
  - [D.1 ask a question here](#d1-jadn-vs-uml-primitive-data-types)
  - [D.2 some more here?](#d2-why-jadn-and-not-rdf)
  - [D.3 and keep going](#d3-why-jadn-and-not-owl)
- [Appendix E. Example whatever](#appendix-e-example-information-model-source)
  - [E.1 something](#e1-music-library)
- [Appendix F. Notices](#appendix-f-notices)

**List of Figures**
 - [Figure 1-1 -- fill in as needed](#figure-1-1----range-of-model-types)


**List of Tables**
 - [Table 3-1 -- fill in as needed](#table-3-1----compound-type-decision-tree)

-------

<!-- Insert a "line rule" (three or more hyphens alone on a new line, following a blank line) before each major section. This is used to generate a page break in the PDF format. -->

# 1 Introduction

put intro here

## 1.1 Background: Motivation for ...

Scenarios 1-4 were defined and prioritized by the [Data & Trust Alliance](https://dataandtrustalliance.org/) in an effort to help users understand how the provenance metadata helps manage data as it is begins it data lifecyle (captured, created, and/or purchased).

### 1.1.1 whatever

add text

## 1.2 Purpose

The purpose of the following use cases is to provide examples of how the provenance metadata may be used to capture the salient information needed to make decisions about the legal use, data protection, data privacy, and data viability given the planned use.

## 1.3 Terminology

This CN uses the definitions contained in the [[Provenance Metadata Specification](#prov-md-v10)], section whatever. The following
additional terms are defined for this document:

 - **whatever:** definition here with ref to where got if we didn't create

 - **next:** definition here with ref to where got if we didn't create


-------

# 2 Scenario 1 - Healthcare insurance data procurement

## 2.1 Persona  
### 2.1.1 Name/ Role  
Bella Ramirez / Procurement Team Lead

### 2.1.2 Background 
Bella holds a BS in Accounting and has over 15 years of experience in the healthcare industry, specializing in procurement. Before her current role, she worked in various capacities within healthcare organizations, including as a contracting specialist and an accounting auditor. This gave her a deep understanding of the technical and procurement of healthcare data.

### 2.1.3 Responsibilities 
- Leading the procurement team in evaluating and acquiring high-quality datasets to improve the company's analytical models.
- Facilitating vendor reviews and ensuring all datasets comply with data provenance standards, including transparent AI data usage, metadata coverage, and regulatory requirements.
- Partnering with the data team charged with integrating new datasets into existing systems ensures that procured data meets their operational needs.
- Collaborating with the legal and compliance departments to ensure data usage aligns with healthcare regulations and company policies.
- Contributing to the success of strategies to leverage data insights for innovative marketing and improved customer trust.

## 2.2 Use case
Bella and her team are evaluating a new dataset that contains comprehensive patient and insurance payment information. This dataset is considered crucial for enhancing the company's predictive analytics models, which forecast healthcare trends, personalize insurance plans, and optimize claim processing.

### 2.2.1 Goals
- Assess metadata coverage: Bella prioritizes the evaluation of the dataset's metadata to ensure it includes essential information like the dataset title, unique metadata identifier, metadata location, and details about data origin and collection methods. This step is crucial for establishing the dataset's lineage, context, and usage restrictions, aligning with the company's data provenance standards.
- Ensure regulatory compliance: By collaborating with the legal department, Bella ensures the dataset for adherence to healthcare data regulations, focusing on confidentiality classification, consent documentation, and data processing and storage geographies. This provides the dataset's use will not breach any legal or ethical boundaries.
- Operational efficiency and integration: Bella validates the dataset's potential impact on operational efficiency by working with the data team. She meets with the team that assesses how well the dataset integrates with existing systems and whether it can provide the expected enhancements to the analytical models without significant overhaul or disruption.
- Strategic use and innovation: Beyond compliance and integration, Bella explores how the dataset can be used to develop innovative marketing strategies and improve customer trust. This involves touching base with the marketing team, which is focused on analyzing the dataset's intent and proprietary data presence to identify new opportunities for personalized customer engagement and service delivery.

### 2.2.2 Challenges
- Balancing the need for detailed, comprehensive data with privacy and confidentiality requirements.
- Ensuring the dataset's metadata is accurate, up-to-date, and compliant with evolving data provenance standards.
-	Integrating new datasets with existing systems and models without compromising data integrity or system performance.
-	Navigating the complex landscape of healthcare regulations and ensuring all data usage is compliant.

### 2.3 How the standards are used
For Bella to ensure the dataset under evaluation meets the standards required for her healthcare insurance company's analytical models, she would assess the following values within the specified metadata:

- Version used for metadata	Bella checks for the specific version number of the metadata schema or standard used, ensuring it's the latest or a widely recognized version to maintain consistency and future-proof the dataset. The version used for metadata is "1.0.0" which indicates the dataset uses the third revision of the 1.0.0 version of the metadata standard, suggesting that it is up to date with current standards.
- Dataset title/name	She evaluates whether the dataset's title is descriptive and precise, clearly reflecting the dataset's content and intended use, facilitating easy identification and retrieval. The title of the dataset is "2024 Comprehensive Patient Care and Insurance Claims Dataset", a descriptive title indicating the dataset's content and scope, including the year for currency.
-Unique metadata identifier	Bella verifies the presence of a unique identifier, like a UUID, ensuring it is correctly formatted and unique to prevent any confusion or overlap with other datasets. A unique identifier, "UUID-1234-5678-9012-3456" ensures this dataset's metadata is distinguishable.
- Metadata unique URL	She examines the URL's accessibility, ensuring it leads directly to a comprehensive metadata page that provides detailed information about the dataset, and checks that the URL is secure and reliable. She uses the provided value of https://example.com/dataset/metadata/UUID-1234-5678-9012-3456, which is a direct link to the dataset's detailed metadata page, providing ease of access for further information.
- Metadata location for datasets feeding the current dataset	Bella assesses this to understand the dataset's lineage and dependencies, ensuring that the metadata for source datasets is easily accessible and well-documented. She uses https://example.com/metadata/sources, a URL that points to metadata for source datasets, establishing the lineage and dependencies of the current dataset.
- Date of previously published version of the dataset	She looks for the date to track the dataset's evolution, ensuring that any updates or revisions are noted and the dataset's version history is clear. "March 15, 2023" indicates when the last version of the dataset was released, helping track updates over time.
- Creator	Bella verifies the creator's identity, ensuring they are reputable and have the necessary expertise. This provides accountability and a reliable point of contact for inquiries. The creator is noted as the "National Health Data Systems,” which Identifies the organization responsible for creating the dataset, adding a layer of trust and accountability.
- Source (if different from Creator)	She checks the source(s) of the data, ensuring transparency and the integrity of the data collection process, significantly if the source differs from the dataset creator. "Nationwide Hospitals Systems, Insurance Providers Ltd." Are specified in the source, which indicates the original data sources, providing context for the data's origin.
- Data origin geography	Understanding the geographical context of the data's origin is crucial for Bella, especially for compliance with regional laws and regulations and for the dataset's applicability to her company's customer base. The geographic location where the data was collected, relevant for regulatory and contextual reasons, is listed as "United States” for the country, “California” for the state, and “Arcata, Eureka, San Francisco” for the cities.
- Dataset creation date	She confirms the dataset's creation date to assess its freshness and relevance to current analytical needs. The metadata lists "January 10, 2024" as the creation date value and indicates when the dataset was compiled, providing context for its currency and relevance of business cases.
- Range of dates for data generation:	Bella evaluates the time frame during which the data was collected, ensuring it is relevant to the current analytical models and reflects recent trends or patterns. "January 1, 2023 - December 31, 2023" dates that are provided show Bella the time during which the data was collected, highlighting the dataset's recency.
- Method	Understanding the data collection or generation methodology is critical for assessing the dataset's reliability and validity: Bella scrutinizes this aspect thoroughly and passes the information on to the data team. “Database feed” is the value in the method metadata field, and in the specification field, Bella notes, "Electronic Health Records Extraction and Insurance Claim Processing Logs" is added. This information describes how the data was collected, providing Bella with insight into its reliability.
- Content type:	She assesses whether the dataset's content type (numerical, textual, multimedia, etc.) is compatible with the company's analytical tools and is suitable for the intended analyses. "SQL” as the value and “Structured Data - Numerical and Categorical" specifies the nature of the dataset, which is crucial for understanding how it can be analyzed.
- Privacy-enhancing technologies (PETs):	Bella confirms whether PETs were applied to the dataset to protect personal data, ensuring the dataset's compliance with privacy regulations and ethical standards. She notes that the metadata indicates a "No”, which confirms that no measures have been taken to protect personal information within the dataset.
- Organizational content classification:	She ensures the dataset's classification aligns with the company's data handling policies, assessing whether its classification is appropriate and clear. "Restricted" indicates the data handling requirements and access restrictions, which is a flag to Bella that the dataset has protected health information (PHI) under the Health Insurance Portability and Accountability Act (HIPAA) and that the medical information must be carefully managed under provincial, state, or other healthcare privacy laws.
- Confidentiality classification:	Bella examines the level of sensitivity assigned to the dataset, ensuring it is adequately secured and that access is appropriately controlled based on its classification. “Private Health Information” reflects the dataset's sensitivity level and dictates security measures.
- Consent location:	Because the dataset involves confidential information, she verifies the location and adequacy of consent documentation, ensuring compliance with legal standards. https://example.com/dataset/UUID-1234-5678-9012-3456/consent1.html points to where consent documentation is kept, which Bella forwards to the legal department for review and determination of whether the consent meets the organization’s legal obligations for processing.
- Data processing geography:	Bella assesses any geographical restrictions on where the data can be processed, ensuring compliance with legal and regulatory requirements regarding data processing locations. The metadata lists "United States” for the country and “California” for the state. Bella sees this as a flag since from experience, she knows that California’s data privacy laws don’t have geographic restrictions on data processing. She flags the information for legal department review.
- Data storage geography:	She checks for any geographical restrictions on where the data is stored, which is crucial for adherence to data sovereignty laws and protecting sensitive information. The metadata lists "United States” for the country and “California” for the state. Again, this is a flag for Bella as she knows that California’s data privacy laws don’t have geographic restrictions on data storage. However, she knows that additional protections require special handling of personal healthcare data, so she checks in with the legal department for a final determination.
- License to use:	Bella reviews the metadata in this category but passes along to the legal team information about the terms under which the dataset can be used, including any restrictions or obligations, to ensure the company's use of the dataset is legally sound and in line with the licensing terms. "License details available upon request from the Data Governance Department, National Health Data Repository, contactme@example.com" is listed and provides information on how to access terms of use. Bella sent an email asking for clarification about the license to use the data under the name "2024 Comprehensive Patient Care and Insurance Claims Dataset".
- Intent:	She evaluates the purpose of the dataset's creation, ensuring it aligns with her company's intended use and supports identified use cases without misalignment or misuse. The intent in the metadata indicates “AI” use and specifies “Pre-Training,” which aligns with the use cases and requirements specified by the data team. Bella can gain insights from this information, along with the method metadata and dates generated, whether the data cost aligns with the organization’s value assessment.
- Proprietary data presence:	Bella assesses whether the dataset contains proprietary information, ensuring its use does not infringe on intellectual property rights and is consistent with contractual agreements. All the values are empty, which indicates to Bella that the data is free to be used by her company without infringing on proprietary rights.

### 2.4 Outcome 
Bella met with the legal department and the data team, to incorporate their assessment into the procurement analysis package. After investigating, the legal team determined that the data supplier mistakenly tagged the data processing and storage metadata incorrectly and had to correct the metadata associated with the dataset before the procurement process could proceed. This delayed the data procurement process by four business days. However, by successfully evaluating and integrating the new dataset, Bella ensures that the organization is well-positioned to positively impact the company's business operations, including enhanced analytical capabilities, improved customer trust, and the development of responsible AI applications. This will align with the company's business considerations and set a benchmark for efficient and trustworthy data usage in the healthcare insurance industry.

 
-------

# 3 Scenario 2 - Media consumption pattern dataset for consumer behavior insights

blah blah

# 4 Scenario 3 - Financial services customer product enablement

-------
# 5 Scenario 4 - Enhancing global logistics efficiency through AI-driven tariff harmonization

blah blah



-------

# Appendix A. Informative References

<!-- Required section -->

This appendix contains the informative references that are used in this document.

While any hyperlinks included in this appendix were valid at the time of publication, OASIS cannot guarantee their long-term validity.

EDITOR's NOTE: the following are cribbed from another CN and just included as examples.
We will need to delete and replace with ones relative to this CN

###### [ASN.1]
Recommendation ITU-T X.680 (2021) *Information technology - Abstract Syntax Notation One (ASN.1): Specification of basic notation* 

###### [JADN-v1.0]
JSON Abstract Data Notation Version 1.0. Edited by David Kemp. 17
August 2021. OASIS Committee Specification 01.
https://docs.oasis-open.org/openc2/jadn/v1.0/cs01/jadn-v1.0-cs01.html.
Latest stage:
https://docs.oasis-open.org/openc2/jadn/v1.0/jadn-v1.0.html.

###### [JSONSCHEMA]
Wright, A., Andrews, H., Hutton, B., *"JSON Schema Validation"*,
Internet-Draft, 16 September 2019,
https://tools.ietf.org/html/draft-handrews-json-schema-validation-02,
or for latest drafts: https://json-schema.org/work-in-progress.

###### [NTIA-SBOM]
NTIA Multistakeholder Process on Software Component Transparency, "SBOM At A Glance", April 2021,   https://ntia.gov/sites/default/files/publications/sbom_at_a_glance_apr2021_0.pdf

###### [RFC3444]
Pras, A., Schoenwaelder, J., "On the Difference between
Information Models and Data Models", RFC 3444, January 2003,
https://tools.ietf.org/html/rfc3444.

###### [RFC7049]
Bormann, C., Hoffman, P., *"Concise Binary Object Representation
(CBOR)"*, RFC 7049, October 2013,
https://tools.ietf.org/html/rfc7049.

###### [RFC8610]
Birkholz, H., Vigano, C. and Bormann, C., "Concise Data
Definition Language (CDDL): A Notational Convention to Express
Concise Binary Object Representation (CBOR) and JSON Data
Structures", RFC 8610, DOI 10.17487/RFC8610, June 2019,
https://www.rfc-editor.org/info/rfc8610

###### [UML]
"Unified Modeling Language", Version 2.5.1, December 2017,
https://www.omg.org/spec/UML/2.5.1/About-UML/

###### [YTLee]
Lee, Y. (1999), *Information Modeling: From Design to
Implementation*, IEEE Transactions on Robotics and Automation,
[online],
https://tsapps.nist.gov/publication/get_pdf.cfm?pub_id=821265
(Accessed October 5, 2022)


-------

# Appendix B. Acknowledgments


## B.1 Special Thanks

The DPS TC thanks the following individuals for their
assistance in the development of this Committee Note:

 - fill in

## B.2 Participants

The following individuals have participated in the creation of this document and are gratefully acknowledged:

| First Name | Last Name  | Company                                        |
|------------|------------|------------------------------------------------|
| fill       | in         | fill in                                        |
| fill       | in         | fill in                                        |
| fill       | in         | fill in                                        |

-------

# Appendix C. Revision History
| Revision           | Date       | Editor      | Changes Made          |
|:-------------------|:-----------|:------------|:----------------------|
| prov-uc-v1.0-cn01-wd01.md | 2025-05-16 | David Kemp | Initial working draft / CND01 |
| prov-uc-v1.0-cn01-wd02.md | 2023-x-x | David Kemp | Second WD / CN01 candidate |

-------

# Appendix D. Frequently Asked Questions (FAQ)

This appendix responds to a variety of Frequently Asked Questions
regarding ....

## D.1 ask a question herr

put answers here


## D.2 another question?

another answer


## D.3 another question?

answer


------

# Appendix E. Example whatever

## E.1 whatever


------

# Appendix F. Notices

Copyright &copy; OASIS Open 2023. All Rights Reserved.

All capitalized terms in the following text have the meanings assigned to them in the OASIS Intellectual Property Rights Policy (the "OASIS IPR Policy"). The full [Policy](https://www.oasis-open.org/policies-guidelines/ipr/) may be found at the OASIS website.

This document and translations of it may be copied and furnished to others, and derivative works that comment on or otherwise explain it or assist in its implementation may be prepared, copied, published, and distributed, in whole or in part, without restriction of any kind, provided that the above copyright notice and this section are included on all such copies and derivative works. However, this document itself may not be modified in any way, including by removing the copyright notice or references to OASIS, except as needed for the purpose of developing any document or deliverable produced by an OASIS Technical Committee (in which case the rules applicable to copyrights, as set forth in the OASIS IPR Policy, must be followed) or as required to translate it into languages other than English.

The limited permissions granted above are perpetual and will not be revoked by OASIS or its successors or assigns.

This document and the information contained herein is provided on an "AS IS" basis and OASIS DISCLAIMS ALL WARRANTIES, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTY THAT THE USE OF THE INFORMATION HEREIN WILL NOT INFRINGE ANY OWNERSHIP RIGHTS OR ANY IMPLIED WARRANTIES OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE.

The name "OASIS" is a trademark of [OASIS](https://www.oasis-open.org/), the owner and developer of this specification, and should be used only to refer to the organization and its official outputs. OASIS welcomes reference to, and implementation and use of, specifications, while reserving the right to enforce its marks against misleading uses. Please see https://www.oasis-open.org/policies-guidelines/trademark/ for above guidance.

