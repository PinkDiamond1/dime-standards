# DIME Standards

This repository includes [DIME](https://www.worldbank.org/en/research/dime)'s
commitments to high-quality research.
In the spirit of transparency,
we are developing and version-controlling
DIME's standards on GitHub.
This repository is maintained by the
[DIME Analytics team](https://www.worldbank.org/en/research/dime/data-and-analytics).

There are two components to this repository:

* **[DIME Research Standards](https://github.com/worldbank/dime-standards#dime-research-standards)**
* **[DIME Coding Standards](https://github.com/worldbank/dime-standards/#dime-coding-standards)**

## DIME Research Standards

### Pillar 1 - Research Ethics
- DIME Researchers must secure ethics approval from an institutional review board (IRB) and, if applicable, any relevant authority in the study location, for studies directly involving human subjects or using personally-identifying information.
- All DIME team members that handle personally-identifiable information must have up-to-date Human Subjects Research Certification.
- DIME staff must ensure confidentiality, privacy, and anonymity of study participants;
study participants must have the opportunity to provide [informed consent](https://github.com/worldbank/dime-standards/tree/master/dime-research-standards/pillar-1-research-ethics/research-ethics-resources/informed-consent-templates), and revoke that consent at any time.

For details and implementation resources, see the [Research Ethics Guidelines](https://github.com/worldbank/dime-standards/tree/master/dime-research-standards/pillar-1-research-ethics)

### Pillar 2 - Research Transparency
- All DIME projects must be registered prior to receiving implementation funding.

For implementation resources, see the [Research Transparency Guidelines](https://github.com/worldbank/dime-standards/tree/master/dime-research-standards/pillar-2-research-transparency)

###  Pillar 3 - Research Reproducibility
- All DIME projects will use GitHub to document data work.
- DIME Research assistants will regularly participate in peer code review sessions.
- All DIME projects will have a [master script](https://dimewiki.worldbank.org/wiki/Master_Do-files) that runs all the other
scripts that are needed for the project, in order.
- *Computational Reproducibility* must be verified by DIME Analytics prior to publication for all DIME Working Papers
and academic publications.

For implementation resources, see the [Research Reproducibility Guidelines](https://github.com/worldbank/dime-standards/tree/master/dime-research-standards/pillar-3-research-reproducibility)

###  Pillar 4 - Data Security
- All personally-identifiable data must be stored and transferred securely, including in communication with field staff. 
  - All servers for data collection must be [encrypted](https://dimewiki.worldbank.org/wiki/Encryption) both
  in transit and at rest.
  - All identified data must be stored only in securely encrypted locations,
  and must always be encrypted when shared, even if shared only within the project team
  - All DIME projects must follow the [DIME Data Back-up Protocols](https://github.com/worldbank/dime-standards/blob/master/dime-research-standards/pillar-4-data-security/data-security-resources/onedrive-backup-guidelines.md)

For implementation resources, see the [Data Security Guidelines](https://github.com/worldbank/dime-standards/tree/master/dime-research-standards/pillar-4-data-security)

###  Pillar 5 - Data Publication
- Data must be de-identified prior to publication, DIME Analytics can assist with assessing the risk of statistical disclosure.
- All DIME publications must include a replication package, including a citation or reference to the data in the [World Bank Microdata Catalog](https://dimewiki.worldbank.org/wiki/Microdata_Catalog) and a GitHub repository containing the code required for replication of the paper.
- Data must be deposited into the World Bank's [Development Data Hub](https://datacatalog.worldbank.org/) no later than six months after it is acquired, with the
provision to also later deposit any revisions or updates, as per the World Bank Procedure on Development Dataset Acquisition,
Archiving and Dissemination

For implementation resources, see the [Data Publication Guidelines](https://github.com/worldbank/dime-standards/tree/master/dime-research-standards/pillar-5-data-publication)


## DIME Coding Standards

### DIME Data Map

The DIME data map provides a high quality professional framework for planning data work.

- For a general discussion on the usages and benefits, see the [Data Map article](https://dimewiki.worldbank.org/Data_Map) on the DIME Wiki.
- To download our Data Linkage Table template [click here](https://github.com/worldbank/dime-standards/blob/data-map/dime-coding-standards/data-map/templates/data-linkage-table-template.xlsx?raw=true)
- For an example of a Data Map with a Data Linkage Table, Master datasets and Data Flow Charts, see [here]()

### Style guides

DIME code should adopt the following guides:

- Python: [PEP 8](https://www.python.org/dev/peps/pep-0008/)
- R: [Tidyverse style guide](https://style.tidyverse.org/)
- Stata: DIME Analytics style guide (see the Appendix in the [DIME Data Handhook](https://worldbank.github.io/dime-data-handbook/))

### Code review

- Department-wide peer code review rounds are held every quarter and all DIME and DIME-affiliated projects can sign up [here](https://survey.wb.surveycto.com/collect/code_review_sign_up?caseid=).
- Checklists to prepare and review code for different tasks are available [here](https://github.com/worldbank/dime-standards/tree/master/dime-coding-standards/checklists).
