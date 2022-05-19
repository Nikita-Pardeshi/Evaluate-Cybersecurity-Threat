# Evaluate Cybersecurity Threat

### A data visualization mini-project using Highcharts in JS


This is part of a cyber risk project for the NSA. Their task is to help the NSA develop new methods for prioritizing cyber risk among Defense Industrial Base companies. They are focusing on contract/supply chain risk as the key dimension of overall cyber risk - essentially hoping to build a model of how likely a defense company is to be targeted for cyber espionage based on their products and subcontractors.

The key database for analyzing & quantifying contract risk is the [USASpending](https://www.usaspending.gov/explorer/agency) website, which compiles comprehensive government award data from across federal agencies. We believe this data - properly understood - can meaningfully improve the security of America's industrial base.
Because we are trying to map out supply chains based on text data we think that NLP and network analysis would likely be the most relevant approaches. 

For a bit more context, in essence we are trying to use the government's [list of critical technologies](https://www.whitehouse.gov/wp-content/uploads/2022/02/02-2022-Critical-and-Emerging-Technologies-List-Update.pdf) to identify important subcontractors within the defense industrial base who supply those products or inputs to them. From an adversarial perspective, the most important subcontractors to find are ones that are either pervasive (appearing in many critical supply chains) or provide a unique product (and are therefore a single point of failure).

The important columns of concern in the [Subcontractors dataset](https://github.com/Nikita-Pardeshi/Evaluate-Cybersecurity-Threat/Dataset_Contract_Sub-Awards.csv) are subcontractors' company info, geographical presence, and description of services rendered etc. and this project mainly focuses on the relationships between the subcontractors and their parent companies and finding important subcontractors based on 2 critical criteria defined by the NSA: 

* Subcontractors appearing in majority of the supply chain or contracts.
* Subcontractors that provide with a unique product.

More details about the problem statement can be found [here](https://github.com/Nikita-Pardeshi/Evaluate-Cybersecurity-Threat/blob/51a4f3280543129cf309e15b839b843bf365a391/SC-NSA-24-%20Cyber%20Risk%20Management%20and%20Prioritization-FINAL%20(1)%20(1).pdf)
